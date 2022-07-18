# RTC-
To make Real Time  Clock using verilog 
A real-time clock (RTC) is an electronic device (most often in the form of an integrated circuit) that measures the passage of time.

Although the term often refers to the devices in personal computers, servers and embedded systems, RTCs are present in almost any electronic device which needs to keep accurate time of day. RTCs are designed for ultra-low power consumption as they usually continue running when the main system is powered down.
RTCs are a very common element. They are present in everything from the instrument clusters and infotainment systems in automotive applications to house metering. RTCs frequently integrate into other devices—for example, the broadband communications ICs used in car radios.

They usually interface to a microprocessor circuit by an SPI or I2C serial bus, and may contain a number of other functions like backup memory, a watchdog timer for supervising the microprocessor and countdown timers to generate real time event. Some RTCs include second or minute interrupt outputs and are even clever enough to account for leap years .
An RTC maintains its clock by counting the cycles of an oscillator – usually an external 32.768kHz crystal oscillator circuit, an internal capacitor based oscillator, or even an embedded quartz crystal. Some can detect transitions and count the periodicity of an input that may be connected.

This can enable an RTC to sense the 50/60Hz ripple on a mains power supply, or detect and accumulate transitions coming from a GPS unit epoch tick. An RTC that does this operates like a phase locked loop (PLL), shifting its internal clock reference to ‘lock’ it onto the external signal. If the RTC loses its external reference, it can detect this event (as its PLL goes out of lock) and free run from its internal oscillator.

Some RTCs maintain the oscillator setting at the last known point before it went out of lock with the input. Time resolution is an important consideration – how accurately do you need to read the current time? This is specified by the RTC datasheet, but is ultimately limited by the oscillator frequency.

An RTC that is running from its own internal reference will integrate an error related to the absolute accuracy of the crystal reference, and is effected by a number of conditions including temperature.
RTCs need continuous power and must have extremely low power consumption. Most RTCs use the digital circuits supply when the device is on and active, but switch over to a continuously connected power source when the circuit is powered down. This power source could be a dedicated battery, a charged supercapacitor or a separate power supply from mains.

Many RTCs can detect this change-over and go into an ultra-low power state where they power down all circuitry except those essential for maintaining the clock in order to conserve battery life. RTCs can also include alarm functions – set times that when reached trigger the RTC to drive an output that wakes the processor up.
