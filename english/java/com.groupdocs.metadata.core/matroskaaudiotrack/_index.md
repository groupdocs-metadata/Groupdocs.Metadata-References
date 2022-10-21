---
title: MatroskaAudioTrack
second_title: GroupDocs.Metadata for Java API Reference
description: Represents audio metadata in a Matroska video.
type: docs
weight: 114
url: /java/com.groupdocs.metadata.core/matroskaaudiotrack/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage), [com.groupdocs.metadata.core.MatroskaBasePackage](../../com.groupdocs.metadata.core/matroskabasepackage), [com.groupdocs.metadata.core.MatroskaTrack](../../com.groupdocs.metadata.core/matroskatrack)
```
public class MatroskaAudioTrack extends MatroskaTrack
```

Represents audio metadata in a Matroska video.

**Learn more**

 *  [Working with metadata in Matroska (MKV) files][Working with metadata in Matroska _MKV_ files]


[Working with metadata in Matroska _MKV_ files]: https://docs.groupdocs.com/display/metadatajava/Working+with+metadata+in+Matroska+%28MKV%29+files
## Methods

| Method | Description |
| --- | --- |
| [getSamplingFrequency()](#getSamplingFrequency--) | Gets the sampling frequency in Hz. |
| [getOutputSamplingFrequency()](#getOutputSamplingFrequency--) | Gets the real output sampling frequency in Hz (used for SBR techniques). |
| [getChannels()](#getChannels--) | Gets the numbers of channels in the track. |
| [getBitDepth()](#getBitDepth--) | Gets the bits per sample, mostly used for PCM. |
### getSamplingFrequency() {#getSamplingFrequency--}
```
public final double getSamplingFrequency()
```


Gets the sampling frequency in Hz.

**Returns:**
double - The sampling frequency in Hz.
### getOutputSamplingFrequency() {#getOutputSamplingFrequency--}
```
public final double getOutputSamplingFrequency()
```


Gets the real output sampling frequency in Hz (used for SBR techniques).

**Returns:**
double - The real output sampling frequency in Hz (used for SBR techniques).
### getChannels() {#getChannels--}
```
public final long getChannels()
```


Gets the numbers of channels in the track.

**Returns:**
long - The numbers of channels in the track.
### getBitDepth() {#getBitDepth--}
```
public final Long getBitDepth()
```


Gets the bits per sample, mostly used for PCM.

**Returns:**
java.lang.Long - The bits per sample, mostly used for PCM.
