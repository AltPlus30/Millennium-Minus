<img width="3844" height="793" alt="image" src="https://github.com/user-attachments/assets/2c662772-bca1-4de4-988f-5304d7dfd87d" />

Millennium is an **open-source low-code modding framework** to create, manage and use themes/plugins<br/> for the desktop Steam Client without any low-level internal interaction or overhead.

If you enjoy this tool, please consider starring the original project: https://github.com/SteamClientHomebrew/Millennium

## This is my personal fork with failsafes removed. The approach here is deemed insecure by the original developer. There will be no support provided for it. Don't bug the dev about it and don't expect them to fix issues present here.

# You've been warned.

Q: Why?
A: The original Millenium release removes .cef-enable-remote-debugging file, which is essential for Decky Loader and similar tools to work. As mentioned here: https://github.com/SteamClientHomebrew/Millennium/issues/591 keeping this file is deemed insecure by the original developers. This fork simply removes the function to delete it on Steam's startup and does nothing else.
