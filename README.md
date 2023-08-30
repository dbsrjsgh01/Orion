# Orion reference implementation
------------
## 참조
Paper: https://eprint.iacr.org/2022/1010
------------
``` bash
$ cmake .
$ make
```
+ ```src/VPD```
 * ```fri.cpp```, ```fft_circuit_GKR.cpp```
   FRI에서 Reed-Solomon code encoding 이용하여 commitment 생성하는 과정 참조한 듯
 * ```linearPC.cpp```
   중요하게 봐야할 내용. Main protocol로 commit, prove, verify 과정 있음
 * ```vpd_verifier.cpp```
   Verifying 과정 확인
 * 추가로 encoding circuit을 어떻게 작성했는지 확인할 필요 있음
