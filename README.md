This is a NIX flake to address some of the issues i am having while moving over to NixOs. 

This flake has dev shell which adds access to a c compiler so i am able to compile rust code. 

This adds extra build imports, specifically for GUI and graphics. 
allows my VULKAN backend for WGPU: https://github.com/gfx-rs/wgpu
allows a openGL backend for use with egui: https://github.com/emilk/egui

This was thrown together late at night from bits and peices of other scripts i found online and added to the rust shell on the NixOs Wiki.
So its likely some of the build imports arent needed. 

