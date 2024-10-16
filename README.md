# ostris/OpenFLUX.1 Cog Model

This is an implementation of [ostris/OpenFLUX.1](https://huggingface.co/ostris/OpenFLUX.1) as a [Cog](https://github.com/replicate/cog) model.

## Development

Follow the [model pushing guide](https://replicate.com/docs/guides/push-a-model) to push your own model to [Replicate](https://replicate.com).


## How to use

Make sure you have [cog](https://github.com/replicate/cog) installed.

To run a prediction:

    cog predict -i prompt="a panda" -i output_format="png"

![Output](output.0.png)