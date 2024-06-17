# Frequently asked questions

## :material-file-code: About device specifications
??? question "What are the absolute maximum input frequencies?"
    Both channels can be used safely with frequencies up to 150 kHz, which is the maximum our flowmeters support. Theoretically each channel is capable of measuring frequencies up to 1 MHz.

??? question "What does "internal boost converter" mean?"
    The internal boost converter allows the user to generate a stable 24V output voltage for supplying the flowmeters by only using the USB connection (and no DC-Jack!). It is a ciruit that will transform the 5V bus voltage up to 24V but with a lower current capability. Therefore it is advisable to only connect low power flowmeters with a total current consumption $I<50 \textrm{ mA}$ to the Cal.flow if using the converter. Otherwise the internal circuit will overheat and will not be able to generate a steady power supply.

    The internal boost converter is practical on mobile setups/notebooks where no external power is available.

    For reference: A testbox TB2 pulse generator uses $30  \textrm{ mA}$, while a VSI+ preampilfier uses about $36 \textrm{ mA}$.

## :material-chat-question: General problems
??? question "Why does the measurement not start even though the flow is set correctly?"
    Try to set the ```minimum flow hysteresis``` higher or ```flow steady time``` lower so that the steadyness check can complete successfully. Watch the graph - is the master flowrate inside the hysteresis lines?

    Another reason could be that the calibration state machine is not running: The calibration process must **always** be started using the ```Start calibration procedure``` button on the ```calibration setup``` page.

??? question "The live graph shows zero even though flow is present and the M12 connector is plugged in"
    1. Check if the port config if set right for both flowmeters (1/2-channel).

    2. Check if the master linearization table in filled and valid.

    3. Check if a nominal K-Factor for the DUT is selected.

    4. If all else fails, try reconnecting the Cal.flow.