# E-ink displays power by ESPhome and Home Assistant



This is my take on the [F1pitboard](https://github.com/Nicxe/esphome).

I have adapted further to include F1 Fonts, and an additional Race Control page which will list various Race Control messages.
The Race Control page will only show when a session is active, an additional input sensor for spoilers is set to `Allowed`

This is my first attempt at anything with 

## F1 Pit board
This dashboard fetches information about the upcoming F1 race using the [F1 Sensor](https://github.com/Nicxe/f1_sensor) integration.

<img width="500" alt="F1_pitwall" src="https://github.com/geozza123/f1pitboard/blob/bcad790f278f21b4681e462f9bb24bdfc4e14149/sample_images/f1pitboard_countdown.jpg" />
<img width="500" alt="F1_pitwall" src="https://github.com/geozza123/f1pitboard/blob/bcad790f278f21b4681e462f9bb24bdfc4e14149/sample_images/f1pitboard_race_control.jpg" />




## Hardware
- [Waveshare 7.5inch E-Ink](https://www.waveshare.com/product/displays/e-paper/7.5inch-e-paper-g.htm) 
- [Waveshare Universal e-Paper Driver Board with ESP32](https://www.waveshare.com/e-paper-esp32-driver-board.htm)
- [IKEA Ribba 13x18cm](https://www.ikea.com/se/sv/p/ribba-ram-svart-50378448/)



## Software
- ESPHome
- Home Assistant






