### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Choreograph a Dance

## Step 1
Search the room to find what 4 dances are needed to open the door and the sequence they need to be in. Then use the ``||hoc2024:dance steps||`` block to sequence the 4 dances into the correct oder.

#### ~ tutorialhint
There are 4 posters on the wall with numbers. Those posters will tell you the sequence the 4 ``||hoc2024:dance steps||`` need to be placed.


```ghost
    hoc2024.dancea()
```
```template
    hoc2024.dancea(DancesA.Move1)
    hoc2024.dancea(DancesA.Move1)
    hoc2024.dancea(DancesA.Move1)
    hoc2024.dancea(DancesA.Move1)
```

```package
hoc2024-ts=github:ReWrite-Media/hoc2024-ts#v0.0.50
```