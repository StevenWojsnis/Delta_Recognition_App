# Delta_Recognition_App
Project that uses CMU PocketSphinx for speech recognition. Note: This application is the result of a group effort.

This application enalbes the use of Speech-to-text Speech recognition, through the use of the CMU Sphinx, PocketSphinx project.

To perform the speech-to-text operation, a user can either record a new voice file on the spot, or upload a pre-existing .raw or
.wav file. Note that, due to project specifications (given by professor), when a user opts to record something on the spot for 
speech recognition, the input stream from the microphone is not fed directly into the speech recognition module, rather, the input
stream is used to create a new file, which is then, in turn, fed into the speech recognition module. Thus, the two options (newly recorded
or pre-existing file) essentially perform the same function - taking a file input stream of a voice file and feeding it into the speech
recognition module.
