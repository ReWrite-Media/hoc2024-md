### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Choose the costumes

## Step 1
Time to pick out some costumes! Sequence together the different ``||hoc2024:head, body, and legs||`` costumes you want the Agent to change into during the show.

#### ~ tutorialhint
You can use a ``||loops:for loop||`` instead of multiple blocks to keep a specific costume on for longer.


```ghost
    hoc2024.costume()
    for (let i = 0; i < 5; i++) {}
```
```template
    hoc2024.costume(HeadWear.Head2, MidWear.Mid2, LowerWear.Lower2)
    hoc2024.costume(HeadWear.Head2, MidWear.Mid2, LowerWear.Lower2)
    hoc2024.costume(HeadWear.Head2, MidWear.Mid2, LowerWear.Lower2)
    hoc2024.costume(HeadWear.Head2, MidWear.Mid2, LowerWear.Lower2)
    for (let i = 0; i < 3; i++) {
        hoc2024.costume(HeadWear.Head2, MidWear.Mid2, LowerWear.Lower2)
    }
    hoc2024.costume(HeadWear.Head2, MidWear.Mid2, LowerWear.Lower2)
    hoc2024.costume(HeadWear.Head2, MidWear.Mid2, LowerWear.Lower2)
    hoc2024.costume(HeadWear.Head2, MidWear.Mid2, LowerWear.Lower2)
    hoc2024.costume(HeadWear.Head2, MidWear.Mid2, LowerWear.Lower2)
```

```package
hoc2024-ts=github:ReWrite-Media/hoc2024-ts#v0.0.50
```