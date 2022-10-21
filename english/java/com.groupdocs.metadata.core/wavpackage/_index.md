---
title: WavPackage
second_title: GroupDocs.Metadata for Java API Reference
description: Represents a native metadata package in a WAV audio file.
type: docs
weight: 237
url: /java/com.groupdocs.metadata.core/wavpackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage)
```
public final class WavPackage extends CustomPackage
```

Represents a native metadata package in a WAV audio file.

This code sample shows how to extract technical audio information from a WAV file.

> ```
> ```
> 
>  try (Metadata metadata = new Metadata(Constants.InputWav)) {
>      WavRootPackage root = metadata.getRootPackageGeneric();
>      if (root.getWavPackage() != null) {
>          System.out.println(root.getWavPackage().getAudioFormat());
>          System.out.println(root.getWavPackage().getBitsPerSample());
>          System.out.println(root.getWavPackage().getBlockAlign());
>          System.out.println(root.getWavPackage().getByteRate());
>          System.out.println(root.getWavPackage().getNumberOfChannels());
>          System.out.println(root.getWavPackage().getSampleRate());
>      }
>  }
>  
> ```
> ```
## Constructors

| Constructor | Description |
| --- | --- |
| [WavPackage()](#WavPackage--) | Initializes a new instance of the  WavPackage  class. |
## Methods

| Method | Description |
| --- | --- |
| [getAudioFormat()](#getAudioFormat--) | Gets the audio format. |
| [getNumberOfChannels()](#getNumberOfChannels--) | Gets the number of channels. |
| [getSampleRate()](#getSampleRate--) | Gets the sample rate. |
| [getByteRate()](#getByteRate--) | Gets the byte rate. |
| [getBlockAlign()](#getBlockAlign--) | Gets the block align. |
| [getBitsPerSample()](#getBitsPerSample--) | Gets the bits per sample value. |
### WavPackage() {#WavPackage--}
```
public WavPackage()
```


Initializes a new instance of the  WavPackage  class.

### getAudioFormat() {#getAudioFormat--}
```
public final int getAudioFormat()
```


Gets the audio format. PCM = 1 (i.e. Linear quantization). Values other than 1 indicate some form of compression.

**Returns:**
int - The audio format.
### getNumberOfChannels() {#getNumberOfChannels--}
```
public final int getNumberOfChannels()
```


Gets the number of channels.

**Returns:**
int - The number of channels.
### getSampleRate() {#getSampleRate--}
```
public final int getSampleRate()
```


Gets the sample rate.

**Returns:**
int - The sample rate.
### getByteRate() {#getByteRate--}
```
public final int getByteRate()
```


Gets the byte rate.

**Returns:**
int - The byte rate.
### getBlockAlign() {#getBlockAlign--}
```
public final int getBlockAlign()
```


Gets the block align.

**Returns:**
int - The block align.
### getBitsPerSample() {#getBitsPerSample--}
```
public final int getBitsPerSample()
```


Gets the bits per sample value.

**Returns:**
int - The bits per sample value.
