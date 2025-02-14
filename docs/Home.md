# YarnSpinner-Godot

Beta port of [YarnSpinner-Unity](https://github.com/YarnSpinnerTool/YarnSpinner-Unity) integration to the Godot Mono engine v4. It allows you to write dialogue in a simple, screenplay-like format. You have to use the Mono version of the engine which supports C#. 

This addon is heavily based on the code and user experience of the original YarnSpinner-Unity integration. As such, the number one resource for learning about the Yarn language syntax is [the official documentation of the YarnSpinner-Unity functionality](https://docs.yarnspinner.dev/). 

To the extent possible, deviations from the way that Unity integration works have been avoided so that the original documentation remains a good resource. The biggest exceptions are the specifics of how the plugin integrates with the Godot editor, and how engine-specific features like Localization work. Additionally, any use of coroutines from the Unity integration are replaced in YarnSpinner-Godot with `async Task`. 

This Wiki will describe what differences there are from the Unity version, and how to integrate the addon with your project.

For information about samples included in this repository, see [Samples](./Samples.md)
To begin using the plugin in your own project, [Install the plugin](./Installation.md)