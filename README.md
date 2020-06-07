# Trained Model Examples
In this repository, we serve several example trained models to make predictions over HTTP.

## Architecture
In each example directory, custom machine learning system code is defined in `system.py`, where we only load a pre-trained model (i.e. no training occurs within this application). In particular, we implement the `output()` interface on Catacomb's `System` class, which is called in our generated `server.py` file.

## Usage
Each example directory has a `README.md` file with instructions on running the example.

## License
MIT