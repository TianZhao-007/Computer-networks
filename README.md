# Computer-networks

## Signal and simple informatics  

### Modulation  
1. AM/FM/PM  
  Amplitude modulation调幅  
  Frequency modulation调频  
  Phase Modualtion相位调制  
  
2. ASK/FSK/PSK  
  ASK(Amplitude-shift keying)幅度偏移调制  
  通过carrier载波的幅度变化来表示数字信号
  
  FSK(Frequency-shift keying)频率偏移调制  
  利用频率差异的信号来传送信号  
  
  PSK(Phase-shift keying)相位偏移调制  
  利用相位差异的信号来传送信号  
  
### Multiplexing复用技术  
[link to learn](https://blog.csdn.net/kai_locust/article/details/108476147?utm_medium=distribute.pc_relevant.none-task-blog-baidujs_utm_term-0&spm=1001.2101.3001.4242)
TDM,SDM,FDM,WDM  

TDM:Time-division multiplexing  
SDM：Space-division multiplexing  
FDM：Frequency-division multiplexing  
WDM: Wave-division multiplexing  

### Encoding  
[click here to learn](https://www.daimajiaoliu.com/daima/479be07e2100408)  
4b/5b: Give 4 bits, rewirte as 5 bits  

- Encoding question: why is ‘encoding’ bits into a modulated signal so important?  
What problems are you solving?  
Make the signal clearer overall, by ensuring a *higher rate of transitions* (easier to  
detect), to avoid the 100000…000…000 vs “are-you-dead” problem.  
AND provide a mechanism for *clock-recovery*, so you know how wide a bit is, i.e.  
what the data rate actually is, and where the bit boundaries are (clock sync).  

Mancherster:用电压变化来分辨0、1；高->低 是0； 低->高 是1；
- 优点： 提供一种同步机制，保证接收端和发射端信号同步。  
- 缺点： 编码频率高，带宽大一倍（和NRZ相比）  

### baseband/passband/broadband
[click here to lean](https://youtu.be/Ph9N0XGmi-E)  

### Nyquist limit and shannon capacity limit  
Nyquist limit = 2 * frequency * log2 (V)  bit/s  
Reliable capacity = Baudrate * log2 (1+signal/noise)  

- Nyquist example: Given a 1MHz wave, amplitude modulated to 8 levels, what’s the  
potential datarate achievable?  
2*1MHz*log2(8)=6Mb/s – students may struggle why they can fit two bits into a  
single wave, you need to look at it like a 180degree phase-shift-key  

### check some frequency understanding
1. why we care about frequency things?  
Nature prefers waves, and blocks some! Losing high/low frequencies plays havoc  
with your nice square signals. Main message is just that underpinning digital  
signals are real analogue waves across a range and combination of frequencies,  
that we can take advantage of.   

2.Why do we use Frequency Division Multiplexing rather than Frequency Shift Keying?  
Because electronics can be tuned to a frequency and use it as a dedicated  
(multiplexed) channel with ASK/PSK, which is also way more efficient than using  
a bunch of idle frequencies and jumping between them.  

 3. [intersting to check Fourier](http://www.falstad.com/fourier/Fourier)  
 4. The joys of Cables  
- What’s the benefit of the thicker coax, what are the main downsides?  
• Greater shielding/noise protection; greater diameter=less resistance=longer  
runs; but lots of materials (=expensive) and very stiff (=hard to deploy)  
 
-  
 
 
 
 
 
 
