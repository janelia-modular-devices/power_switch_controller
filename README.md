power_switch_controller
=======================

Authors:

    Peter Polidoro <polidorop@janelia.hhmi.org>

License:

    BSD

##More Detailed Help on Installation and Usage

[modular-devices](https://github.com/janelia-modular-devices/modular-devices)

##Device Information

```json
{
  "method":"?",
  "device_info":{
    "name":"power_switch_controller",
    "model_number":1110,
    "serial_number":0,
    "firmware_number":1
  },
  "methods":[
    "getMemoryFree",
    "resetDefaults",
    "setSerialNumber",
    "executeStandaloneCallback",
    "getLedsPowered",
    "setChannelOn",
    "setChannelOff",
    "setChannelsOn",
    "setChannelsOff",
    "toggleChannel",
    "toggleChannels",
    "toggleAllChannels",
    "setAllChannelsOn",
    "setAllChannelsOff",
    "setChannelOnAllOthersOff",
    "setChannelOffAllOthersOn",
    "setChannelsOnAllOthersOff",
    "setChannelsOffAllOthersOn",
    "getChannelsOn",
    "getChannelsOff",
    "getChannelCount",
    "saveState",
    "recallState",
    "getSavedStates",
    "addPulseCentered",
    "addPwmPeriodOnDuration",
    "addPwmFrequencyDutyCycle",
    "addSpikeAndHold",
    "stopAllPulses",
    "startPwmPeriodOnDuration",
    "startPwmFrequencyDutyCycle",
    "startSpikeAndHold",
    "stopPulseWave"
  ],
  "status":success
}
```

##Verbose Device Information

```json
{
  "method":"??",
  "device_info":{
    "name":"power_switch_controller",
    "model_number":1110,
    "serial_number":0,
    "firmware_number":1
  },
  "methods":[
    {
      "getMemoryFree":{
        "parameters":[]
      }
    },
    {
      "resetDefaults":{
        "parameters":[]
      }
    },
    {
      "setSerialNumber":{
        "parameters":[
          "serial_number"
        ]
      }
    },
    {
      "executeStandaloneCallback":{
        "parameters":[]
      }
    },
    {
      "getLedsPowered":{
        "parameters":[]
      }
    },
    {
      "setChannelOn":{
        "parameters":[
          "channel"
        ]
      }
    },
    {
      "setChannelOff":{
        "parameters":[
          "channel"
        ]
      }
    },
    {
      "setChannelsOn":{
        "parameters":[
          "channels"
        ]
      }
    },
    {
      "setChannelsOff":{
        "parameters":[
          "channels"
        ]
      }
    },
    {
      "toggleChannel":{
        "parameters":[
          "channel"
        ]
      }
    },
    {
      "toggleChannels":{
        "parameters":[
          "channels"
        ]
      }
    },
    {
      "toggleAllChannels":{
        "parameters":[]
      }
    },
    {
      "setAllChannelsOn":{
        "parameters":[]
      }
    },
    {
      "setAllChannelsOff":{
        "parameters":[]
      }
    },
    {
      "setChannelOnAllOthersOff":{
        "parameters":[
          "channel"
        ]
      }
    },
    {
      "setChannelOffAllOthersOn":{
        "parameters":[
          "channel"
        ]
      }
    },
    {
      "setChannelsOnAllOthersOff":{
        "parameters":[
          "channels"
        ]
      }
    },
    {
      "setChannelsOffAllOthersOn":{
        "parameters":[
          "channels"
        ]
      }
    },
    {
      "getChannelsOn":{
        "parameters":[]
      }
    },
    {
      "getChannelsOff":{
        "parameters":[]
      }
    },
    {
      "getChannelCount":{
        "parameters":[]
      }
    },
    {
      "saveState":{
        "parameters":[
          "state"
        ]
      }
    },
    {
      "recallState":{
        "parameters":[
          "state"
        ]
      }
    },
    {
      "getSavedStates":{
        "parameters":[]
      }
    },
    {
      "addPulseCentered":{
        "parameters":[
          "channels",
          "delay",
          "on_duration"
        ]
      }
    },
    {
      "addPwmPeriodOnDuration":{
        "parameters":[
          "channels",
          "delay",
          "period",
          "on_duration",
          "count"
        ]
      }
    },
    {
      "addPwmFrequencyDutyCycle":{
        "parameters":[
          "channels",
          "delay",
          "frequency",
          "duty_cycle",
          "pwm_duration"
        ]
      }
    },
    {
      "addSpikeAndHold":{
        "parameters":[
          "channels",
          "delay",
          "spike_duty_cycle",
          "spike_duration",
          "hold_duty_cycle",
          "hold_duration"
        ]
      }
    },
    {
      "stopAllPulses":{
        "parameters":[]
      }
    },
    {
      "startPwmPeriodOnDuration":{
        "parameters":[
          "channels",
          "delay",
          "period",
          "on_duration"
        ]
      }
    },
    {
      "startPwmFrequencyDutyCycle":{
        "parameters":[
          "channels",
          "delay",
          "frequency",
          "duty_cycle"
        ]
      }
    },
    {
      "startSpikeAndHold":{
        "parameters":[
          "channels",
          "delay",
          "spike_duty_cycle",
          "spike_duration",
          "hold_duty_cycle"
        ]
      }
    },
    {
      "stopPulseWave":{
        "parameters":[
          "pulse_wave_index"
        ]
      }
    }
  ],
  "status":success
}
```
