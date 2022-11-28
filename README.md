# vs-fsharp-android-namespace-issue
Shows issue with Visual Studio 2022 and automatic adding of Android namespaces

Screen recording of issue

![Issue recording](https://github.com/bent-rasmussen/vs-fsharp-android-namespace-issue/blob/main/F%23-android.gif)

Screenshot of Add New Item dialog

![Issue screenshot](https://github.com/bent-rasmussen/vs-fsharp-android-namespace-issue/blob/main/F%23-android.png)

See below*

The problem persists regardless of whether I create a new F# Console project or a new F# Library project. I was not able to create a screenshot from the popup Window, as the VS feedback mechanism does not seem to have that feature. The Add New Item window shows:

I have tried to attach my screen recording for a brand new F# project (.NET 6 - but my existing project is .NET 7 - so it does not depend on that): But then I get an "Upload failed. Unable to get file upload info."

So here is a web upload instead.




...

* Trying to use "My Feedback" from Visual Studio shows a web page with this (so I guess the repeated auth problem is showing its face again):

```
ERR_SEND_API: 403 Forbidden: 

POST: /searchquery/searchV2 authRequired=True **{"searchFor":{"trackingId":"2bbe864caf9043f5b794147b092aa3b3","source":"Send a smile","culture":"en-DK","uiculture":"en-US","userType":"External","correlationIdentity":"588d6c53-6aa9-496c-97af-aa2ccdb682a4:0:0","tags":[{"type":"user-id","value":"{f4e63bd5-9083-4029-8dbe-1084d01ee7f0}"},{"type":"machine-id","value":"{6d26a50a-3646-4971-8d54-9863edd696e8}"},{"type":"mac-address-hash","value":"21f6d1711118706d2704839e7306a7950130481e49af2a497a2d6340e0b1024f"},{"type":"user-alias","value":""},{"type":"os-arch","value":"AMD64"},{"type":"vs-arch","value":"AMD64"},{"type":"arch-new","value":"true"},{"type":"user-os-ui-locale","value":"en-US"},{"type":"dpl-settings-enabled","value":"False"},{"type":"vs-lowimpact-enabled","value":"true"},{"type":"vs-lowimpact-installname","value":"visualstudio/17.4.0+33103.184"},{"type":"vs-lowimpact-installversion","value":"17.4.33103.184"},{"type":"vs-lowimpact-installworkloads","value":"microsoft.visualstudio.workload.coreeditor,microsoft.visualstudio.workload.netweb,microsoft.visualstudio.workload.netcrossplat,microsoft.visualstudio.workload.manageddesktop"},{"type":"os-version","value":"10.0"},{"type":"os-build","value":"10.0.22621.0"},{"type":"ndp-ver","value":"Client.4.8.09032.533320;Full.4.8.09032.533320;Client.4.0.0.0;"},{"type":"vsts-username","value":"6e039768-fe6d-6f08-b179-d852f494528b"},{"type":"vs-otuid","value":"6e039768-fe6d-6f08-b179-d852f494528b"},{"type":"vs-providerid","value":"aad"},{"type":"is-nexus","value":"false"},{"type":"prj-kind","value":"{f2a71f9b-5d33-465a-a702-920d77279786}"},{"type":"prj-flavor-guids","value":""},{"type":"prj-target-framework","value":".NETCoreApp,Version=v7.0"},{"type":"prj-target-platform","value":"Windows"},{"type":"experiment","value":"lazytoolboxinit"},{"type":"experiment","value":"fwlargebuffer"},{"type":"experiment","value":"refactoring"},{"type":"experiment","value":"spmoretempsbtn1"},{"type":"experiment","value":"asloff"},{"type":"experiment","value":"keybindgoldbarext"},{"type":"experiment","value":"asynccsproj"},{"type":"experiment","value":"vsfricheditor"},{"type":"experiment","value":"completionapi"},{"type":"experiment","value":"typeimportcompletion"},{"type":"experiment","value":"multitenanttasmigration_002"},{"type":"experiment","value":"nugetrecommendpkgs"},{"type":"experiment","value":"vites718"},{"type":"experiment","value":"disablerecoverabletreescf"},{"type":"experiment","value":"viopt689"},{"type":"experiment","value":"mauiwinui"},{"type":"experiment","value":"whatsnew172"},{"type":"experiment","value":"nugettransitivedependenciesinpmui"},{"type":"experiment","value":"vstecommitgraphnotification"},{"type":"experiment","value":"roslyncorehost"},{"type":"experiment","value":"identityserviceonnetcore"},{"type":"experiment","value":"vsttkcf"},{"type":"experiment","value":"guidesinstructional"},{"type":"experiment","value":"vsttkdebugcheckerexpcf"},{"type":"feedback-session-id","value":"7bf7c2f5-54df-4d38-a054-c351754a8f5f"},{"type":"source-dialog","value":""},{"type":"vote-userid","value":"vsId:6e039768-fe6d-6f08-b179-d852f494528b"},{"type":"vsts-email","value":"bent.rasmussen@stati-cal.com"},{"type":"vsts-displayname","value":"Bent Rasmussen"}],"version":20220110,"text":"","customerChosenArea":null,"user":"bent.rasmussen@stati-cal.com","title":"","dotNetEntries":[],"watsonEntries":[]},"skip":0,"take":20,"sort":"active","filter":"follow","stateGroup":null,"version":3,"topicsToFilterBy":[],"returnTotalCount":false,"typesFilterFlags":1,"includeCountsByType":true,"searchStartTimeMsec":1669630705389,"searchSource":"MyFeedbackList","clientVersion":"1.0.151","capabilities":{"canDisplayTypedMarkdown":true,"expRichEditor":true,"rawTextSupport":true,"expFlights":"lazytoolboxinit;fwlargebuffer;refactoring;spmoretempsbtn1;asloff;keybindgoldbarext;asynccsproj;vsfricheditor;completionapi;typeimportcompletion;multitenanttasmigration_002;nugetrecommendpkgs;vites718;disablerecoverabletreescf;viopt689;mauiwinui;whatsnew172;nugettransitivedependenciesinpmui;vstecommitgraphnotification;roslyncorehost;identityserviceonnetcore;vsttkcf;guidesinstructional;vsttkdebugcheckerexpcf;lazytoolboxinit;fwlargebuffer;refactoring;spmoretempsbtn1;asloff;keybindgoldbarext;asynccsproj;vsfricheditor;completionapi;typeimportcompletion;multitenanttasmigration_002;nugetrecommendpkgs;vites718;disablerecoverabletreescf;viopt689;mauiwinui;whatsnew172;nugettransitivedependenciesinpmui;vstecommitgraphnotification;roslyncorehost;identityserviceonnetcore;vsttkcf;guidesinstructional;vsttkdebugcheckerexpcf"}}**
```

