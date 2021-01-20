# Datastream: Min/Max values

**Min / Max** fields are used to specify the range of incoming values. This setting is applied everywhere, where this Datastream is used.

For example, if you use a Chart widget, it will use min/max values by default. Some visualization widgets allow overriding min/max values.

**IMPORTANT:** If the incoming value falls out of the specified min/max range, the value will be _cropped_.

Example: Datastream `Min-Max` fields are set to `0-100`

| Datastream | Min | Max |
| :--- | :--- | :--- |
| Humidity | `0` | `100` |

Here is how incoming values will be processed:

| Incoming value | Result |
| :--- | :--- |
| `50` | `50` |
| `314` | `100` |
| `-2` | `0` |

Min /Max setting is applied if the value matches the Data Type. Otherwise, the value will be ignored. Check Data Type Settings reference.

