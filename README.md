
# matToGA4, Parameters Conversion Tool
This tool is designed to convert Universal Google Analytics parameters into GA 4 parameters. It’s a simple HTML file that can be used to map Universal Analytics name-value pairs to their corresponding GA 4 parameters.

## How to Use
1. Enter the Universal Analytics name-value pairs in the first input field. These should be comma-separated values, similar to a JavaScript object but without {}.
2. You can either manually enter the builder type (**without{}**) from the **tagging-library** or use the select field below if the desired builder is available up-to-date in the options list.
3. After clicking on the "Get to clipboard corresponding GA4" button, the mapped values will be displayed in the textarea. These can be directly copied to the clipboard. If there are optional GA 4 parameters in the builder type that don’t have corresponding data in Universal Analytics, those properties will not be included in the new object.
<img width="1725" alt="image" src="https://github.com/janos-gyarmati/mapToGa4/assets/149151738/d3eb8951-8bc9-4644-8818-16f189f7e5fc">

## Quick Check for Universal Custom Dimension
For a quick check of a Universal Custom Dimension (CD), simply enter the CD number and click on the "Get GA4" button. The corresponding GA 4 param of that Custom Dimension will be displayed in the textarea.
<img width="1719" alt="image" src="https://github.com/janos-gyarmati/mapToGa4/assets/149151738/b37c4688-78e9-45d2-b3f3-951982a179a5">

## Note
Please be aware that this tool might contain bugs, and manual checking of the mapping is advised to ensure accuracy.
## Feedback
Your feedback is valuable in helping to improve this tool. If you encounter any issues or have any suggestions, please let us know. Enjoy converting!
