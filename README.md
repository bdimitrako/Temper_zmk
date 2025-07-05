![Diagram of config](keymap-drawer/temper.svg)

# Keyboard Layout Documentation

## Table of Contents
1. [Base Layout](#base-layout)
2. [Thumb Clusters](#thumb-clusters)
   - [On Tap](#on-tap)
   - [On Hold](#on-hold)
   - [Two-Key Combos](#two-key-combos)
   - [Three-Key Combos (Layer Toggles)](#three-key-combos-layer-toggles)
3. [Numbers Layer](#numbers-layer)
4. [Symbols Layer](#symbols-layer)
5. [Navigation Layer](#navigation-layer)
6. [Mouse Layer](#mouse-layer)
7. [Function Layer](#function-layer)
8. [Bluetooth Media Layer](#bluetooth-media-layer)
9. [Photos](#photos)

## Base Layout  
The foundation is **Colemak-DH**, with additional modifications on the right hand.  
- Instead of `/` on the bottom-row pinky key, there is `;`, which in Greek is used for accenting letters (e.g., ά, έ, ί, ό, ή, ύ, ώ) and shifted accents like ϊ.  
- Instead of `;` on the top-row pinky key, there is `'`.  
- This layout **does not** include home-row mods, as it is designed for speed, minimizing accidental modifier activations while typing or switching between Greek and English—even within the same sentence.  

## Thumb Clusters  

### On Tap  
**Left:** `Esc`, `Space`, `Shift-next-character`  
**Right:** `Enter`, `Backspace`, `Delete`  

- **Neutral thumb positions** (easiest to reach) are assigned to **Space** and **Backspace**, as they are the most frequently used.  
- **Outer thumb positions** (faster but less precise) are used for **Shift-next-character** (e.g., capitalizing the first letter in a rolling motion) and **Enter** (for quick new-line creation).  
- **Inner thumb positions** (harder to reach) are used for **Escape** and **Delete**, as they are less common and should not be hit accidentally.  
- The layout is strongly influenced by **Miryoku**, though **Tab** was replaced with **Shift-next-character** on the left outer thumb key.  

### On Hold  
**Left:** `Bluetooth`, `Navigation`, `Numbers`  
**Right:** `Symbols`, `Mouse`, `Function`  

- Inspired by **Miryoku**, where one thumb activates a layer while the other hand uses that layer's main keys and combos.  
- Standard Miryoku assigns `Media`, `Navigation`, `Mouse` on the left and `Symbols`, `Numbers`, `Function` on the right.  
- However, I swapped **Numbers** and **Mouse** because I found it unnatural to type numbers with my left hand.  
- Since the **Numbers layer** is used frequently, it shouldn't be placed in the inner palm position. Instead, it occupies the **left outer palm key**, keeping **Navigation** in the **neutral thumb position**.  
- This change led to placing the **Mouse trigger** in the **right-hand neutral thumb position**, as it mirrors the **inverted-T movement pattern** I use in games with my left hand.  

### Two-Key Combos  
Having **Choc switches and flat keycaps** enables comfortable multi-key presses with a single finger.  

- **Single middle-left finger (`F`, `S`)** → Activates a **single digit** from the **Numbers layer** and returns to base.  
- **Single middle-right finger (`U`, `E`)** → Activates a **single digit** from the **Symbols layer** and returns to base.  
- **Both momentary and sticky layer triggers** remain consistent with the hand used to activate them.  

Since **Tab** was moved to the left outer thumb key, I needed a **quick-access Tab key**:  
- **Single right index finger (`L`, `N`)** → **Tab**  
- **Single left index finger (`P`, `T`)** → **Switch language (`Win+Space` / `Alt+Shift`)**, allowing seamless Greek-English transitions within a sentence.  

### Three-Key Combos (Layer Toggles)  
For **Mouse** and **Navigation** layers, I needed a more ergonomic toggle option, as I spend extended time in these modes while browsing or navigating files.  

- A **three-key, three-finger combo** was created for each layer, using dominant fingers in their **neutral positions**.  
- These toggle triggers are placed within the **Mouse and Navigation key zones**, allowing:  
  - **Single-handed use** (e.g., when using a mouse or holding a coffee).  
  - **Convenient layer switching** without disrupting workflow.  

All other layers contain a set of home row modifiers allowing the auto repeat on those keypresses on the triggering hand and a top row sticky modifiers for easier rolling actions shortcuts involving a single modifier.

## Numbers Layer  
The **Numbers layer** is structured similarly to a numpad, prioritizing efficiency in numeric entry and utilizing my existing muscle memory on numpads of other keyboards.  
- **Top row:** `7 8 9`  
- **Home row:** `4 5 6 0` zero is nicely located in the home row pinky position. 
- **Bottom row:** `1 2 3`  
- Additional functions include `+`, `-`, `*`, `/`, and `=` for fast calculations in a single column.
- Number toggle to get back to base.

## Symbols Layer  
The **Symbols layer** includes frequently used programming and punctuation symbols.  
- Layout follows a **logical grouping**:  
  - `=`, `&`, `*`, `^`, `'` easy to find pinky finger equal and quick bullets in middle finger.
  - `!`, `@`, `#`, `$`, `%`  following a normal keyboard `1 2 3 4 5` shifted positions.
  - `[`, `(`, `)`, `]`, `\` the parentesis and brackets are symmetrical as per the middle of the columns.
  - `?`,`/` by having both thumbs rolling to give slash the character that was original on base Colemak-DH
- On the right hand side there are braces and dashes in an easy location for single handed typing.  

## Navigation Layer  
- Provides **efficient text and file navigation** without moving hands from the home position.  
- **Left hand:** Home, End, Page Up, Page Down.  
- **Right hand:** Arrow keys in an inverted-T layout.  
- Additional keys: `Ctrl+Arrow` shortcuts for faster word movement.  

## Mouse Layer  
- Designed for **precise control** over cursor movement.  
- **Left-hand inverted-T movement** mirrors gaming muscle memory.  
- **Left-hand shortcuts**: Left click, Right click, Middle click, Scroll and extra mouse buttons for browsing.  
- Mouse toggle to get back to base.  

## Function Layer  
- Includes **F1-F12 keys** in a standard layout.  
- Macro shortcuts: Custom scripts for automation available from Microsoft Power Toys on the right hand side.

## Bluetooth Media Layer  
- **Left hand:**  
  - `Boot` This allows to enter the bootloader to prep the keyboard for firmware flashing through usb type c. Found out that both the layer trigger and the boot button should be on the same split keyboard part or it wouldn't work.
- **Right hand:** Media control keys and Bluetooth connections and device switching.  
  - `Clear current bluetooth profile`, `BT1`, `BT2`, `BT3` , `BT4`, `BT5` for different devices.
  - `Toggle Microfone`, `Volume Up`, `Volume Down`.  Here lives a windows `Win+Alt+K` shortcut for microphone toggle across device's apps, even when they do not have the active focus. 
  - `Play/Pause`, `Next Track`, `Previous Track` The **Media Layer** allows quick control of music or video playback without disrupting workflow.  

This structure ensures a **balanced, efficient workflow** across typing, navigation, programming, and mouse control while maintaining **ergonomic comfort**.

## Photos
![photo01](photos/IMG_20250310_170347.jpg)
![photo02](photos/IMG_20250310_170352.jpg)
![photo03](photos/IMG_20250310_193301.jpg)
![photo04](photos/IMG_20250310_193310.jpg)
![photo05](photos/IMG_20250310_193332.jpg)
![photo06](photos/IMG_20250310_193345.jpg)
![photo07](photos/IMG_20250310_193424.jpg)
![photo08](photos/IMG_20250310_193434.jpg)
![photo09](photos/IMG_20250705_132208.jpg)
