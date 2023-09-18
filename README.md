***Hi，kid.By the time you see this, I've addressed these issues and hope to help you***  

***By the way, before that, I hope you read the documentation again***





# How can I start to use PSO?

[Documentation](https://docs.unrealengine.com/4.26/en-US/SharingAndReleasing/PSOCaching/)

# FAQ

## Where is 'CollectedPSO' folder?  Where is 'rec.upipelinecache' file?

* After you have played through your project a few times,you can check under **ProjectName\Saved\StagedBuilds\WindowsNoEditor\GameName\Saved**

* ![image](https://github.com/Nanfengzhiwo1/TipsAboutPSO_UEOnWindows/assets/107869748/7043187e-c62c-4b5e-b300-29114460d906)
  
## Why didn't 'stablepc.csv' file be generated?

* have you see that?  

* ![Z%UEKX9@}TDLQ_O4JQ`V6QG](https://github.com/Nanfengzhiwo1/TipsAboutPSO_UEOnWindows/assets/107869748/d074943f-8454-49df-a735-c3ae1ca541ce)  

* You need to modify these parameters when you execute this command
  
* `ActionRPG`:Look at YourProjectName.uproject address and copy it.**Don't forget to put double quotes around the address**.

* `.scl.csv`:If you are using UE 4.27.2 or later,then you should **use .shk instead of .scl.csv.** 

* `ActionRPG_SF_ANDROID`:If you have completed the previous steps, now look at your 'PSOCaching' folder and focus on the file name, **everyone may be different**.

* ### Example(modify `ActionRPG`)  

* ![O_E 8DJHRMDQEY(F_(ZXMZS](https://github.com/Nanfengzhiwo1/TipsAboutPSO_UEOnWindows/assets/107869748/06dc95e5-31b2-43c8-a486-6f3bc9694547)
  
* ### Example(modify `ActionRPG_SF_ANDROID`)

* ![~F5E~$)TVV~(SOLPZED37 X](https://github.com/Nanfengzhiwo1/TipsAboutPSO_UEOnWindows/assets/107869748/a410a712-d266-4c63-8ac4-d094246cb76e)           

* ### My Target is for your reference：

* _E:\UE_4.27\Engine\Binaries\Win64\UE4Editor-Cmd.exe "E:\UE_4.27Project\PSO_LowPoly\PSO_LowPoly.uproject" -run=ShaderPipelineCacheTools expand C:\PSOCaching\*.rec.upipelinecache C:\PSOCaching\*.shk PSO_LowPoly-PCD3D_SM5.stablepc.csv_

# The Application of PSO in Game

***["You can setup the PSO cache compiling so that it will only happen when a UI, Cutscene or Pause Menu is opened"](https://docs.unrealengine.com/4.26/en-US/SharingAndReleasing/PSOCaching/CompilingUsingPSOCachingData/)***

* [《Rise Of Tomb Raider》](https://youtu.be/OjULOVma0Kc?t=1367)
