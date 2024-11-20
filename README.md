<img src="https://github.com/galaxytreesoftware/quantum-launcher-client/assets/124552176/78b9da8b-5fef-4f13-a9d6-7a263b2ca7fb" width="800" />

# What is Quantum Game Launcher?
Quantum Game Launcher is a fast and free Windows application (Linux and Mac coming eventually) written in Java, Rust and Javascript, designed to combine all of your games into one central location. It is designed to be the first and final destination for those who are into legal emulation. Those who are experienced and even those who have no experience at all are made to feel at home. No tutorials needed, because the program itself lends a helping hand.


<img src="https://github.com/galaxytreesoftware/quantum-launcher-client/assets/124552176/04295656-04c2-443c-9a04-e9259f081084" width="1000" />

## Current state of the project
We are currently at version 0.3.3 BETA. Development began September 2022. Some features may be noticeably incomplete, but a lot of the core foundation is ready. You can import your games, download metadata for them, and launch them through your emulators. Development is non-linear and may seem slow, but that is because we develop to a high standard and focus on unique features. The latest releases are not currently public, 

## Current Features
**Automated ROM scanner**

Features an automated ROM scanner that is fast, even when games are within zip files, or detecting more difficult game formats, such as Playstation 3 and Wii U.

<img src="https://github.com/galaxytreesoftware/quantum-launcher-client/assets/124552176/f4698755-c4e7-4e23-9df2-02a55f1599e2" width="800" />

**Emulator Scanner**

Quickly search your entire PC for installed emulators, and import them in one click. Launch parameters are automatically configured and can be changed before launch. No manual setup needed. If emulators aren't pre-installed, you can also download them through the application.

<img src="https://github.com/galaxytreesoftware/quantum-launcher-client/assets/124552176/05356dfe-1762-4973-bcc2-48ae6e1649c2" width="800" />

**Manage Multiple Emulators**

For when compatability differs between versions or emulators, maintain multiple versions of each emulator. Try the latest versions to see if there are improvements or regressions.
Quantum Launcher can check if the emulator has been setup yet (if it needs a BIOS file etc.) and assist in the process. Also receive helpful hints, such as when the emulator does not support the file format of a game, removing the ambiguity of "failed to launch" messages.

<img src="https://github.com/galaxytreesoftware/quantum-launcher-client/assets/124552176/dfca242c-29c3-45e4-a38d-a134e059eec9" width="800" />

**Pause Screen Overlay**

At any time during gameplay, press the controller hotkey to bring up the pause screen and use your gamepad to exit emulation and return to the user interface or perform emulator specific functionality.
Add your own entries to the menu by setting custom hotkey combinations to change discs etc.

<img src="https://github.com/galaxytreesoftware/quantum-launcher-client/assets/124552176/51381ebc-e7f2-4753-b940-9e6e3111a852" width="800" />

**Import Games From Various Storefronts**

With zero configuration, import all of your games from various storefronts, ready to launch within seconds.

![import from storefront](https://github.com/user-attachments/assets/dae9d679-cdb5-4c3b-a50f-21e952f609b6)

**Partial Support For EmulationStation Desktop Edition Themes**

Download and use ES-DE themes to launch your games with style.

<div style="display: flex; flex-wrap: wrap; gap: 10px;">
  <img width="49%" alt="es-de-theme-2" src="https://github.com/user-attachments/assets/2b49bb9e-05bd-4a82-a2d2-11e23a363039">
<img width="49%" alt="es-de-theme-1" src="https://github.com/user-attachments/assets/26ac2b9c-298b-479b-b82a-b0d4e55016f4">
  <img width="49%" alt="es-de-theme-7" src="https://github.com/user-attachments/assets/c428f816-426b-41de-94dd-e480c10f8421">
<img width="49%" alt="es-de-theme-6" src="https://github.com/user-attachments/assets/5a9592e1-9887-40f4-b354-9bd98142764c">
<img width="49%" alt="es-de-theme-4" src="https://github.com/user-attachments/assets/22e52413-9cef-47b4-a190-02ada512c912">
<img width="49%" alt="es-de-theme-3" src="https://github.com/user-attachments/assets/c41c1c79-e071-48ee-97d7-83c152273473">
<img width="49%" alt="es-de-theme-5" src="https://github.com/user-attachments/assets/a7d397e9-54e8-4c2c-a010-03e023fc0f8d">
  <img width="49%" alt="es-de-theme-8" src="https://github.com/user-attachments/assets/3e837d9e-796f-4fa4-9bf9-354fb34683fe">
</div>

**Controller Support**

Plug and play support for the most common game controllers such as Xbox, PS4 and PS5.


**Efficiency at the forefront**

A typical startup time of ~1sec for 1000 games, the entire application package is around ~70MB, memory usage of ~400mb and an ultra optimised grid view capable of displaying hundreds of thousands of game entries without any distinguishable interface lag.
Experimental unreleased builds have lowered memory usage by ~100mb, and have been able to lower startup time to 400 milliseconds consistently. All tests were done on hardware 2 generations old.

## Proposed Features

- **Live preview of controller mappings**

Remembering controller mappings when emulating various consoles can certainly be confusing. At any time, press the hotkey to bring up the pause screen and get a live preview of your current controller and the controller of the emulated console, and see how each button or axis is mapped. 


<video width="400" height="400" src="https://github.com/galaxytreesoftware/quantum-launcher-client/assets/124552176/92bf5769-a650-4b05-b7d7-ae66df2127d8">
