# Windows

## Caps Lock 

### What is? 

Caps-lock is kind of like the hard mute button switch on an iPhone  - You never know what status it's in. 
To disable the button and use the keyboard like a decent person, use the shift keys instead. 
If you're a professional then you're also using the left shift for left hand, and right shift for right hand. 

### What does it do? 

Adds a registry key to Windows that disable the Caps-lock functionality. 

### How to install 

Download and Run [CapsLock_Disable.reg](CapsLock_Disable.reg) to disable the caps-lock key. Windows restart is required. 

### How to uninstall 

Start Registry Editor or run 'regedit' in the Command Prompt for example
- Find the location HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Keyboard Layout
- Right-click on 'Scancode Map' and Delete the entry 

