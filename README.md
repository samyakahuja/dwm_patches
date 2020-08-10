# DWM Patches

This is my build of dwm which can be installed using `quilt`.

## Setup

- Clone the repository

    ```
    git clone --recursive https://github.com/samyakahuja/dwm_patches
    ```

- Activate all patches

    ```
    quilt push -a
    ```

- Build dwm

    ```
    cd dwm
    rm -r config.h
    sudo make install
    ```

## Patches Used

| Purpose                                    | Patch                                                                    | Suckless link                                                            |
| :----------------------------------------- | :----------------------------------------------------------------------- | :----------------------------------------------------------------------- |
| Change mod key to Super                    | [patches/mod_key.patch](patches/mod_key.patch)                           | No link                                                                  |
| Change font                                | [patches/font.patch](patches/font.patch)                                 | No link                                                                  |
| Set terminal to alacritty                  | [patches/term_and_master_size.patch](patches/term_and_master_size.patch) | No link                                                                  |
| Change key binding for `incmaster`         | [patches/increase_masters.patch](patches/increase_masters.patch)         | No link                                                                  |
| Moving and Resizing floating windows       | [patches/moveresize.patch](patches/moveresize.patch)                     | [suckless/moveresize](https://dwm.suckless.org/patches/moveresize/)      |
| Save size and position of floating windows | [patches/save_floats.patch](patches/save_floats.patch)                   | [suckless/save_floats](http://dwm.suckless.org/patches/save_floats)      |
| Move all floating windows to selected tag  | [patches/tagall.patch](patches/tagall.patch)                             | [suckless/tagall](https://dwm.suckless.org/patches/tagall)               |
| Swap focus with Alt-Tab                    | [patches/swapfocus.patch](patches/swapfocus.patch)                       | [suckless/swapfocus](https://dwm.suckless.org/patches/swapfocus)         |
| Add centeredmaster layout                  | [patches/centeredmaster.patch](patches/centeredmaster.patch)             | [suckless/centredmaster](https://dwm.suckless.org/patches/centredmaster) |
| Remove border when only one window         | [patches/noborder.patch](patches/noborder.patch)                         | [suckless/noborder](https://dwm.suckless.org/patches/noborder)           |

## Interesting Unapplied patches

- [pertag](https://dwm.suckless.org/patches/pertag)
