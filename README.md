YY180726.2: 80-Al-KIDs Nb-feedline device
==========================================

* 300 nm Nb feedline
*  30 nm Al KIDs

# Cooldowns:
1. Wire bonds @ room temp
   - center-ground: 864/936 ohm
   - center-center: 1871 ohm
2. Wire Bonds @ 4K
   - center-ground: 0.9 ohm (measured @ 7K)
   - center-center: 1.8 ohm (measured @ 7K)
3. 180820YY180726p1.h5
   - Data taken in 4K dewar, around 7K cold plate. Using B140's HP 8720D VNA
   ![Alt text](s21.png "Title")
4. Wire Bonds @ 4K
   - center-ground: 0.9 ohm (measured @ 7K)
   - center-center: 1.5 ohm (measured @ 7K)
5. Wire bonds @ room temp
   - center-ground: 877/OL ohm
   - center-center: OL ohm
   - maybe the wirebonds broke during warmup
6. Re-wire-bonded on 180822
7. Wire bonds @ room temp
   - center-ground: 897/912 ohm
   - center-center: 1836 ohm
8. swp_243_-25dB_180828_DM_device-3-3p7GHz.mat
   - Data taken in yellow dewar, around 245 mK. Using B140's HP 8720D VNA and the matlab data taking program
9. 180828YY180726p2.h5
   - "swp_243_-25dB_180828_DM_device-3-3p7GHz.mat", but converted to an h5 file for the python programs
10. Fridge Run # 39
    - http://www.submm.caltech.edu/wiki/kids//Oxford_20Kelvinox_2025/attachments/180924Pictures.zip
    - center-ground: 892/984 ohm
    - center-center: 1773 ohm
    - http://www.submm.caltech.edu/kids/Run_2339_20_28180926_29
11. Fridge Run # 41
    - http://www.submm.caltech.edu/kids/Run_2341_20_28181017_29
    - 181019YY180726p2.h5
      - On DR channel 1
      - 40 dB of attenuators before device
      - 1 dB of attenuator between device and HEMT 121 D
      - HEMT 121 D bias:
        - Id = 19.53 mA
        - Vd = 2.915 V
        - Vg = 1.734 V
      - MC temp is pretty stable
        - 62.53-62.66 mK on the Lake Shore
        - 67.6-67.9 mK on the IGH
      - fwinsize = 0.005 GHz
      - power = -15 dBm
      - fwinstart = 3 GHz
      - fwinend = 3.8 GHz
      - channels = S21, S22
      ![Alt text](181019YY180726p2s21.png "Title")
