## 1. Video-based automatic people counting

### Meta Data
- DOI: https://doi.org/10.1016/j.compind.2024.104195  
- Journal: Computers in Industry  
- Publisher: Elsevier  
- Year: 2024

### Abstract

- Market demand of APC.
- Existing solution/similar tech.
- What rail replacement bus services.
- What existing paper does(uses dataset and don't deploy model)
- what this paper will do(trial occured both on and off bus use cases).

The primary objective of this research is to evaluate and compare the performance and practical implications of a video-based APC system when deployed in on-vehicle versus off-vehicle settings. The study aims to highlight differences in accuracy, operational considerations, and the validity of underlying assumptions for both scenarios within the public transport sector.
### Introduction
- Overcrowding
- Solved by APC.
### Contributions

1. **First comparative evaluation**: It provides the first exploration of key configuration choices (on-bus vs. off-bus and camera positions) for a low-cost, compute-efficient video-based passenger counter in real-world services.

2. **Operational insights**: It offers novel insights into practical factors (weather, lighting, occlusions) that influence the performance of line-of-interest passenger counting.

3. **Implementation guidance**: The study provides practical guidance for managers and researchers on assessing the suitability of video-based APC solutions for specific use-cases

### Methodology
### Models
### Results
### Limitations

1. **Environmental Sensitivity**: Video-based systems remain the most susceptible to external variables like lighting extremes (direct sunlight) and weather (rain).
2. **Occlusions**: Heavy rain and the use of umbrellas were observed sources of error in the off-bus trials. In on-bus trials, high density caused occlusions that hampered tracking.
3. **Hardware Constraints**: The fixed-focus lens with a 62° field of view sometimes limited visual coverage, especially in the confined rear-door areas of buses.
4. **Systematic Errors**: The study noted that detection-based "line-of-interest" counting can accumulate error over time, unlike direct "head-count" (region-of-interest) methods.

## Keywords
- APC - Automatic People Counting
## Technology
