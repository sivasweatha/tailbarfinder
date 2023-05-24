# Tailbar Finder

Tailbar Finder uses Keras to identify tailbars ([bottoming and topping](https://static.incrediblecharts.com/images/png_images/candle_shadow_tail.png) tails). This is to be integrated with a charting system that plots the candles to use it in real-time.

This uses a pre-trained Keras image classification model to train the tailbars with.

## Usage

1. The `data` folder contains some tailbar images. The dataset needs to be larger for this to be used.
2. This does not contain the charting system. So it is not trading ready yet.
