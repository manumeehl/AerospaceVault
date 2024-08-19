- Method of increasing information throughput density in digital circuits

##### PSK constellation diagrams
Circle with
- Amplitude: Distance to center
- Phase Shift: Position of circle
- Points for each phase position
- Lines to indicate the phase shifts

##### Binary Phase Shift Keying (BPSK)
- Both Amplitude and Frequency are kept constant
- Round circle in diagram
- The Phase shifts by 180°
- Sample rate is same as bitrate

##### Quadrature Phase Shift Keying
- Even higher throughput with the use of 4 phase states
- Seperated by 90°
- Used widely in mobile networks, WIFI and sat comms.

##### Higher order PSK
- Even more throughput
- Error rate becomes larger with increasing number of states
- If higher data rates are needed, amplitude and frequency modulation comes into play

##### Avoiding the origin
- Transition through the origin can be problematic

They should be avoided during state transitions as:
- Carrier amplitude goes (close) to zero
- High peak to average power ratio
- Complicates design of transmitters and amplifiers
- Can create synchronization issues

Avoiding the origin is usually achieved by transitioning not more than 90° and doing multiple partial transitions during one sample cycle  