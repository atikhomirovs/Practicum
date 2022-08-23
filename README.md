# Description of the data
### Technological process
* Rougher feed — raw material
* Rougher additions (or reagent additions) — flotation reagents: Xanthate, Sulphate, Depressant
* Xanthate — promoter or flotation activator;
* Sulphate — sodium sulphide for this particular process;
* Depressant — sodium silicate.
* Rougher process — flotation
* Rougher tails — product residues
* Float banks — flotation unit
* Cleaner process — purification
* Rougher Au — rougher gold concentrate
* Final Au — final gold concentrate

### Parameters of stages
* air amount — volume of air
* fluid levels
* feed size — feed particle size
* feed rate

## Feature naming
Here's how you name the features:
`[stage].[parameter_type].[parameter_name]`

Example: rougher.input.feed_ag
Possible values for `[stage]`:
* rougher — flotation
* primary_cleaner — primary purification
* secondary_cleaner — secondary purification
* final — final characteristics

Possible values for `[parameter_type]`:
* input — raw material parameters
* output — product parameters
* state — parameters characterizing the current state of the stage
* calculation — calculation characteristics

# Goal
Build a prototype of a machine learning model that predicts the amount of gold recovered from gold ore.

# Libraries
pandas, sklearn, numpy, matplotlib
