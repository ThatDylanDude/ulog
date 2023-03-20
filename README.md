# ulog & glog

Simple snippets for Unreal Engine in Visual Studio. All relevant arguments are editable by tabbing thru them such just like your typical 'for loop' snippet.

&nbsp;

Type ulog and hit tab to expand to: 

    UE_LOG(LogTemp, Display, TEXT(""));

&nbsp;

Type glog and hit tab to expand to:

    if (GEngine)
    {
        FString Message = FString::Printf(TEXT(""));
        GEngine->AddOnScreenDebugMessage(0, 60.f, FColor::Green, Message);
    }

&nbsp;

### To Install:

1) Download the snippets and save them wherever. By default Visual Studio creates "Documents/Visual Studio < Year >/Code Snippets/< Languages >/My Code Snippets". I would recommend downloading to "Documents/Visual Studio < Year >/Code Snippets/C++/My Code Snippets"

2) Open the Code Snippets Manager (Tools > Code Snippet Manager or Ctrl-K, Ctrl-B)

3) If the "My Code Snippets" folder is not listed, click Add and select the folder you've saved the snippets to.
