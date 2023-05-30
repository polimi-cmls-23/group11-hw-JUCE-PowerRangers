# group11-hw-JUCE-PowerRangers

The aim of this homework is to analyze an existing JUCE plugin. The plugin we chose is called BiquadLimiter. The BiquadLimiter plugin implements a biquad filter which has a dynamic range limiter in front of the feedback section (Limiter1) and another limiter in the final section (Limiter2). Through the user interface, it’s possible to set the following values: filter coefficients, filter cutoff frequency, the Q and the filter type (LPF, BPF, HPF). The frequency display shows the filter frequency response and it's possible to see the change of its behavior when one of the parameters is changed. The two limiters prevent the output from becoming too loud when either the filter is unstable or the input is too loud. In addition, the front limiter generates a unique sound by feeding the compressed sound back to the biquad filter.


<img width="658" alt="GUIplugin" src="https://github.com/polimi-cmls-23/group11-hw-JUCE-PowerRangers/assets/101117878/aa3ed4ef-8f4d-43b5-bd72-b08e2419aac1">

