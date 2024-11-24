# Unity-Script-Templates

This repository provides a variety of pre-built script templates designed to streamline your Unity development workflow, saving you time and effort when creating new scripts.

Feel free to explore, use, and customize these templates to suit your project's needs. Happy coding!


## Setup

1. Download the `ScriptTemplates` folder and place it directly inside the `Assets` folder of your Unity project.  
   **Note:** The `ScriptTemplates` folder must remain within the `Assets` directory and should not be moved elsewhere.  
2. Restart the Unity Editor to reload the templates.  
3. Access the templates by right-clicking in the **Project** window and selecting **Create**.

## Create Your Own Custom Template

You can add your own custom script templates to further tailor the development process to your needs. Follow these steps:

### Step 1: Create a Template File

- Navigate to the `Assets/ScriptTemplates` folder in your project.  
- Create a new `.txt` file with the following naming format: `81-C# Script__[Name in Editor]-[File Name].cs.txt` 

### Step 2: Edit the Template Content

Open the newly created .txt file and define the default content for your template. Use placeholders to make the script dynamic:  
- `#SCRIPTNAME#`: Automatically replaced by the name of the new file when it is created.  
- `#ROOTNAMESPACE#`: Replaced by the default namespace if configured in Unity.  

**Example Template Content**:  
```csharp
using UnityEngine;

namespace #ROOTNAMESPACE#
{
  public class #SCRIPTNAME# : MonoBehaviour
  {
      private void Awake()
      {

      }
  }
}
```
### Step 3: Use Your Custom Template
1. After editing and saving your template file, restart the Unity Editor for the new template is loaded.
2. Right-click in the **Project** window in Unity.
3. Navigate to **Create**, and you will see your custom template listed under the name specified in **[Name in Editor]**.
4. Select the template, and Unity will create a new file based on your custom settings.
