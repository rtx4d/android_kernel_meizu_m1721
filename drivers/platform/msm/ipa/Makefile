ifdef CONFIG_X86
ccflags-y += -DIPA_EMULATION_COMPILE=1
else
ccflags-y += -DIPA_EMULATION_COMPILE=0
endif

ccflags-y += -DIPA_DEBUG

obj-$(CONFIG_IPA) += ipa_v2/ ipa_clients/ ipa_common
obj-$(CONFIG_IPA3) += ipa_v3/ ipa_clients/ ipa_common
obj-$(CONFIG_IPA_UT) += test/

ipa_common += ipa_api.o ipa_rm.o ipa_rm_dependency_graph.o ipa_rm_peers_list.o ipa_rm_resource.o ipa_rm_inactivity_timer.o
