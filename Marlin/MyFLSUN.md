Send: M503
Recv: echo:  G21    ; Units in mm (mm)
Recv: echo:  M149 C ; Units in Celsius
Recv: 
Recv: echo:; Filament settings: Disabled
Recv: echo:  M200 S0 D1.7500
Recv: echo:; Steps per unit:
Recv: echo: M92 X100.0000 Y100.0000 Z100.0000 E412.9900
Recv: echo:; Maximum feedrates (units/s):
Recv: echo:  M203 X250.0000 Y250.0000 Z250.0000 E200.0000
Recv: echo:; Maximum Acceleration (units/s2):
Recv: echo:  M201 X1000.0000 Y1000.0000 Z1000.0000 E1000.0000
Recv: echo:; Acceleration (units/s2): P<print_accel> R<retract_accel> T<travel_accel>
Recv: echo:  M204 P1000.0000 R250.0000 T1000.0000
Recv: echo:; Advanced: B<min_segment_time_us> S<min_feedrate> T<min_travel_feedrate> X<max_x_jerk> Y<max_y_jerk> Z<max_z_jerk> E<max_e_jerk>
Recv: echo:  M205 B20000.0000 S0.0000 T0.0000 X10.0000 Y10.0000 Z10.0000 E5.0000
Recv: echo:; Unified Bed Leveling:
Recv: echo:  M420 S1 Z10.0000
Recv: 
Recv: Unified Bed Leveling System v1.01 active
Recv: 
Recv: echo:; Active Mesh Slot: 1
Recv: echo:; EEPROM can hold 2 meshes.
Recv: 
Recv: echo:; Endstop adjustment:
Recv: echo:  M666 X0.0000 Y-2.7082 Z-3.1732
Recv: echo:; Delta settings: L<diagonal rod> R<radius> H<height> S<segments per sec> XYZ<tower angle trim> ABC<rod trim>
Recv: echo:  M665 L280.0000 R141.9439 H354.3339 S200.0000 X0.0353 Y0.2565 Z-0.2919 A0.0000 B0.0000 C0.0000
Recv: echo:; Material heatup parameters:
Recv: echo:  M145 S0 H210 B60 F200
Recv: echo:  M145 S1 H230 B50 F0
Recv: echo:  M145 S2 H240 B60 F0
Recv: echo:  M145 S3 H0 B60 F0
Recv: echo:; PID settings:
Recv: echo:  M301 P16.5118 I0.8956 D76.1048
Recv: echo:  M304 P82.7215 I15.1755 D300.6100
Recv: echo:; Power-Loss Recovery:
Recv: echo:  M413 S1
Recv: echo:; Z-Probe Offset (mm):
Recv: echo:  M851 X0.0000 Y0.0000 Z-19.3200
Recv: echo:; Linear Advance:
Recv: echo:  M900 K0.0000
Recv: echo:; Stepper motor currents:
Recv: echo:  M907 X800 Z800 E800
Recv: echo:; Filament load/unload lengths:
Recv: echo:  M603 L750.0000 U850.0000
Recv: echo:; Filament runout sensor:
Recv: echo:  M412 S1 D25.0000
Recv: ok
