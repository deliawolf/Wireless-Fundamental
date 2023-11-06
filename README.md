# Wireless-Fundamental


# RF Principles

## RF Spectrum

Different waves have different sizes that are typically expressed in meters. Another unit of measurement, hertz, expresses how often a wave occurs per second. Waves are grouped by category, with each group matching a size variation. The highest waves are in the gamma-ray group.

The waves that a human body cannot perceive are used to send information. Depending on the type of information being sent, certain wave groups are more efficient than others in the air because they have different properties. For example, in wireless networks, because of the different needs and regulations that arose over time, creating subgroups became necessary.

Reference : https://en.wikipedia.org/wiki/Radio_spectrum

##  Frequency

A wave is always sent at the speed of light because it is an electromagnetic field. Therefore, the wave takes a shorter or longer time to travel one cycle, depending on its length.
Frequency determines how often a signal is seen.

For example, a signal wavelength that is 0.2 inch (5 mm) long takes less time to travel a cycle than one that is 1312 feet (400 m) long. The speed is the same in both cases, but because a longer signal takes more time to travel one cycle than a shorter signal, the longer signal goes through fewer cycles in 1 second than the shorter signal.

A direct relationship exists between the frequency of a signal (how often the signal is seen) and the wavelength of the signal (the distance that the signal travels in one cycle). The shorter the wavelength, the more often the signal repeats itself over a given time and, therefore, the higher the frequency.

## Wavelength

The size of the cycle pattern of an electromagnetic wave is called the wavelength.

The physical distance from one point of the cycle to the same point in the next cycle is called a wavelength, which is usually represented by the Greek symbol lambda. The wavelength is defined as the physical distance that the wave covers in one cycle.

## Amplitude

Amplitude can be defined as the strength of the signal. In a graphical representation, amplitude is seen as the distance between the highest and lowest crests of the cycle.

Amplitude is the strength of the signal.

Amplification is the increase in the amplitude of the wave. Amplification can be active or passive. In active amplification, the applied power is increased. Passive amplification is accomplished by focusing the energy in one direction by using an antenna. Amplitude can also be decreased. This decrease is called attenuation.

An easy way to represent this concept is to picture a 20-foot (600 cm) rope that is tied to a fence. If you shake the free end of the rope, you create a wave in the rope. To create a larger wave, you must shake the rope harder. Generating a large wave with a rope requires more energy than generating a small one.

## Free Path Loss

Free Path Loss is often referred to as Free Space Path Loss. A radio wave that an access point (AP) emits is radiated in the air. If the antenna is omnidirectional, the signal is emitted in all directions, such as when a stone is thrown into water, and waves radiate outward from the point at which the stone touches the water. If the AP uses a directional antenna, the beam is more focused in one direction.

An electromagnetic wave becomes weaker as it spreads away from the emitter.

The attenuation of the signal strength on its way between a sender and a receiver is called free path loss. The word “free” in the expression refers to the fact that the loss of energy is simply a result of distance, not of any obstacle. Including this word in the term is important because RF engineers also talk about path loss, which considers other sources of loss.

## RSSI and SNR

### RSSI

The value indicating how much power is received is called RSSI, a more common name for the signal value. RSSI is the signal strength that one device receives from another device. RSSI is usually expressed in decibels (dBs) referenced to 1 milliwatt (dBm).

### SNR

Another important metric is SNR. SNR is a ratio-based value that evaluates your signal, which is based on the noise that is seen. SNR is measured as a positive value between 0 and 120; the closer the value is to 120, the better

Signal-to-noise ratio (SNR) is the evaluation of signal strength after it has been affected by noise.

For example, if the RSSI is –55dBm and the noise value is –95dBm, the following is true:

  –55 – –95 = –55 + 95 = 40

  The result is a SNR of 40dB. The general principle is that any SNR above 20dB is good.


# Watts and Decibels

Decibels measure the amount of power relative to a reference:

  0 dB = same power

  3 dB = 2 times the power

  –3 dB = 1/2 the power

  10 dB = 10 times the power

  –10 dB = 1/10 the power

Decibels are used to compare powers in Wi-Fi networks.

Watt or milliwatt (mW) is an absolute power value that simply expresses power consumption. These measurements are also useful in comparing devices. For example, a typical AP can have a power of 100 mW. But this power varies depending on the context (indoor or outdoor) and the country because there are some regulations in this field.

Another value that is commonly used in Wi-Fi networks is the decibel (dB). This term is a familiar one regarding sound levels. A decibel is a logarithmic unit of measurement that expresses the amount of power relative to a reference.

Decibels are used extensively in Wi-Fi networks to compare powers. Two types of powers can be compared:

  1. the electric power of a transmitter

  2. the electromagnetic power of an antenna

Transmitters express power in milliwatts.

When converting between decibels and milliwatts, use the rules of “3 and 10”.

   +3 dBm = 2 mW (2 times the power)

  –3 dBm = 0.5 mW (1/2 the power)

   +10 dBm = 10 mW (10 times the power)

   –10 dBm = 0.1 mW (1/10 the power)

## Decibels to Milliwatts

Example 1: When converting 36 dBm to milliwatts:

  Express the dBm value as sums of 10 and 3, for example, 36 dBm = 10 + 10 + 10 + 3 + 3.

  Then begin at 1 mW and apply the rules of 10s and 3s, multiplying or dividing by 10 or 2 as appropriate, thus resulting in (1 mW x 10 x 10 x 10 x 2 x 2) = 4000 mW or 4 W.

Example 2: When converting 27 dBm to milliwatts:

  Express the dBm value as sums of 10 and 3; for example, 27 dBm = 10 + 10 + 10 – 3.

  Then begin at 1 mW and apply the rules of 10s and 3s, multiplying or dividing by 10 or 2 as appropriate, thus resulting in (1 mW x 10 x 10 x 10) /2 = 500 mW.


The direct formula for converting decibels to milliwatts is P(mW) = 1 mW · 10^(P(dBm) /10).

## Milliwatts to Decibels

Example 1: When converting 40 mW to dBm:

  Express the milliwatt value as factors of 2 and 10, for example, 40 mW = 10 x 2 x 2.

  Apply the rules of 10s and 3s, you substitute +10 for the 10s and +3 for the 2s resulting in + 10 + 3 + 3 = 16 dBm.

Example 2: When converting 50 mW to dBm:

  Express the milliwatt value as factors of 2 and 10—for example, 50 mW = (10 x 10) /2.

  Apply the rules of 10s and 3s, you substitute +10 for the 10s and –3 for the 2s resulting in + 10 + 10 – 3 = 17 dBm.

The direct formula for converting milliwatts to decibels is P(dBm) = 10 · log10(P(mW) / 1 mW).

## Antenna Power

An antenna does not send an electric current, but rather an antenna sends an electromagnetic field. Wi-Fi engineers need to compare the power of antennas without using the indirect value of the current that is sent, and they do so by measuring the power gain relative to a reference antenna.

Decibels measure the amount of power relative to an isotropic antenna:

  0 dB = same power

  3 dB = 2 times the power

   –3 dB = 1/2 the power

   10 dB = 10 times the power

   –10 dB = 1/10 the power

Decibels are used to compare antenna power.

This reference antenna, called an isotropic antenna, is a spherical antenna that is theoretically 1 dot large and radiates in all directions

Other scales can be used to compare antennas. Some Wi-Fi professionals prefer to use a dipole antenna as the reference. This comparison is expressed in dBd. When comparing antennas, be sure to use the same format (either dBd or dBi) for each antenna.

## Effective Isotropic Radiated Power

Comparing antennas gives a measure of their gain. The antenna is a passive device, so it does not add to the energy that it receives from the cable. The only thing that the antenna can do is to radiate this power in one or more directions.

Effective Isotropic Radiated Power (EIRP) measures how much energy is actually radiated from an antenna toward the main beam.

In mathematical terms, EIRP, expressed in dBm, is simply the amount of Tx power plus the gain (in dBi) of the antenna. However, the signal might go through a cable in which some power might be lost, so the cable loss must be deducted.

Therefore, EIRP can be expressed as: EIRP = Tx power (dBm) + antenna gain (dBi) – cable loss (dB).

EIRP is important from a resulting power and regulations standpoint. Most countries allow a maximum Tx power of the transmitter and a final maximum EIRP value, which is the resulting power when the antenna is added. The installer must pick the appropriate antenna and transmitter power settings that are based on regulations for the country of deployment.

For example, calculate the EIRP for a deployment with the following parameters:

  Tx power = 17 dBm

   Antenna gain = 28 dBi

   Cable loss = -3 dB

The EIRP = 17 + 28 -3 = 42 dBm. In this case, if the FCC EIRP limitation is 36 dBm, the installer would need to turn down the transmit power or choose a different antenna.
