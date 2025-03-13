# SafeRL
Explicit safe reinforcement learning


# Safety-Gymnasium Benchmark 
Baseline models were trained based on the implementation of safe reinforcement learning algorithms in the [Omnisafe](https://www.omnisafe.ai/en/latest/) frameowrk.

### 🏀 Safety Status Indicator  
The **ball** represents the system's safety status:  
- 🔴 **Red** → Unsafe  
- 🟢 **Green** → Safe  

## SafetyHopperVelocity-v1

### Demo Video
| DDPG | TD3 | TD3_LAG | TD3_PID | Ours |
|------|-----|---------|---------|------|
| <img src="gif/DDPG_SafetyHopperVelocity_v1.gif" width="150"/> | <img src="gif/TD3_SafetyHopperVelocity_v1.gif" width="150"/> | <img src="gif/TD3_LAG_SafetyHopperVelocity_v1.gif" width="150"/> | <img src="gif/TD3_PID_SafetyHopperVelocity_v1.gif" width="150"/> | <img src="gif/Ours_SafetyHopperVelocity_v1.gif" width="150"/> |
|------|-----|---------|---------|------|
|Reward|
| 1462.56 ± 591.14 | 3404.41 ± 82.57 | 928.79 ± 389.48 | 1225.97 ± 224.71 | 1216.583 ± 118.336 |
|Cost|
| 429.17 ± 220.05 | 973.80 ± 4.92 | 40.67 ±30.99 | 46.87 ±65.28 | 1.340 ± 3.803 |
