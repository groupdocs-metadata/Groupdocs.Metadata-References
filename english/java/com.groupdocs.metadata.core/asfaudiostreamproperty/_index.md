---
title: AsfAudioStreamProperty
second_title: GroupDocs.Signature for Java API Reference
description: Represents Audio stream property metadata in the ASF media container.
type: docs
weight: 11
url: /java/com.groupdocs.metadata.core/asfaudiostreamproperty/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage), [com.groupdocs.metadata.core.AsfBaseStreamProperty](../../com.groupdocs.metadata.core/asfbasestreamproperty)
```
public class AsfAudioStreamProperty extends AsfBaseStreamProperty
```

Represents Audio stream property metadata in the ASF media container.

**Learn more**

 *  [Working with Metadata in ASF Files][]


[Working with Metadata in ASF Files]: https://docs.groupdocs.com/display/metadatajava/Working+with+Metadata+in+ASF+Files
## Methods

| Method | Description |
| --- | --- |
| [getFormatTag()](#getFormatTag--) | Gets the unique ID of the codec used to encode the audio data. |
| [getChannels()](#getChannels--) | Gets the number of audio channels. |
| [getSamplesPerSecond()](#getSamplesPerSecond--) | Gets a value in Hertz (cycles per second) that represents the sampling rate of the audio stream. |
| [getBitsPerSample()](#getBitsPerSample--) | Gets the number of bits per sample of monaural data. |
### getFormatTag() {#getFormatTag--}
```
public final int getFormatTag()
```


Gets the unique ID of the codec used to encode the audio data.

**Returns:**
int - The unique ID of the codec used to encode the audio data.
### getChannels() {#getChannels--}
```
public final int getChannels()
```


Gets the number of audio channels.

**Returns:**
int - The number of audio channels.
### getSamplesPerSecond() {#getSamplesPerSecond--}
```
public final long getSamplesPerSecond()
```


Gets a value in Hertz (cycles per second) that represents the sampling rate of the audio stream.

**Returns:**
long - The a value in Hertz (cycles per second) that represents the sampling rate of the audio stream.
### getBitsPerSample() {#getBitsPerSample--}
```
public final int getBitsPerSample()
```


Gets the number of bits per sample of monaural data.

**Returns:**
int - The number of bits per sample of monaural data.
