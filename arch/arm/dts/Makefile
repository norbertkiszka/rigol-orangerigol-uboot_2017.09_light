#
# SPDX-License-Identifier:	GPL-2.0+
#


dtb-$(CONFIG_ARCH_ROCKCHIP) += \
	rk3399-evb.dtb \
	rk3399-firefly.dtb \
	rk3399-orangerigol.dtb \
	rk3399-puma-ddr1333.dtb \
	rk3399-puma-ddr1600.dtb \
	rk3399-puma-ddr1866.dtb \
	rv1108-evb.dtb

targets += $(dtb-y)

# Add any required device tree compiler flags here
DTC_FLAGS +=

PHONY += dtbs
dtbs: $(addprefix $(obj)/, $(dtb-y))
	@:

clean-files := *.dtb
