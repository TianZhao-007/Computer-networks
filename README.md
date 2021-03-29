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

Mancherster:用电压变化来分辨0、1；高->低 是0； 低->高 是1；
- 优点： 提供一种同步机制，保证接收端和发射端信号同步。  
- 缺点： 编码频率高，带宽大一倍（和NRZ相比）  

### baseband/passband/broadband
[click here to lean](https://youtu.be/Ph9N0XGmi-E)  

### Nyquist limit and shannon capacity limit  
Nyquist limit = 2 * frequency * log2 (V)  bit/s  
Reliable capacity = Baudrate * log2 (1+signal/noise)  



