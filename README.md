<ins>**VPD and Temperature-Based Controller for Humidifier, Cooler, Heater, and Dehumidifier**</ins>

Overview
This Home Assistant Blueprint controls a humidifier, cooler, heater, and dehumidifier as simple On/Off switches, independently based on:

VPD (Vapor Pressure Deficit) value (in kPa)

Temperature (in °C)

Humidity (in %)




<ins>_**Features:**_</ins>

✅ Humidifier Control

Turns ON when VPD exceeds the threshold.

Turns OFF when VPD drops below the threshold.

✅ Cooler Control

Turns ON when VPD exceeds the threshold.

Turns ON when temperature exceeds the threshold.

Turns OFF when temperature drops below the threshold, unless activated by VPD.

✅ Heater Control

Turns ON when temperature drops below the threshold.

Turns OFF when temperature rises above the threshold.

✅ Dehumidifier Control

Turns ON when humidity exceeds the threshold.

Turns OFF when humidity drops below the threshold.

✅ Failsafe Dummy Switch

If a device is not available, a Dummy Switch (switch.dummy_switch) is used as a placeholder to prevent errors.

✅ Automatic Updates

The automation triggers every 10 seconds to ensure real-time adjustments.

<a href="https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fcommunity.home-assistant.io%2Ft%2Fvpd-and-temperature-based-controller-for-home-assistant%2F899334" target="_blank" rel="noreferrer noopener"><img src="https://my.home-assistant.io/badges/blueprint_import.svg" alt="Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled." /></a>
