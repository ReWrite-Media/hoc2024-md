### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Choreograph a Dance

## Dance like no one's watching
The Agent needs help choreographing a dance sequence for the show. Use the *hoc.dance()* function to sequence a dance choreography for the Agent.

```python
# *hoc.dance()* can use the following dances.
# Dance.Move1, Dance.Move2, Dance.Move3 all the way through Dance.Move14
hoc.dance(Dance.Move1)
```

```python-template
for i in range(3):
    hoc.dance(Dance.Move1)
hoc.dance(Dance.Move2)
hoc.dance(Dances.Move3)
hoc.dance(Dances.Move4)
```

```package
hoc2024-ts=github:ReWrite-Media/hoc2024-ts/dance#v0.0.70
```