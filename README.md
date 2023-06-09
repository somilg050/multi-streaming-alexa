# Build A Multi-Stream Audio Alexa Skill with the Audio Player Interface (Node.js)
## Summary
This Alexa sample skill is a template for using the AudioPlayer interface for Alexa-hosted skills. The skill consists of an interface model and logic of the skill. This sample contains a sample skill that plays multiple audio, along with handlers for all of the AudioPlayer events, touch controls and error handling. Current playback information is tracked in the DynamoDB table provisioned as part of the Alexa-hosted skill using the DynamoDB persistence adapter.

## Getting started
1. Create a new skill on the Developer Console using the **Custom** model and select **Alexa-hosted (Node.js)** as the backend.
2. When prompted to select a template, click the **Import Skill** button and paste this repository's web URL.
4. Edit the **constants.js** to add your audio files by following the sample format in the same file.
5. Test the skill - if it doesn't play the audio, there there could be issues with the file format of your audio. In that case, make sure your audio follows the [audio file requirements](https://developer.amazon.com/docs/alexa/custom-skills/audioplayer-interface-reference.html#audio-stream-requirements).

## Additional Resources
### Documentation
* [AudioPlayer Interface](https://developer.amazon.com/docs/alexa/custom-skills/audioplayer-interface-reference.html)
* [Audio stream/file requirements](https://developer.amazon.com/docs/alexa/custom-skills/audioplayer-interface-reference.html#audio-stream-requirements)
* [Import a skill from a Git repository](https://developer.amazon.com/docs/alexa/hosted-skills/alexa-hosted-skills-git-import.html)

### Other Samples
* [AudioPlayer sample for a single audio file](https://github.com/alexa/skill-sample-nodejs-audio-player/)

### Security 
See [CONTRIBUTING](https://github.com/alexa-samples/skill-sample-nodejs-multistream-audio-player/blob/main/CONTRIBUTING.md#security-issue-notifications) for more information.

### License 
This library is licensed under the Amazon Software License.
