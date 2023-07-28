# DWL-IPC

dwl-ipc is a wayland protocol that is built to allow communication between wayland clients and the dwl compositor.

## Protocol Features
A list of features supported for each version of the protocol

 + dwl_manager
    + layout: V1,V2,V3
    + tag: V1
    + tag_amount: V2,V3
 + dwl_output
    + title: V1,V2,V3
    + appid: V1,V2,V3
    + tag: V1,V2
    + tags: V3
    + layout: V1,V2,V3
    + layout_symbol: V1,V2,V3
    + toggle_visibility: V1,V2,V3
    + active/selected: V1,V2,V3
    + fullscreen: V1,V2,V3
    + floating: V1,V2,V3
    + frame/done: V1,V2,V3
    + set_layout: V1,V2,V3
    + set_client_tags: V1,V2
        + with XOR and AND
    + set_client_tags: V3
        + with tagset
    + set_tags: V1,V2,V3
