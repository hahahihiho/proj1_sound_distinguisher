# Deep Learning sound distinguisher

- 음성 분석, 기본 딥러닝 모델로 음성 분리



## Folder 0,1 : Learn and Analyze the data

> 0 : 라이브러리 연습
>
> > * scipy, simpleaudio, pydub, matplotlib, keras, speech_recognition 등
>
> 1 : 데이터 분석
>
> > * 음성데이터 분석
> >
> > * 음성 특징추출(feature extraction)(stft,mfcc...)
> >
> > *  번외 프로젝트(미완결)
> >   >
> >   > * 스튜어디스의 목소리, 일반인 목소리 Standardization,PCA,DeepLearning
> >   >* 같은단어 목소리 출석
> >   > * 자신만의단어 로그인(글자인식+화자인식)



##  Folder 2 : Voice Distinguish(Voice Filter)

> 2 : 화자 분리
> * Goal
> ![Goal](/README_IMG/goal.png)
>
> * Feature Extraction
>
>    > STFT,MFCC,RMSE,Zero-crossing,spectral_centroid,spectral_bandwidth,spectral_rolloff
>
> *   Deep-Learning Model
>
>    > DNN
>    > (tried - conv1d) but the result was similar
>
> * Result
> ![Voice_Filter_Model](/README_IMG/Goal_Result.png)
> * Improvements
>   
>    > HMM, GMM, various and more complex Model by using tensor-flow
>	 > Done by less data, General data
> 
>