# Fly_IQ456

Здесь я собираю файлы, драйвера и т.п. которые мне подошли при создании ядра для Fly IQ456 Era Life 2.
Это уже рабочии драйвера для 456. Репозиторий будет обновляться.

/* Драйвера экрана */

CUSTOM_KERNEL_LCM = ili9806c_wvga_dsi_vdo
CUSTOM_LK_LCM = ili9806c_wvga_dsi_vdo
CUSTOM_UBOOT_LCM = ili9806c_wvga_dsi_vdo

/* Драйвера тача */

CUSTOM_KERNEL_TOUCHPANEL = ft6306

/* Размер экрана */

LCM_HEIGHT = 854 // 0x356
LCM_WIDTH = 480 // 0x1E0

/* TPD */

0x01:139:55:900:110:50:0x01:172:240:900:110:50:0x01:158:424:900:110:50

/* Исходники */
https://github.com/darklord4822/KK_kernel_lenovo_a369i // Lenovo A369I 4.4
https://github.com/rex-xxx/KK_kernel_iq4404_MT6572 // Fly IQ4404 4.4
http://git.huayusoft.com/tomsu/AP7200_MDK-kernel/tree/master //AP7200 4.2
https://github.com/LosTigeros/Trooper2_4.0_5.0_kernel	//Trooper2 4.2
https://github.com/kirito96/android_kernel_alcatel_4013D // Alcatel 4013D Дисплей и тач идентичен
https://github.com/kirito96/android_kernel_mts_982t // Почти идентичны (флеш память тоже)
