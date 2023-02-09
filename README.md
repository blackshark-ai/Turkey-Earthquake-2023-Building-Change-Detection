[![Blackshark.ai](BSK-logo-small.png)](https://blackshark.ai/)

# Turkey/Syria Earthquake Disaster 2023 <br> Building Footprints and Change Detection

On February 6th, 2023, a catastrophic earthquake struck southern and central Turkey and northern Syria
(for more information see [Wikipedia](https://en.wikipedia.org/wiki/2023_Turkey%E2%80%93Syria_earthquake]).
[Maxar Technologies](https://maxar.com/) released satellite imagery of the area soon afterwards.
This repository builds on the public data released by Maxar Technologies which can be retrieved from their
[open data platform](https://www.maxar.com/open-data/turkey-earthquake-2023).

## Contents

The repository contains building footprints derived from the original open data imagery and results from our
change detection.

The footprints are based on Maxar's open data imagery available as of February, 9th, 2023.
 
Our change detection was run against Maxar's Vivid basemap (2021 vintage) which is comprised of
analysis-ready data from 2018 to 2021. The raw output of our change detection was then manually reviewed and
cleaned up (missing buildings due to cloud cover or cloud shadows etc.) Please note that we didn't do any
postprocessing and that images used for comparison may be up to 4 years old. As such, changes might be due to
a variety of reasons, such as detection errors, regular building changes, and collapsed buildings. So take
the changes with a grain of salt.

## License

The data here is licensed under the 
[Create Commons Attribution-NonCommercial license](LICENSE) (CC-BY-NC).

## Get in touch

For inquiries please [get in touch](https://blackshark.ai/inquires/). 
For technical matters just use Github issues.

## Donate!

If you would like to help, supporte organizations that help survivors and coordinates rescue operations.
We recommend to support Ahbap, a very active non-governmental organization: https://ahbap.org/disasters-turkey
