dtb-$(CONFIG_ARCH_VEXPRESS) += rtsm_ve-aemv8a.dtb foundation-v8.dtb
dtb-$(CONFIG_ARCH_XGENE) += apm-mustang.dtb

targets += dtbs

#used for cleaning - not building
subdir- := dts/qcom

.PHONY: dtbs
dtbs: $(addprefix $(obj)/, $(DTB_LIST))
	@true

clean-files := dts/*.dtb *.dtb
