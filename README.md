This branch contains sanitized reproduction evidence for BerriAI/litellm PR #48775

The screenshots use actual Azure calls with synthetic speech and a browser WebRTC client

Before was captured at 1176e608b199c4a6572c22490839147a9f134ece. It shows a completed audible response with 159 tokens and six seconds of nested transcription, with zero current-session accounting records

After was captured at 494e59d4005e93f74944f757f470f8b60e25e86e. It shows a completed audible response with 194 tokens and five seconds of nested transcription, with two matching accounting records

The archive contains the portable harness, configuration and synthetic audio. Configure server-side Azure credentials and follow its README to reproduce

These files contain no provider credentials or raw service logs
