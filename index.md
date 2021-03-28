## DeepClassical

以下展示的音频文件用于DeepClassical的听众实验。MIDI文件使用GarageBand的Strings Staccato音色进行渲染，所有乐曲都统一在默认速度 (bpm=120) 和力度 (velocity=90) 下进行。因此，参与者可以关注乐谱内容的差异，而不是表演风格。

问卷开头提供了时长42秒的BWV 1001.4 Presto节选作为参考 (该片段不包括在测试样本中)。

<audio id="audio" controls="" preload="none">
<source id="mp3" src="Re_Bach.mp3">
</audio>

参与者需要在问卷中回答三个不同的问题。这三个问题依次是开头、中间和结尾的辨别问题，要求参与者选择从每道题选出节选自巴赫创作的乐曲的音频。每个问题包括三个音频片段：一个巴赫原作和两个分别由DeepClassical及其变体生成的作品。

### 开头

<table>
    <tr>
        <th>J.S. Bach</th>
        <th><audio id="audio" controls="" preload="none">
            <source id="mp3" src="Q1_Bach.mp3">
            </audio></th>
    </tr>
    <tr>
        <th>DeepClassical</th>
        <th><audio id="audio" controls="" preload="none">
            <source id="mp3" src="Q1_DC.mp3">
            </audio></th>
    </tr>
    <tr>
        <th>DeepClassical-linear</th>
        <th><audio id="audio" controls="" preload="none">
            <source id="mp3" src="Q1_DCL.mp3">
            </audio></th>
    </tr>
</table>
  
<br> 
  
### 中间

<table>
    <tr>
        <th>J.S. Bach</th>
        <th><audio id="audio" controls="" preload="none">
            <source id="mp3" src="Q2_Bach.mp3">
            </audio></th>
    </tr>
    <tr>
        <th>DeepClassical</th>
        <th><audio id="audio" controls="" preload="none">
            <source id="mp3" src="Q2_DC.mp3">
            </audio></th>
    </tr>
    <tr>
        <th>DeepClassical-linear</th>
        <th><audio id="audio" controls="" preload="none">
            <source id="mp3" src="Q2_DCL.mp3">
            </audio></th>
    </tr>
</table>
  
<br>
  
### 结尾

<table>
    <tr>
        <th>J.S. Bach</th>
        <th><audio id="audio" controls="" preload="none">
            <source id="mp3" src="Q3_Bach.mp3">
            </audio></th>
    </tr>
    <tr>
        <th>DeepClassical</th>
        <th><audio id="audio" controls="" preload="none">
            <source id="mp3" src="Q3_DC.mp3">
            </audio></th>
    </tr>
    <tr>
        <th>DeepClassical-linear</th>
        <th><audio id="audio" controls="" preload="none">
            <source id="mp3" src="Q3_DCL.mp3">
            </audio></th>
    </tr>
</table>
  
<br>
  
最后，请欣赏基于参考音频由DeepClassical生成的音乐片段。 :)

<audio id="audio" controls="" preload="none">
<source id="mp3" src="Re_DC.mp3">
</audio>

## MuseRNN

为了将MIDI文件转换为音频文件，所有的乐曲使用GarageBand中的Guqin音色渲染，并且全都统一在默认速度 (bpm=60) 和默认力度 (velocity=90) 演奏。因此，最终所有音频的演奏风格都是统一的，可以消除其对参与者判断的影响。

本次测试中，参与者需要根据音频进行二元判断：1) 该音乐由人工智能生成，以及2) 该音乐并非由人工智能生成。在测试前，参与者被告知所有音频的前半段节选自中国传统音乐，需要注意后半段的内容是否与前半段相似，但所有参与者并未得知所有音频的后半段均由模型生成。每个参与者需要完成六次听辨，而这六次听辨的音频分别来自于六个不同的音乐生成模型。以下是实验中的部分生成样例。

<table>
    <tr>
        <th>DBDPCG</th>
        <th><audio id="audio" controls="" preload="none">
            <source id="mp3" src="DBDPCG.mp3">
            </audio></th>
    </tr>
    <tr>
        <th>BDPCG</th>
        <th><audio id="audio" controls="" preload="none">
            <source id="mp3" src="BDPCG.mp3">
            </audio></th>
    </tr>
    <tr>
        <th>DDPCG</th>
        <th><audio id="audio" controls="" preload="none">
            <source id="mp3" src="DDPCG.mp3">
            </audio></th>
    </tr>
    <tr>
        <th>DBDPG</th>
        <th><audio id="audio" controls="" preload="none">
            <source id="mp3" src="DBDPG.mp3">
            </audio></th>
    </tr>
    <tr>
        <th>MidiNet</th>
        <th><audio id="audio" controls="" preload="none">
            <source id="mp3" src="MidiNet.mp3">
            </audio></th>
    </tr>
    <tr>
        <th>Melody RNN</th>
        <th><audio id="audio" controls="" preload="none">
            <source id="mp3" src="Melody RNN.mp3">
            </audio></th>
    </tr>
</table>
![image](https://user-images.githubusercontent.com/81492902/112756085-128f6600-9016-11eb-89e4-331240478d12.png)
