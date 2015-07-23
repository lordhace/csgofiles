# README CS:GO Settings

## Settings
```shell
# Settings for launch options
-high -novid -threads 4

# Settings for network related things
fps_max 256; cl_updaterate 128; cl_cmdrate 128; cl_interp 0; cl_interp_ratio 1; rate 128000;

# CrossHair Color and Default Style
cl_crosshairstyle 4;cl_crosshairdot 1;cl_crosshairusealpha 0;cl_crosshairalpha 255;cl_crosshaircolor 5;cl_crosshaircolor_b 255;cl_crosshaircolor_r 255;cl_crosshaircolor_g 255;

# Pistol/Knife CrossHair
alias chx_pistol "cl_crosshairsize  0;cl_crosshairthickness 2;cl_crosshairgap 0;cl_crosshair_drawoutline 0;cl_fixedcrosshairgap 0;cl_crosshair_outlinethickness 0; bind x chx_m4;";

# AK CrossHair
alias chx_ak "cl_crosshairsize 23;cl_crosshairthickness 0.2;cl_crosshairgap -3;cl_crosshair_drawoutline 1; bind x chx_pistol;";

# M4 CrossHair
alias chx_m4 "cl_crosshairsize 17;cl_crosshairthickness 0.2;cl_crosshairgap -3;cl_crosshair_drawoutline 1; bind x chx_ak;";

# Custom Crosshir Color WHITE
alias chc_1 "cl_crosshaircolor 5;cl_crosshaircolor_b 255;cl_crosshaircolor_r 255;cl_crosshaircolor_g 255; bind c chc_2;";

# Custom Crosshir Color PINK
alias chc_2 "cl_crosshaircolor 5;cl_crosshaircolor_b 255;cl_crosshaircolor_r 255;cl_crosshaircolor_g 0; bind c chc_3;";

# Custom Crosshir Color CYAN
alias chc_3 "cl_crosshaircolor 4; bind c chc_4;";

# Custom Crosshir Color GREEN
alias chc_4 "cl_crosshaircolor 1; bind c chc_1";

# Default cross_hair color is for chc_2
bind c chc_2;

# Default cross hair stye is for chx_pistol
bind x chx_pistol;
```
