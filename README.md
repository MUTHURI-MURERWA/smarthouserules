# smarthouserules

Fact Format
% sensors and states
motion(Room).
no_motion(Room, Minutes).
light_level(Room, Lux).
lights_on(Room).
lights_brightness(Room, Level).

time(Hour, Minute).
weekday.
between_sunset_sunrise.

% devices and environment
tv_on(Room).
security_alarm.
indoor_temp(Value).
outdoor_temp(Value).
windows_closed.
windows_open(Zone).

% people and modes
someone_home.
all_away.
system_mode(home).
system_mode(away).
