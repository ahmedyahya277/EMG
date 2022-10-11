this is the circuit of the EMG (Electromyograph):
	diagnostic procedure to assess the health of muscles and the nerve cells that control them (motor neurons).
First:
	the instumentation sage in which we ampliy the signal as it's very small (from 0.1 to 2.5 mvolts).
Second:
	the high pass filter which pass the signals that thier frequences are more than 20 HZ (2nd order filter).
3rd :
	the low pass filter which pass the signals that thier frequences are less than 500 HZ (2nd order filter).

So, 	the pand pass is from 20 to 500 HZ which is the ranage of the EMG signals.

4th :
	the notch filter and it's verry narrow pand stop filter used to remove the 60 HZ of the electric signals that found in the environment.

5th :
	the rectification stage which surve to rectify the signal as the relaxation of the muscles happen negative voltages are created then rectified to the positive side.

6th :
	Amplification used to make the signal more readable and applicable to be used in microcontroller as Arduino.

7th :	
	Smothing stage used to smoth the signal and not to drop all the voltage when the arm relaxed but read the peaks of the pulses.
 
  By the way the project is done using Proteus Simulation and done practically too under supervision ENG.Mazen
