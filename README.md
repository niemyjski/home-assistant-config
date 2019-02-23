# home-assistant


### Required Custom Updater Resources

To install one of these custom components or Python scripts for the first time, use the [`custom_updater.install`](https://github.com/custom-components/custom_updater/wiki/Services#install-element-cardcomponentpython_script) service with appropriate service data:

#### Illuminance
```
{
  "element": "sensor.illuminance"
}
```

#### Required Lovelace components
1. monster-card
2. surveillance-card
3. mini-graph-card