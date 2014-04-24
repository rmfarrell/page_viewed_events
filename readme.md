##Create custom events that fire when the viewport reaches certain thresholds

Useful for tracking

See index.html for implementation

takes two parameters:
1. An array of percentages as integers that represent percentage of page viewed
2. a container element (like body)

The class returns an array of custom events

The events are triggered when the viewport reaches each percentage in the array

The event follows the naming convention of "viewed-" + [number]

Dependencies: none

 