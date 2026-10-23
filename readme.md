# PAPR Reduction and Performance Analysis of P-SLM Algorithm Based on Slantlet in Alamouti MIMO-OFDM System [with MATLAB]

Introduction: Multi-Input Multi-Output Orthogonal Frequency Division Multiplexing (MIMO-OFDM) systems have attracted significant attention due to their potential for achieving high data rates and providing reliable diversity and spatial multiplexing performance. However, the drawback of OFDM-based transmission systems is the peak-to-average power ratio (PAPR) of the transmitted signals. If the linear range of the high power amplifier (HPA) at the OFDM transmitter is insufficient, this can lead to inter-subcarrier band-to-band distortion and undesired spectrum regrowth.
To reduce the PAPR of OFDM, numerous techniques have been developed, such as clipping and filtering [6], partial transmission sequence (PTS) [12], selective mapping (SLM) [3], compression [10], and adaptive full-pass filters [4]. Many techniques have also been proposed for reducing PAPR in MIMO-OFDM [9]. SLM technology is considered the best among existing techniques because it reduces the PAPR without causing any signal distortion. In traditional SLM techniques, the phase rotation sequence is used to rotate the phase of the OFDM signal, and this sequence is sent along with the transmitted signal as side information (SI). This additional bit increases the data rate. Moreover, SI interferes with frequency-selective fading channels, leading to significant degradation in the system's bit error rate (BER). The available blind SLM (B-SLM) schemes for Alamanti MIMO-OFDM systems perform PAPR reduction without using SI [7]. The phase rotation sequence in B-SLM only uses 1, -1, which is not suitable for many cases.
This paper proposes a phase-shifted SLM (P-SLM) scheme, which is combined with the Slantlet transform to reduce the Peak Amplitude Rejection Ratio (PAPR) in an American MIMO-OFDM system without Side Information (SI). In the P-SLM scheme, phase shifts are used to distinguish signals at different transmit antennas. These phase shifts correspond to phase rotation sequences, thus eliminating the need for SI transmission. At the receiver end, a minimum Euclidean Distance (MED) decoder is proposed for decoding signals with the minimum Euclidean distance. Since SI can be estimated from phase shifts, no additional bits are retained. Additionally, the use of the Slantlet transform provides orthogonality without using cyclic prefixes, leading to better PAPR and BER reduction performance.
The article includes illustrations.
Conclusion: This paper introduces a Slantlet-based P-SLM scheme that utilizes the corresponding phase shift values from the phase rotation sequence and an orthogonal filter to reduce the PAPR in an American MIMO-OFDM system without side information and cyclic prefixes. As it eliminates the need for SI transmission compared to the C-SLM scheme, it offers increased data rate. Simulation results show that, compared to the FFT-based P-SLM scheme and B-SLM scheme, the method based on Slantlet in the P-SLM scheme reduces the PAPR value at the transmit antenna by approximately 14% and 20%, respectively.

## Images

![PAPR suppression and performance analysis of P-SLM algorithm based on Slantlet in Alamouti MIMO-OFDM system [with MATLAB]](01.jpg)
![PAPR suppression and performance analysis of P-SLM algorithm based on Slantlet in Alamouti MIMO-OFDM system [with MATLAB]](02.jpg)
![PAPR suppression and performance analysis of P-SLM algorithm based on Slantlet in Alamouti MIMO-OFDM system [with MATLAB]](03.jpg)
![PAPR suppression and performance analysis of P-SLM algorithm based on Slantlet in Alamouti MIMO-OFDM system [with MATLAB]](04.jpg)
![PAPR suppression and performance analysis of P-SLM algorithm based on Slantlet in Alamouti MIMO-OFDM system [with MATLAB]](05.jpg)
![PAPR suppression and performance analysis of P-SLM algorithm based on Slantlet in Alamouti MIMO-OFDM system [with MATLAB]](06.jpg)
![PAPR suppression and performance analysis of P-SLM algorithm based on Slantlet in Alamouti MIMO-OFDM system [with MATLAB]](07.jpg)
![PAPR suppression and performance analysis of P-SLM algorithm based on Slantlet in Alamouti MIMO-OFDM system [with MATLAB]](08.jpg)

<!-- PAYMENT_BLOCK -->

## Get this dataset

- Payment link (Stripe): [Buy now](https://buy.stripe.com/3cs8yP7sY87d0vu9AB)
- Payment QR code: ![Payment QR code](pay.png)

<!-- /PAYMENT_BLOCK -->
