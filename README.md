# TTT Blink
Traitor weapon for Trouble in Terrorist Town. Inspired by Dishonored's "blink" ability.

## Installation
Clone this repository into `.../garrysmod/addons`.

## Usage
### CVars
This special weapon supports the following configurable variables.

| Variable | Description | Type | Default |
| --- | --- | --- | --- |
| `ttt_minty_blink_charge_count` | The maximum amount of charges.<br>Set to `0` to use 'semi-unlimited' mode. | `int` | `0` |
| `ttt_minty_blink_charge_cost` | The cost per blink in arbitrary units.<sup>1</sup> | `int` | `50` |
| `ttt_minty_blink_charge_max` | The initial maximum charge in arbitrary units.<sup>1</sup> | `int` | `100` |
| `ttt_minty_blink_charge_exhaust_scalar` | The amount of current maximum charge to deduct.<sup>1</sup><br>Relative to `ttt_minty_blink_charge_cost`.<br>Only deducts if the current charge is below the current maximum. | `float` | `0.75` |
| `ttt_minty_blink_charge_recharge_rate` | The recharge rate in units/sec.<sup>1</sup>  | `int` | `15` |
| `ttt_minty_blink_post_process` | Whether to enable post-processing (`0/1`).  | `int` | `0` |
| `ttt_minty_blink_range` | The maximum blink distance in Source units.  | `int` | `3072` |

<sup>1</sup>*Unused in 'limited' mode (`ttt_minty_blink_charge_count > 0`).*

## License
See `LICENSE.md`.
