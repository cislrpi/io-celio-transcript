@cisl/io-celio-transcript
===================

Plugin for @cisl/io for interfacing with the transcript-worker

Usage
-----

```javascript
const io = require('@cisl/io');
const { registerTranscript } = require('@cisl/io-celio-transcript');
io.registerPlugins(registerTranscript);

io.speaker.speak('test');
```

```typescript
import io from '@cisl/io';
import { registerTranscript } from '@cisl/io-celio-transcript';
io.registerPlugins(registerTranscript);

io.speaker.speak("test");
```
