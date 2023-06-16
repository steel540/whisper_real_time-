# Real time whisper 中英文

PaulGiver已經把原本[1]改成中文版本，在使用情境中可以中文與英文交雜，辨識率都還不錯(medium版本)，如果GPU能力夠的話建議使用medium版本以上，或是在意辨識速度者可以使用base或tiny，安裝方程序必須先參考[2]文件做安裝，之後只需要安裝兩個套件皆可完成Real time whisper

第一個

pip install SpeechRecognition

第二個

pip install PyAudio

如果需要細部修改參數，建議可以參考原作者文件[3]

[1] [https://github.com/davabase/whisper_real_time](https://github.com/davabase/whisper_real_time) 

[2] [https://paulgiver.super.site/whisper-快速安裝教學-windows-10](https://paulgiver.super.site/whisper-%E5%BF%AB%E9%80%9F%E5%AE%89%E8%A3%9D%E6%95%99%E5%AD%B8-windows-10)

[3] [https://github.com/openai/whisper](https://github.com/openai/whisper)
