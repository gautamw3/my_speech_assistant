# my_speech_assistant
Simple speech assistant Python application





This application listeans to the user's command and respond to them programmatically:

For example, try saying hi, hey or hello, ask the time by saying - tell me the time or what time it is.

It's developed on top of a Ubuntu machine and so in order to work it properly, first install these core system dependencies:

	sudo apt-get install portaudio19-dev
	sudo apt install libcairo2-dev pkg-config python3-dev
	sudo apt-get install gobject-introspection libgirepository1.0-dev

Later on, install all the Python dependencies by running the command:

	pip install -r requirements.txt

Run the program by executing the command:

	python assistant.py

That's it.
