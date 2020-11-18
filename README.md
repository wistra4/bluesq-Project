# How to use m4lpatch

### autoSQ
左上のtoggleでオンオフをします．  
1番上の列はランダムに生成したmidi  
2番目の列は1列目のmidiの1オクターブ高い音  
3番目は階段状に上がる音  
4番目は1列目とは異なるランダムのmidiになっています．  
一度再生するとtoggleをオフにするとオフにした時の音声がループされます．  
最初は左から音が流れていきますが，ランダムで右から音が流れるようになります．  
Upbutton,downbuttonでsqのspeedの調整ができます．  
Midichangeは16小節に1度起動してsq内のmidiを変更しますが，buttonを押すことで好きな時にmidiを変えることもできます．  

### visual_oscillator
左側のブロックから波形を選びADSRを動かすことができます．  
ADSRはtoggleのオンオフの度にリセットされます．  
右側は波形を表しており，bungを押すと4パターン表示が変わります．  

### active_filter
上側の2つはlowpathfilterでresonanceをかけています．  
下側の2つはresonancefilでreduxのような効果を持っています．  
左側が左側の音声，右側が右側の音声です．左右で若干動きが異なります．  

### double_delay
左右で別々にdelayが動いています．  
それぞれ3パターンのdelayの組み合わせがあり，それぞれ異なる効果を生み出します．  
2重にdelayをかけることで空間が生まれています．  
