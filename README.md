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

