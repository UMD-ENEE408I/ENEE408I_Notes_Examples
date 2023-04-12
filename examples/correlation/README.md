# Correlation with normalization by the overlapping region of the signals

When correlating two signals without complete overlap, it is important to normalize the correlation by the overlapping portion of the signals. Else the estimated time shift between the signals will be incorrect. Thus it is not enough to normalize the two signals being correlated beforehand.

This script shows what happens when the normalization by the overlapping region is not performed. The first time shift estimated is off by 9 samples and the mismatch is clearly visible in the time shifted plots of the two signals. When the normalization is calculated per shift, the estimated timeshift is correct.

This image shows the expected out:
