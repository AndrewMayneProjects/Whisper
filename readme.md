<h2>Creating YouTube transcripts with OpenAI's Whisper model</h2>
 

###**Note: For faster performance set your runtime to "GPU"**
(Click on "Runtime" in the menu and click "Change runtime type".

<br> 
**Step 1.** Follow the instructions in each block and select the options you want\
**Step 2.** Grab the url of the video you want to transcribe\
**Step 3.** Click the run button on the left side of the box below\
**Step 4.** Refresh the folder on the left and download your transcript\
**Step 5.** Go to your YouTube account and upload the transcript to the video it came from and use "autosync."

That's it!

Have a question? Hit me up on Twitter: @AndrewMayne

<br>



---


**What is this?**
<br>
This is a Python notebook that creates a transcript from a YouTube url using OpenAI's Whisper transcription model that you can then upload to YouTube using the autosync feature to create captions.
<br>  
**Why use this?**
<br> 
The quality of the OpenAI Whisper model is amazing (I am slightly biased, but seriously, check it out.) You can also use it to transcribe in other languages.
<br> 
<br>
**What do the different model sizes do?**
<br>
Each model size has an improvement in quality – especially with different languages. I've found that for a YouTube video with clear speech, the base model works really well. If you see transcription errors, you can try a larger model.
<br>
<br> 
**Do I need timestamps?**
<br> 
Nope. YouTube's autosync function will match the text to the spoken words and syncs up really well. All you need is each spoken sentence in a .txt file.
<br> 
<br> 
**How do I do this?**
<br> 
Just follow each step. If you've never used Colab of a Python notebook, don't panic. It's super easy and runs in the cloud.
<br> 
<br> 
**Does this cost anything to use?**
<br>
Nope. You can use Colab for free and Whisper is an open source model. 
<br> 
 
[Tips for creating a YouTube transcript file](https://support.google.com/youtube/answer/2734799?hl=en)\
[Information on OpenAI's Whisper model](https://openai.com/blog/whisper/)\
[OpenAI's Whisper GitHub page](https://github.com/openai/whisper)
<br>


