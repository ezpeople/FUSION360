# FUSION360
SNAPMAKER A350+ENCLOSURE &amp; AUTODESK FUSION360 CAM SETTINGS FOR MACHINE, TOOLS + POSTPROCESSORS 

NOTES ON PATHS for MacOS (Apple Silicon):
- Local Post Processors are installed here: ~/Library/Application Support/Autodesk/Fusion 360 CAM
- Local Machines Definitions are here: ~/Library/Application Support/Autodesk/CAM360/machines
- Local Templates are here: ~/Library/Application Support/Autodesk/CAM360/templates
- Local Tools Library are here: ~/Library/Application Support/Autodesk/CAM360/libraries/Local
- VS Code Extension Autodesk Fusion Post Processor Utility is here: ~/.vscode/extensions/autodesk.hsm-post-processor-4.1.6 (4.1.6 as of today is the latest version)
- Post Processor Executable is here: ~/Library/Application Support/Autodesk/webdeploy/production/30bbf97dcd394de9009af5fcb50b947d5af1ceb6/Autodesk Fusion.app/Contents/Libraries/Applications/CAM360/post (considering 30bbf97dcd394de9009af5fcb50b947d5af1ceb6 identifies the latest installed version of Autodésk Fusion 360 for Mac)

NOTES ON Post Executable:
- Since it is downloaded, you got to unlock it:
  a. Open a Terminal
  b. cd to directory where the executable is
  c. run it: ./post ⏎
  d. a system popup is displayed to verify the executable, accept it
  e. you are done
- There is help but lacks a manual

NOTES ON VS Code Extension Autodesk Fusion Post Processor Utility:
- Took me hard times to figure where the executable is
- Once the extension is configured with the executable path, everything is working nicely
- The new debugger is great and works fine
- You got to generate intermediate custom files from G-Code and import it to the extension to make a post processor to working with a custom CNC file, see the Post Processor Training Guide, pages 53-54 (https://cam.autodesk.com/posts/posts/guides/Post%20Processor%20Training%20Guide.pdf)

THANKS:
- To @NunoOliveira (https://github.com/nunorvoliveira) for getting me up to speed with his Machine, Tools libraries and Post Processor for Snapmaker 2.0 (works great with my Snapmaker A350)
- To @shurushetr (https://github.com/shurushetr/awesome-snapmaker) for his exhaustive incredible list of ressources
