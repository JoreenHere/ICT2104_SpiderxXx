################################################################################
# Automatically-generated file. Do not edit!
################################################################################

SHELL = cmd.exe

CG_TOOL_ROOT := C:/ti/ccs910/ccs/tools/compiler/ti-cgt-arm_18.12.3.LTS

GEN_OPTS += C:/Users/Justin/workspace_v9/tirtos_builds_MSP_EXP432P401R_release_ccs/Debug/configPkg/compiler.opt
GEN_OPTS__FLAG := --cmd_file="C:/Users/Justin/workspace_v9/tirtos_builds_MSP_EXP432P401R_release_ccs/Debug/configPkg/compiler.opt"
GEN_CMDS += C:/Users/Justin/workspace_v9/tirtos_builds_MSP_EXP432P401R_release_ccs/Debug/configPkg/linker.cmd
GEN_CMDS__FLAG := -l"C:/Users/Justin/workspace_v9/tirtos_builds_MSP_EXP432P401R_release_ccs/Debug/configPkg/linker.cmd"

ORDERED_OBJS += \
"./main_tirtos.obj" \
"./syscfg/ti_drivers_config.obj" \
"./App/app.obj" \
"./App/global_val.obj" \
"./Basic/Delay/delay.obj" \
"./Basic/SystemInit/SystemInit.obj" \
"./Hardware/myiic/myiic.obj" \
"./Module/pca9685/pca9685.obj" \
"./Module/servo/servo.obj" \
"../MSP_EXP432P401R_TIRTOS.cmd" \
-l"ti/display/lib/display.aem4f" \
-l"ti/grlib/lib/ccs/m4f/grlib.a" \
-l"third_party/spiffs/lib/ccs/m4f/spiffs.a" \
-l"ti/drivers/lib/drivers_msp432p401x.aem4f" \
-l"third_party/fatfs/lib/ccs/m4f/fatfs.a" \
-l"ti/dpl/lib/dpl_msp432p401x.aem4f" \
$(GEN_CMDS__FLAG) \
-l"ti/devices/msp432p4xx/driverlib/ccs/msp432p4xx_driverlib.lib" \
-llibc.a \

-include ../makefile.init

RM := DEL /F
RMDIR := RMDIR /S/Q

# All of the sources participating in the build are defined here
-include sources.mk
-include subdir_vars.mk
-include App/subdir_vars.mk
-include Basic/Delay/subdir_vars.mk
-include Basic/SystemInit/subdir_vars.mk
-include Hardware/myiic/subdir_vars.mk
-include Module/pca9685/subdir_vars.mk
-include Module/servo/subdir_vars.mk
-include subdir_rules.mk
-include App/subdir_rules.mk
-include Basic/Delay/subdir_rules.mk
-include Basic/SystemInit/subdir_rules.mk
-include Hardware/myiic/subdir_rules.mk
-include Module/pca9685/subdir_rules.mk
-include Module/servo/subdir_rules.mk
-include objects.mk

ifneq ($(MAKECMDGOALS),clean)
ifneq ($(strip $(C55_DEPS)),)
-include $(C55_DEPS)
endif
ifneq ($(strip $(C_UPPER_DEPS)),)
-include $(C_UPPER_DEPS)
endif
ifneq ($(strip $(S67_DEPS)),)
-include $(S67_DEPS)
endif
ifneq ($(strip $(S62_DEPS)),)
-include $(S62_DEPS)
endif
ifneq ($(strip $(S_DEPS)),)
-include $(S_DEPS)
endif
ifneq ($(strip $(OPT_DEPS)),)
-include $(OPT_DEPS)
endif
ifneq ($(strip $(C??_DEPS)),)
-include $(C??_DEPS)
endif
ifneq ($(strip $(ASM_UPPER_DEPS)),)
-include $(ASM_UPPER_DEPS)
endif
ifneq ($(strip $(S??_DEPS)),)
-include $(S??_DEPS)
endif
ifneq ($(strip $(C64_DEPS)),)
-include $(C64_DEPS)
endif
ifneq ($(strip $(CXX_DEPS)),)
-include $(CXX_DEPS)
endif
ifneq ($(strip $(S64_DEPS)),)
-include $(S64_DEPS)
endif
ifneq ($(strip $(INO_DEPS)),)
-include $(INO_DEPS)
endif
ifneq ($(strip $(CLA_DEPS)),)
-include $(CLA_DEPS)
endif
ifneq ($(strip $(S55_DEPS)),)
-include $(S55_DEPS)
endif
ifneq ($(strip $(SV7A_DEPS)),)
-include $(SV7A_DEPS)
endif
ifneq ($(strip $(C62_DEPS)),)
-include $(C62_DEPS)
endif
ifneq ($(strip $(C67_DEPS)),)
-include $(C67_DEPS)
endif
ifneq ($(strip $(PDE_DEPS)),)
-include $(PDE_DEPS)
endif
ifneq ($(strip $(K_DEPS)),)
-include $(K_DEPS)
endif
ifneq ($(strip $(C_DEPS)),)
-include $(C_DEPS)
endif
ifneq ($(strip $(CC_DEPS)),)
-include $(CC_DEPS)
endif
ifneq ($(strip $(C++_DEPS)),)
-include $(C++_DEPS)
endif
ifneq ($(strip $(C43_DEPS)),)
-include $(C43_DEPS)
endif
ifneq ($(strip $(S43_DEPS)),)
-include $(S43_DEPS)
endif
ifneq ($(strip $(ASM_DEPS)),)
-include $(ASM_DEPS)
endif
ifneq ($(strip $(S_UPPER_DEPS)),)
-include $(S_UPPER_DEPS)
endif
ifneq ($(strip $(CPP_DEPS)),)
-include $(CPP_DEPS)
endif
ifneq ($(strip $(SA_DEPS)),)
-include $(SA_DEPS)
endif
endif

-include ../makefile.defs

# Add inputs and outputs from these tool invocations to the build variables 
EXE_OUTPUTS += \
uartecho_MSP_EXP432P401R_tirtos_ccs.out \

EXE_OUTPUTS__QUOTED += \
"uartecho_MSP_EXP432P401R_tirtos_ccs.out" \

BIN_OUTPUTS += \
uartecho_MSP_EXP432P401R_tirtos_ccs.hex \

BIN_OUTPUTS__QUOTED += \
"uartecho_MSP_EXP432P401R_tirtos_ccs.hex" \


# All Target
all: $(OBJS) $(CMD_SRCS) $(GEN_CMDS)
	@$(MAKE) --no-print-directory -Onone "uartecho_MSP_EXP432P401R_tirtos_ccs.out"

dependents:
	-cd C:/Users/Justin/workspace_v9/tirtos_builds_MSP_EXP432P401R_release_ccs/Debug && $(MAKE) clean all

# Tool invocations
uartecho_MSP_EXP432P401R_tirtos_ccs.out: $(OBJS) $(CMD_SRCS) $(GEN_CMDS) C:/Users/Justin/workspace_v9/tirtos_builds_MSP_EXP432P401R_release_ccs/Debug/tirtos_builds_MSP_EXP432P401R_release_ccs.lib
	@echo 'Building target: "$@"'
	@echo 'Invoking: ARM Linker'
	"C:/ti/ccs910/ccs/tools/compiler/ti-cgt-arm_18.12.3.LTS/bin/armcl" -mv7M4 --code_state=16 --float_support=FPv4SPD16 -me --advice:power=none --define=__MSP432P401R__ -g --diag_warning=225 --diag_warning=255 --diag_wrap=off --display_error_number --gen_func_subsections=on -z -m"uartecho_MSP_EXP432P401R_tirtos_ccs.map" -i"C:/ti/simplelink_msp432p4_sdk_3_30_00_13/source" -i"C:/ti/simplelink_msp432p4_sdk_3_30_00_13/kernel/tirtos/packages" -i"C:/ti/ccs910/ccs/tools/compiler/ti-cgt-arm_18.12.3.LTS/lib" --diag_wrap=off --display_error_number --warn_sections --xml_link_info="uartecho_MSP_EXP432P401R_tirtos_ccs_linkInfo.xml" --rom_model -o "uartecho_MSP_EXP432P401R_tirtos_ccs.out" $(ORDERED_OBJS)
	@echo 'Finished building target: "$@"'
	@echo ' '

uartecho_MSP_EXP432P401R_tirtos_ccs.hex: $(EXE_OUTPUTS)
	@echo 'Building files: $(strip $(EXE_OUTPUTS__QUOTED))'
	@echo 'Invoking: ARM Hex Utility'
	"C:/ti/ccs910/ccs/tools/compiler/ti-cgt-arm_18.12.3.LTS/bin/armhex"  -o "uartecho_MSP_EXP432P401R_tirtos_ccs.hex" $(EXE_OUTPUTS__QUOTED)
	@echo 'Finished building: $(strip $(EXE_OUTPUTS__QUOTED))'
	@echo ' '

# Other Targets
clean:
	-$(RM) $(GEN_MISC_FILES__QUOTED)$(BIN_OUTPUTS__QUOTED)$(GEN_FILES__QUOTED)$(EXE_OUTPUTS__QUOTED)
	-$(RM) "main_tirtos.obj" "syscfg\ti_drivers_config.obj" "App\app.obj" "App\global_val.obj" "Basic\Delay\delay.obj" "Basic\SystemInit\SystemInit.obj" "Hardware\myiic\myiic.obj" "Module\pca9685\pca9685.obj" "Module\servo\servo.obj" 
	-$(RM) "main_tirtos.d" "syscfg\ti_drivers_config.d" "App\app.d" "App\global_val.d" "Basic\Delay\delay.d" "Basic\SystemInit\SystemInit.d" "Hardware\myiic\myiic.d" "Module\pca9685\pca9685.d" "Module\servo\servo.d" 
	-$(RMDIR) $(GEN_MISC_DIRS__QUOTED)
	-@echo 'Finished clean'
	-@echo ' '

.PHONY: all clean dependents
.SECONDARY:
C:/Users/Justin/workspace_v9/tirtos_builds_MSP_EXP432P401R_release_ccs/Debug/tirtos_builds_MSP_EXP432P401R_release_ccs.lib:

-include ../makefile.targets

