# Adjustable Buck-Boost Converter — design notes

Power electronics, from the feedback network to the physical layout.

## Designing the power stage

I independently designed, manufactured, and assembled a four-layer adjustable buck-boost converter using the TI TPS63000. The design includes feedback, enable, input and output filtering, and voltage selection.

## Layout is part of the circuit

I used ground and power planes, kept high-current paths short, and considered thermal behavior throughout the layout. I also imported and checked LCSC and EasyEDA library assets, ran design-rule checks, and added test points.

## Understanding the behavior

I built a simplified Simulink model to explore transient response and control concepts alongside the physical converter design.

## Design focus

- TI TPS63000 converter
- Adjustable voltage selection
- Ground and power planes
- Test points for board bring-up

[Back to the repository overview](../README.md)
