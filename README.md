# mobile_mppt

Silicon polycrystalline MPP data set

This data set was generated synthetically in order to train a neural network. The neural network must estimate the voltage at the maximum power point (MPP) given datasheet information (short-circuit current, open circuit voltaje, reference maximum power point, voltaje at MPP and current at MPP) altogether with the following inputs (provided by sensors):
1. Solar irradiance and ambient temperature.
2. Ambiente temperature, current and voltage.
3. Current and voltage.

Two assumptions are taken into account in this data set: the shunt resistance is ideal and the diode ideality constant is equal to 1.3
