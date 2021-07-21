# audio-text



from gtts import gTTs
from playsound import playsound
audio="speech.mp3"
language='en'
sp=gTTs(text="welcome to my github account.thanks for exploring ",lang=language,slow=False)
sp.save(audio)
playsound(audio)
print("Audio was playing")
