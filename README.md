This repo contains unofficial archive of STM32 libraries (www.st.com) we are interested in.

See wiki for more details.

The STM32 libraries and demo projects have separate branches per the MCU family:
F0 for STM32F0xxx, F4 for STM32F4xxx, and so on.

To get a specific version, check it out so that directory STM32Cube_FW_F0 in the repo
maps to a directory named STM32Cube_FW_F0_Vx.y.z

For example, label F0_V1.9.0 goes to STM32Cube_FW_F0_V1.9.0

The root directory of this repo can map to ...[STM32Cube]/Repository/
so the complete path to the version would be 
   ...[STM32Cube]/Repository/STM32Cube_FW_F0_V1.9.0

The STM32Cube_FW_F0/ subdirectory corresponds to the root of the official repo:
https://github.com/STMicroelectronics/STM32CubeF0   
   
*Patches* go into patches/ directory, and are applied relative to STM32Cube_FW_F0 .

Tags vs. branches: support branches can be later opened at the tagged releases, as needed.
NOTE: Tag names are different in the ST repo.  
