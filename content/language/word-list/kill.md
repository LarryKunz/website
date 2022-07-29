# Term: Kill  (and derivatives, including *killed*)

## Definition
The user- or process-initiated ending of a thread or process.

## Recommendation
Strongly consider replacing.

## Recommended Replacements
- end
- stop
- cancel
- close

## Unsuitable Replacements
- terminate
- abort

## Rationale
The word *kill* is undoubtedly violent, meeting the INI’s evaluation framework's [second-order concerns](https://inclusivenaming.org/word-lists/tier-2/). There is no need to use it in a light or technical context, as the implications of putting something to death are beyond the scope of such contexts.

The replacement terms cover essentially every situation in which *kill* is used, and they don’t unnecessarily anthropomorphize technology as the original term does.

However, we acknowledge that, particularly in UNIX-based contexts, the term is used too thoroughly to be replaced immediately. Therefore, we recommend replacement where possible to remove the violent, militaristic, and anthropomorphizing connotations.
