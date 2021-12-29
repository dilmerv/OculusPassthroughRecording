These are few of the commands to use when [scrcpy](https://github.com/Genymobile/scrcpy) to record Oculus Quest Passthrough experiences.

# Default Command

```csharp
.\scrcpy
```

## Crop Options
```csharp
// Oculus Quest 2 Crop both eyes with max fps 30
.\scrcpy --crop 3664:1920:0:0 --max-fps 30
```

```csharp
// Oculus Quest 2 Crop one eye with max fps 30
.\scrcpy --crop 1832:1920:0:0 --max-fps 30
```

```csharp
// Oculus Quest 2 Crop one eye with max fps 30
.\scrcpy --crop 1832:1920:1832:0 --max-fps 30
```

```csharp
// Oculus Quest 2 Crop center area with max fps 30
.\scrcpy --crop 1730:974:1934:450 --max-fps 30
```

## BitRate Options

```csharp
// Oculus Quest with max fps 30 and 8 Mbps
.\scrcpy --max-fps 30 --bit-rate 8M
```

|Type|Video Bitrate, Standard Frame Rate (24, 25, 30)|Video Bitrate, High Frame Rate (48, 50, 60)|
|----|----|----|
|2160p(4K)|44–56 Mbps|66–85 Mbps|
|1440p(2K)|20 Mbps|30 Mbps|
|1080p|10 Mbps|15 Mbps|
|720p|6.5 Mbps|9.5 Mbps|

## Helpful Overall Settings
<img src="https://github.com/dilmerv/OculusPassthroughRecording/blob/master/images/settings.jpg" width="250">

Credits and huge thanks to [Greg Madison](https://twitter.com/GregMadison) for providing the helpful settings above !
