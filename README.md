[18:34:30] [main/INFO]: ModLauncher running: args [--username, Clouddser, --version, forge-36.2.26, --gameDir, C:\Users\Jeremy\curseforge\minecraft\Instances\All the Mods 6 - ATM6 - 1.16.5, --assetsDir, C:\Users\Jeremy\curseforge\minecraft\Install\assets, --assetIndex, 1.16, --uuid, d15e14417d3940b18956c962c5f5f107, --accessToken, ????????, --userType, msa, --versionType, release, --width, 1024, --height, 768, --launchTarget, fmlclient, --fml.forgeVersion, 36.2.26, --fml.mcVersion, 1.16.5, --fml.forgeGroup, net.minecraftforge, --fml.mcpVersion, 20210115.111550]
[18:34:30] [main/INFO]: ModLauncher 8.1.3+8.1.3+main-8.1.x.c94d18ec starting: java version 1.8.0_51 by Oracle Corporation
[18:34:30] [main/WARN]: LEGACY JDK DETECTED, SECURED JAR HANDLING DISABLED
[18:34:31] [main/INFO]: OptiFineTransformationService.onLoad
[18:34:31] [main/INFO]: OptiFine ZIP file: C:\Users\Jeremy\curseforge\minecraft\Instances\All the Mods 6 - ATM6 - 1.16.5\mods\OptiFine_1.16.5_HD_U_G8 (3).jar
[18:34:31] [main/INFO]: Target.PRE_CLASS is available
[18:34:31] [main/INFO]: Added Lets Encrypt root certificates as additional trust
[18:34:31] [main/INFO]: SpongePowered MIXIN Subsystem Version=0.8.4 Source=file:/C:/Users/Jeremy/curseforge/minecraft/Install/libraries/org/spongepowered/mixin/0.8.4/mixin-0.8.4.jar Service=ModLauncher Env=CLIENT
[18:34:31] [main/INFO]: OptiFineTransformationService.initialize
[18:34:33] [main/INFO]: [org.antlr.v4.runtime.ConsoleErrorListener:syntaxError:38]: line 13:0 token recognition error at: '`'
[18:34:33] [main/INFO]: [org.antlr.v4.runtime.ConsoleErrorListener:syntaxError:38]: line 1:0 token recognition error at: '~'
[18:34:33] [main/INFO]: OptiFineTransformationService.transformers
[18:34:33] [main/INFO]: Targets: 311
[18:34:34] [main/INFO]: additionalClassesLocator: [optifine., net.optifine.]
[18:34:34] [main/INFO]: Successfully loaded Mixin Connector [shetiphian.core.mixins.MixinConnector]
[18:34:34] [main/INFO]: Successfully loaded Mixin Connector [vazkii.botania.common.MixinConnector]
[18:34:34] [main/INFO]: Successfully loaded Mixin Connector [com.thevortex.allthetweaks.mixin.MixinConnector]
[18:34:34] [main/INFO]: Successfully loaded Mixin Connector [com.leobeliik.extremesoundmuffler.MixinConnector]
[18:34:34] [main/INFO]: Successfully loaded Mixin Connector [vazkii.patchouli.common.MixinConnector]
[18:34:34] [main/INFO]: Successfully loaded Mixin Connector [eutros.framedcompactdrawers.MixinConnector]
[18:34:34] [main/INFO]: Launching target 'fmlclient' with arguments [--version, forge-36.2.26, --gameDir, C:\Users\Jeremy\curseforge\minecraft\Instances\All the Mods 6 - ATM6 - 1.16.5, --assetsDir, C:\Users\Jeremy\curseforge\minecraft\Install\assets, --uuid, d15e14417d3940b18956c962c5f5f107, --username, Clouddser, --assetIndex, 1.16, --accessToken, ????????, --userType, msa, --versionType, release, --width, 1024, --height, 768]
[18:34:34] [main/WARN]: Reference map 'findme.refmap.json' for findme.mixins.json could not be read. If this is a development environment you can ignore this message
[18:34:34] [main/WARN]: Reference map 'modid.refmap.json' for rsinfinitybooster.mixins.json could not be read. If this is a development environment you can ignore this message
[18:34:34] [main/WARN]: Reference map 'rhino-forge-refmap.json' for rhino.mixins.json could not be read. If this is a development environment you can ignore this message
[18:34:34] [main/WARN]: Reference map 'ponderjs.refmap.json' for ponderjs.mixins.json could not be read. If this is a development environment you can ignore this message
[18:34:34] [main/INFO]: Patching ModelBakery#<init>
[18:34:35] [main/INFO]: Adding 'add_custom_entity_collision' ASM patch...
[18:34:35] [main/INFO]: Added 'add_custom_entity_collision' ASM patch!
[18:34:35] [main/INFO]: Adding 'reach_set_server_entity_interact' ASM patch...
[18:34:35] [main/INFO]: Added 'reach_set_server_entity_interact' ASM patch!
[18:34:35] [main/INFO]: Adding 'allow_entity_interaction' ASM patch...
[18:34:35] [main/INFO]: Added 'allow_entity_interaction' ASM patch!
[18:34:35] [main/INFO]: Patching net/minecraft/item/EnchantedBookItem
[18:34:35] [main/INFO]: Patching CrossbowItem#onItemRightClick
[18:34:35] [main/INFO]: Patching CrossbowItem#fireProjectile
[18:34:35] [main/INFO]: Patching Item#getItemEnchantability
[18:34:35] [main/INFO]: Adding 'set_player_field' ASM patch...
[18:34:35] [main/INFO]: Added 'set_player_field' ASM patch!
[18:34:35] [main/INFO]: Patching LivingEntity#attackEntityFrom
[18:34:35] [main/INFO]: Patching LivingEntity#blockUsingShield
[18:34:35] [main/INFO]: Patching LivingEntity#applyPotionDamageCalculations
[18:34:35] [main/INFO]: Adding 'water_movement_slowdown_prevention' ASM patch...
[18:34:35] [main/INFO]: Added 'water_movement_slowdown_prevention' ASM patch!
[18:34:35] [main/ERROR]: Error occurred applying transform of coremod META-INF/asm/multipart.js function render
java.lang.NullPointerException: null
	at org.objectweb.asm.tree.InsnList.insert(InsnList.java:343) ~[asm-tree-9.1.jar:9.1]
	at jdk.nashorn.internal.scripts.Script$Recompilation$185$5956A$\^eval\_.initializeCoreMod$transformer-3(<eval>:135) ~[?:?]
	at jdk.nashorn.internal.runtime.ScriptFunctionData.invoke(ScriptFunctionData.java:638) ~[nashorn.jar:?]
	at jdk.nashorn.internal.runtime.ScriptFunction.invoke(ScriptFunction.java:229) ~[nashorn.jar:?]
	at jdk.nashorn.internal.runtime.ScriptRuntime.apply(ScriptRuntime.java:387) ~[nashorn.jar:?]
	at jdk.nashorn.api.scripting.ScriptObjectMirror.call(ScriptObjectMirror.java:110) ~[nashorn.jar:?]
	at net.minecraftforge.coremod.NashornFactory.lambda$getFunction$0(NashornFactory.java:18) ~[coremods-4.0.6.jar:4.0.6+14+master.c21a551]
	at net.minecraftforge.coremod.NashornFactory$$Lambda$444/190838539.apply(Unknown Source) ~[?:?]
	at net.minecraftforge.coremod.transformer.CoreModMethodTransformer.runCoremod(CoreModMethodTransformer.java:18) ~[coremods-4.0.6.jar:?]
	at net.minecraftforge.coremod.transformer.CoreModMethodTransformer.runCoremod(CoreModMethodTransformer.java:10) ~[coremods-4.0.6.jar:?]
	at net.minecraftforge.coremod.transformer.CoreModBaseTransformer.transform(CoreModBaseTransformer.java:38) [coremods-4.0.6.jar:?]
	at cpw.mods.modlauncher.TransformerHolder.transform(TransformerHolder.java:41) [modlauncher-8.1.3.jar:?]
	at cpw.mods.modlauncher.ClassTransformer.performVote(ClassTransformer.java:179) [modlauncher-8.1.3.jar:?]
	at cpw.mods.modlauncher.ClassTransformer.transform(ClassTransformer.java:111) [modlauncher-8.1.3.jar:?]
	at cpw.mods.modlauncher.TransformingClassLoader$DelegatedClassLoader.findClass(TransformingClassLoader.java:265) [modlauncher-8.1.3.jar:?]
	at cpw.mods.modlauncher.TransformingClassLoader.buildTransformedClassNodeFor(TransformingClassLoader.java:142) [modlauncher-8.1.3.jar:?]
	at cpw.mods.modlauncher.LaunchPluginHandler.lambda$null$8(LaunchPluginHandler.java:97) [modlauncher-8.1.3.jar:?]
	at cpw.mods.modlauncher.LaunchPluginHandler$$Lambda$473/934142486.buildTransformedClassNodeFor(Unknown Source) [modlauncher-8.1.3.jar:?]
	at org.spongepowered.asm.launch.MixinLaunchPluginLegacy.getClassNode(MixinLaunchPluginLegacy.java:222) [mixin-0.8.4.jar:0.8.4+Jenkins-b308.git-2accda5000f7602229606b39437565542cc6fba4]
	at org.spongepowered.asm.launch.MixinLaunchPluginLegacy.getClassNode(MixinLaunchPluginLegacy.java:207) [mixin-0.8.4.jar:0.8.4+Jenkins-b308.git-2accda5000f7602229606b39437565542cc6fba4]
	at org.spongepowered.asm.mixin.transformer.ClassInfo.forName(ClassInfo.java:2005) [mixin-0.8.4.jar:0.8.4+Jenkins-b308.git-2accda5000f7602229606b39437565542cc6fba4]
	at org.spongepowered.asm.mixin.transformer.MixinInfo.getTargetClass(MixinInfo.java:1017) [mixin-0.8.4.jar:0.8.4+Jenkins-b308.git-2accda5000f7602229606b39437565542cc6fba4]
	at org.spongepowered.asm.mixin.transformer.MixinInfo.readTargetClasses(MixinInfo.java:1007) [mixin-0.8.4.jar:0.8.4+Jenkins-b308.git-2accda5000f7602229606b39437565542cc6fba4]
	at org.spongepowered.asm.mixin.transformer.MixinInfo.parseTargets(MixinInfo.java:895) [mixin-0.8.4.jar:0.8.4+Jenkins-b308.git-2accda5000f7602229606b39437565542cc6fba4]
	at org.spongepowered.asm.mixin.transformer.MixinConfig.prepareMixins(MixinConfig.java:867) [mixin-0.8.4.jar:0.8.4+Jenkins-b308.git-2accda5000f7602229606b39437565542cc6fba4]
	at org.spongepowered.asm.mixin.transformer.MixinConfig.prepare(MixinConfig.java:779) [mixin-0.8.4.jar:0.8.4+Jenkins-b308.git-2accda5000f7602229606b39437565542cc6fba4]
	at org.spongepowered.asm.mixin.transformer.MixinProcessor.prepareConfigs(MixinProcessor.java:539) [mixin-0.8.4.jar:0.8.4+Jenkins-b308.git-2accda5000f7602229606b39437565542cc6fba4]
	at org.spongepowered.asm.mixin.transformer.MixinProcessor.select(MixinProcessor.java:462) [mixin-0.8.4.jar:0.8.4+Jenkins-b308.git-2accda5000f7602229606b39437565542cc6fba4]
	at org.spongepowered.asm.mixin.transformer.MixinProcessor.checkSelect(MixinProcessor.java:438) [mixin-0.8.4.jar:0.8.4+Jenkins-b308.git-2accda5000f7602229606b39437565542cc6fba4]
	at org.spongepowered.asm.mixin.transformer.MixinProcessor.applyMixins(MixinProcessor.java:290) [mixin-0.8.4.jar:0.8.4+Jenkins-b308.git-2accda5000f7602229606b39437565542cc6fba4]
	at org.spongepowered.asm.mixin.transformer.MixinTransformer.transformClass(MixinTransformer.java:250) [mixin-0.8.4.jar:0.8.4+Jenkins-b308.git-2accda5000f7602229606b39437565542cc6fba4]
	at org.spongepowered.asm.service.modlauncher.MixinTransformationHandler.processClass(MixinTransformationHandler.java:131) [mixin-0.8.4.jar:0.8.4+Jenkins-b308.git-2accda5000f7602229606b39437565542cc6fba4]
	at org.spongepowered.asm.launch.MixinLaunchPluginLegacy.processClass(MixinLaunchPluginLegacy.java:131) [mixin-0.8.4.jar:0.8.4+Jenkins-b308.git-2accda5000f7602229606b39437565542cc6fba4]
	at cpw.mods.modlauncher.serviceapi.ILaunchPluginService.processClassWithFlags(ILaunchPluginService.java:154) [modlauncher-8.1.3.jar:8.1.3+8.1.3+main-8.1.x.c94d18ec]
	at cpw.mods.modlauncher.LaunchPluginHandler.offerClassNodeToPlugins(LaunchPluginHandler.java:85) [modlauncher-8.1.3.jar:?]
	at cpw.mods.modlauncher.ClassTransformer.transform(ClassTransformer.java:120) [modlauncher-8.1.3.jar:?]
	at cpw.mods.modlauncher.TransformingClassLoader$DelegatedClassLoader.findClass(TransformingClassLoader.java:265) [modlauncher-8.1.3.jar:?]
	at cpw.mods.modlauncher.TransformingClassLoader.loadClass(TransformingClassLoader.java:136) [modlauncher-8.1.3.jar:?]
	at cpw.mods.modlauncher.TransformingClassLoader.loadClass(TransformingClassLoader.java:98) [modlauncher-8.1.3.jar:?]
	at java.lang.ClassLoader.loadClass(ClassLoader.java:357) [?:1.8.0_51]
	at java.lang.Class.forName0(Native Method) ~[?:1.8.0_51]
	at java.lang.Class.forName(Class.java:348) [?:1.8.0_51]
	at net.minecraftforge.fml.loading.FMLClientLaunchProvider.lambda$launchService$0(FMLClientLaunchProvider.java:51) [forge-1.16.5-36.2.26.jar:36.2]
	at net.minecraftforge.fml.loading.FMLClientLaunchProvider$$Lambda$508/2139936252.call(Unknown Source) [forge-1.16.5-36.2.26.jar:36.2]
	at cpw.mods.modlauncher.LaunchServiceHandlerDecorator.launch(LaunchServiceHandlerDecorator.java:37) [modlauncher-8.1.3.jar:?]
	at cpw.mods.modlauncher.LaunchServiceHandler.launch(LaunchServiceHandler.java:54) [modlauncher-8.1.3.jar:?]
	at cpw.mods.modlauncher.LaunchServiceHandler.launch(LaunchServiceHandler.java:72) [modlauncher-8.1.3.jar:?]
	at cpw.mods.modlauncher.Launcher.run(Launcher.java:82) [modlauncher-8.1.3.jar:?]
	at cpw.mods.modlauncher.Launcher.main(Launcher.java:66) [modlauncher-8.1.3.jar:?]
[18:34:35] [main/INFO]: Patching ItemStack#onItemUse
[18:34:35] [main/INFO]: Adding 'add_missing_tag_enchantment_tooltip' ASM patch...
[18:34:35] [main/INFO]: Added 'add_missing_tag_enchantment_tooltip' ASM patch!
[18:34:35] [main/INFO]: Adding 'add_enchantment_tooltip' ASM patch...
[18:34:35] [main/INFO]: Added 'add_enchantment_tooltip' ASM patch!
[18:34:35] [main/WARN]: Error loading class: de/maxhenkel/gravestone/events/DeathEvents (java.lang.ClassNotFoundException: null)
[18:34:35] [main/WARN]: Error loading class: de/maxhenkel/corpse/events/DeathEvents (java.lang.ClassNotFoundException: null)
[18:34:35] [main/INFO]: Patching AnvilScreen#drawGuiContainerForegroundLayer
[18:34:35] [main/INFO]: Patching net/minecraft/loot/functions/EnchantRandomly
[18:34:35] [main/INFO]: Adding 'reach_set_client_renderer' ASM patch...
[18:34:35] [main/INFO]: Added 'reach_set_client_renderer' ASM patch!
[18:34:35] [main/INFO]: Adding 'on_block_change' ASM patch...
[18:34:35] [main/INFO]: Added 'on_block_change' ASM patch!
[18:34:35] [main/INFO]: Adding 'sun_brightness_server' ASM patch...
[18:34:35] [main/INFO]: Added 'sun_brightness_server' ASM patch!
[18:34:35] [main/INFO]: Adding 'sun_brightness_client' ASM patch...
[18:34:35] [main/INFO]: Added 'sun_brightness_client' ASM patch!
[18:34:35] [main/INFO]: Adding 'on_block_change' ASM patch...
[18:34:35] [main/INFO]: Added 'on_block_change' ASM patch!
[18:34:35] [main/INFO]: Adding 'sun_brightness_server' ASM patch...
[18:34:35] [main/INFO]: Added 'sun_brightness_server' ASM patch!
[18:34:36] [main/INFO]: Adding 'render_particles' ASM patch...
[18:34:36] [main/INFO]: Added 'render_particles' ASM patch!
[18:34:36] [main/INFO]: Patching Item#getItemEnchantability
[18:34:36] [main/INFO]: Patching RepairContainer#updateRepairOutput
[18:34:36] [main/INFO]: Successfully removed the anvil level cap.
[18:34:36] [main/INFO]: Patching RepairContainer#updateRepairOutput
[18:34:36] [main/INFO]: Successfully allowed nbt-unbreakable items in the anvil.
[18:34:36] [main/INFO]: Patching net/minecraft/inventory/container/RepairContainer
[18:34:36] [main/INFO]: Adding 'add_enchantment_helper_levels' ASM patch...
[18:34:36] [main/INFO]: Added 'add_enchantment_helper_levels' ASM patch!
[18:34:36] [main/INFO]: Adding 'add_enchantment_helper_enchantments' ASM patch...
[18:34:36] [main/INFO]: Added 'add_enchantment_helper_enchantments' ASM patch!
[18:34:36] [main/INFO]: Adding 'add_enchantment_helper_apply_modifier' ASM patch...
[18:34:36] [main/INFO]: Added 'add_enchantment_helper_apply_modifier' ASM patch!
[18:34:36] [main/INFO]: Patching EnchantmentHelper#getEnchantmentModifierDamage
[18:34:36] [main/INFO]: Patching EnchantmentHelper#getModifierForCreature
[18:34:36] [main/INFO]: Patching EnchantmentHelper#applyThornEnchantments
[18:34:36] [main/INFO]: Patching EnchantmentHelper#applyArthropodEnchantments
[18:34:36] [main/INFO]: Patching buildEnchantmentList for the Enchantability affix.
[18:34:36] [main/INFO]: Patching EnchantmentHelper#getEnchantmentDatas
[18:34:36] [main/INFO]: Patching DataPackRegistries#<init>
[18:34:36] [main/INFO]: Patching LootTableManager#apply
[18:34:36] [main/INFO]: Patching TemptGoal#isTempting
[18:34:37] [main/INFO]: !!! SOME LOGGERS HAVE MOVED TO THE DEBUG FILE (Please Include them in your bug reports) !!!
[18:34:37] [main/INFO]: Adding 'add_custom_entity_collision' ASM patch...
[18:34:37] [main/INFO]: Added 'add_custom_entity_collision' ASM patch!
[18:34:37] [main/INFO]: Adding 'on_block_change' ASM patch...
[18:34:37] [main/INFO]: Added 'on_block_change' ASM patch!
[18:34:37] [main/INFO]: Adding 'sun_brightness_server' ASM patch...
[18:34:37] [main/INFO]: Added 'sun_brightness_server' ASM patch!
[18:34:38] [main/INFO]: Patching BlockModelShapes#getModelLocation
[18:34:38] [main/INFO]: Adding 'set_player_field' ASM patch...
[18:34:38] [main/INFO]: Added 'set_player_field' ASM patch!
[18:34:38] [main/INFO]: Patching LivingEntity#attackEntityFrom
[18:34:38] [main/INFO]: Patching LivingEntity#blockUsingShield
[18:34:38] [main/INFO]: Patching LivingEntity#applyPotionDamageCalculations
[18:34:38] [main/INFO]: Adding 'water_movement_slowdown_prevention' ASM patch...
[18:34:38] [main/INFO]: Added 'water_movement_slowdown_prevention' ASM patch!
[18:34:38] [main/ERROR]: Error occurred applying transform of coremod META-INF/asm/multipart.js function render
java.lang.NullPointerException: null
	at org.objectweb.asm.tree.InsnList.insert(InsnList.java:343) ~[asm-tree-9.1.jar:9.1]
	at jdk.nashorn.internal.scripts.Script$Recompilation$185$5956A$\^eval\_.initializeCoreMod$transformer-3(<eval>:135) ~[?:?]
	at jdk.nashorn.internal.runtime.ScriptFunctionData.invoke(ScriptFunctionData.java:638) ~[nashorn.jar:?]
	at jdk.nashorn.internal.runtime.ScriptFunction.invoke(ScriptFunction.java:229) ~[nashorn.jar:?]
	at jdk.nashorn.internal.runtime.ScriptRuntime.apply(ScriptRuntime.java:387) ~[nashorn.jar:?]
	at jdk.nashorn.api.scripting.ScriptObjectMirror.call(ScriptObjectMirror.java:110) ~[nashorn.jar:?]
	at net.minecraftforge.coremod.NashornFactory.lambda$getFunction$0(NashornFactory.java:18) ~[coremods-4.0.6.jar:4.0.6+14+master.c21a551]
	at net.minecraftforge.coremod.NashornFactory$$Lambda$444/190838539.apply(Unknown Source) ~[?:?]
	at net.minecraftforge.coremod.transformer.CoreModMethodTransformer.runCoremod(CoreModMethodTransformer.java:18) ~[coremods-4.0.6.jar:?]
	at net.minecraftforge.coremod.transformer.CoreModMethodTransformer.runCoremod(CoreModMethodTransformer.java:10) ~[coremods-4.0.6.jar:?]
	at net.minecraftforge.coremod.transformer.CoreModBaseTransformer.transform(CoreModBaseTransformer.java:38) [coremods-4.0.6.jar:?]
	at cpw.mods.modlauncher.TransformerHolder.transform(TransformerHolder.java:41) [modlauncher-8.1.3.jar:?]
	at cpw.mods.modlauncher.ClassTransformer.performVote(ClassTransformer.java:179) [modlauncher-8.1.3.jar:?]
	at cpw.mods.modlauncher.ClassTransformer.transform(ClassTransformer.java:111) [modlauncher-8.1.3.jar:?]
	at cpw.mods.modlauncher.TransformingClassLoader$DelegatedClassLoader.findClass(TransformingClassLoader.java:265) [modlauncher-8.1.3.jar:?]
	at cpw.mods.modlauncher.TransformingClassLoader.loadClass(TransformingClassLoader.java:136) [modlauncher-8.1.3.jar:?]
	at cpw.mods.modlauncher.TransformingClassLoader.loadClass(TransformingClassLoader.java:98) [modlauncher-8.1.3.jar:?]
	at java.lang.ClassLoader.loadClass(ClassLoader.java:357) [?:1.8.0_51]
	at net.optifine.reflect.Reflector.<clinit>(Reflector.java:307) [?:?]
	at net.minecraft.crash.CrashReport.func_71504_g(CrashReport.java:101) [?:?]
	at net.minecraft.crash.CrashReport.<init>(CrashReport.java:54) [?:?]
	at net.minecraft.crash.CrashReport.func_230188_h_(CrashReport.java:425) [?:?]
	at net.minecraft.client.main.Main.main(Main.java:122) [?:?]
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method) ~[?:1.8.0_51]
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62) ~[?:1.8.0_51]
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43) ~[?:1.8.0_51]
	at java.lang.reflect.Method.invoke(Method.java:497) ~[?:1.8.0_51]
	at net.minecraftforge.fml.loading.FMLClientLaunchProvider.lambda$launchService$0(FMLClientLaunchProvider.java:51) [forge-1.16.5-36.2.26.jar:36.2]
	at net.minecraftforge.fml.loading.FMLClientLaunchProvider$$Lambda$508/2139936252.call(Unknown Source) [forge-1.16.5-36.2.26.jar:36.2]
	at cpw.mods.modlauncher.LaunchServiceHandlerDecorator.launch(LaunchServiceHandlerDecorator.java:37) [modlauncher-8.1.3.jar:?]
	at cpw.mods.modlauncher.LaunchServiceHandler.launch(LaunchServiceHandler.java:54) [modlauncher-8.1.3.jar:?]
	at cpw.mods.modlauncher.LaunchServiceHandler.launch(LaunchServiceHandler.java:72) [modlauncher-8.1.3.jar:?]
	at cpw.mods.modlauncher.Launcher.run(Launcher.java:82) [modlauncher-8.1.3.jar:?]
	at cpw.mods.modlauncher.Launcher.main(Launcher.java:66) [modlauncher-8.1.3.jar:?]
[18:34:38] [main/WARN]: @ModifyConstant conflict. Skipping assets/botania/botania.mixins.json:MixinWorldRenderer->@ModifyConstant::makeSunBigger(F)F with priority 1000, already redirected by mythicbotany.mixins.json:MixinWorldRenderer->@ModifyConstant::makeSunBigger(F)F with priority 1000
[18:34:38] [main/WARN]: @ModifyConstant conflict. Skipping assets/botania/botania.mixins.json:MixinWorldRenderer->@ModifyConstant::makeMoonBigger(F)F with priority 1000, already redirected by mythicbotany.mixins.json:MixinWorldRenderer->@ModifyConstant::makeMoonBigger(F)F with priority 1000
[18:34:38] [main/INFO]: Patching ItemStack#onItemUse
[18:34:38] [main/INFO]: Adding 'add_missing_tag_enchantment_tooltip' ASM patch...
[18:34:38] [main/INFO]: Added 'add_missing_tag_enchantment_tooltip' ASM patch!
[18:34:38] [main/INFO]: Adding 'add_enchantment_tooltip' ASM patch...
[18:34:38] [main/INFO]: Added 'add_enchantment_tooltip' ASM patch!
[18:34:38] [main/WARN]: @Redirect conflict. Skipping expandability.mixins.json:swimming.client.LocalPlayerMixin->@Redirect::setUnderWater(Lnet/minecraft/client/entity/player/ClientPlayerEntity;)Z with priority 1000, already redirected by randompatches.mixins.json:client.keybindings.ClientPlayerEntityMixin->@Redirect::isSubmergedInWater(Lnet/minecraft/client/entity/player/ClientPlayerEntity;)Z with priority 1000
[18:34:38] [main/INFO]: Adding 'sun_brightness_client' ASM patch...
[18:34:38] [main/INFO]: Added 'sun_brightness_client' ASM patch!
[18:34:39] [main/INFO]: Adding 'render_particles' ASM patch...
[18:34:39] [main/INFO]: Added 'render_particles' ASM patch!
[18:34:39] [main/INFO]: Adding 'reach_set_client_renderer' ASM patch...
[18:34:39] [main/INFO]: Added 'reach_set_client_renderer' ASM patch!
[18:34:39] [main/INFO]: Patching BlockModelShapes#getModelLocation
[18:34:39] [pool-3-thread-1/INFO]: Patching Item#getItemEnchantability
[18:34:40] [pool-3-thread-1/INFO]: Using Java 8 class definer
[18:34:40] [pool-3-thread-1/INFO]: Patching SharedMonsterAttributes#readAttributeModifier
[18:34:41] [pool-3-thread-1/INFO]: Patching RepairContainer#updateRepairOutput
[18:34:41] [pool-3-thread-1/INFO]: Successfully removed the anvil level cap.
[18:34:41] [pool-3-thread-1/INFO]: Patching RepairContainer#updateRepairOutput
[18:34:41] [pool-3-thread-1/INFO]: Successfully allowed nbt-unbreakable items in the anvil.
[18:34:41] [pool-3-thread-1/INFO]: Patching net/minecraft/inventory/container/RepairContainer
[18:34:41] [pool-3-thread-1/INFO]: Patching CampfireTileEntity#findMatchingRecipe
[18:34:42] [pool-3-thread-1/INFO]: Patching TemptGoal#isTempting
[18:34:43] [pool-3-thread-1/INFO]: Patching ItemArrow#isInfinite
[18:34:43] [pool-3-thread-1/INFO]: Patching net/minecraft/item/EnchantedBookItem
[18:34:43] [pool-3-thread-1/INFO]: Patching ItemArrow#isInfinite
[18:34:43] [pool-3-thread-1/INFO]: Patching CrossbowItem#onItemRightClick
[18:34:43] [pool-3-thread-1/INFO]: Patching CrossbowItem#fireProjectile
[18:34:43] [pool-3-thread-1/INFO]: Patching FishingBobberEntity#catchingFish
[18:34:43] [pool-3-thread-1/INFO]: Patching net/minecraft/loot/functions/EnchantRandomly
[18:34:44] [main/INFO]: Setting user: Clouddser
[18:34:44] [main/ERROR]: java.io.FileNotFoundException: Source 'C:\Users\Jeremy\curseforge\minecraft\Instances\All the Mods 6 - ATM6 - 1.16.5\config\defaultoptions\servers.dat' does not exist
[18:34:44] [main/INFO]: [OptiFine] (Reflector) Class not present: net.minecraft.launchwrapper.Launch
[18:34:44] [main/INFO]: Backend library: LWJGL version 3.2.2 build 10
[18:34:44] [main/INFO]: [OptiFine] 
[18:34:44] [main/INFO]: [OptiFine] OptiFine_1.16.5_HD_U_G8
[18:34:44] [main/INFO]: [OptiFine] Build: 20210515-161946
[18:34:44] [main/INFO]: [OptiFine] OS: Windows 10 (amd64) version 10.0
[18:34:44] [main/INFO]: [OptiFine] Java: 1.8.0_51, Oracle Corporation
[18:34:44] [main/INFO]: [OptiFine] VM: Java HotSpot(TM) 64-Bit Server VM (mixed mode), Oracle Corporation
[18:34:44] [main/INFO]: [OptiFine] LWJGL: 3.3.0 Win32 WGL EGL OSMesa VisualC DLL
[18:34:44] [main/INFO]: [OptiFine] OpenGL: NVIDIA GeForce RTX 2060/PCIe/SSE2, version 4.6.0 NVIDIA 471.68, NVIDIA Corporation
[18:34:45] [main/INFO]: [OptiFine] OpenGL Version: 4.6.0
[18:34:45] [main/INFO]: [OptiFine] Maximum texture size: 32768x32768
[18:34:45] [VersionCheck/INFO]: [OptiFine] Checking for new version
[18:34:45] [main/INFO]: [Shaders] OpenGL Version: 4.6.0 NVIDIA 471.68
[18:34:45] [main/INFO]: [Shaders] Vendor:  NVIDIA Corporation
[18:34:45] [main/INFO]: [Shaders] Renderer: NVIDIA GeForce RTX 2060/PCIe/SSE2
[18:34:45] [main/INFO]: [Shaders] Capabilities:  2.0  2.1  3.0  3.2  4.0 
[18:34:45] [main/INFO]: [Shaders] GL_MAX_DRAW_BUFFERS: 8
[18:34:45] [main/INFO]: [Shaders] GL_MAX_COLOR_ATTACHMENTS_EXT: 8
[18:34:45] [main/INFO]: [Shaders] GL_MAX_TEXTURE_IMAGE_UNITS: 32
[18:34:45] [main/INFO]: [Shaders] Load shaders configuration.
[18:34:45] [main/INFO]: [Shaders] Loaded shaderpack: §r§lAstra§4§lLex§r§l_(§4§lBSL§r§l_Edit)_By_LexBoosT_§4§lV37.0§r§l (1).zip
[18:34:45] [main/INFO]: [OptiFine] [Shaders] Worlds: -1, 1
[18:34:45] [VersionCheck/INFO]: [OptiFine] Version found: G7
[18:34:52] [main/INFO]: [OptiFine] (Reflector) Class not present: net.minecraftforge.fml.common.Loader
[18:34:52] [main/INFO]: [OptiFine] [Shaders] Parsing block mappings: /shaders/block.properties
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: minecraft:azalea_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: minecraft:flowering_azalea_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: minecraft:azalea
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: minecraft:flowering_azalea
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: minecraft:big_dripleaf
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: minecraft:big_dripleaf_stem
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: minecraft:small_dripleaf
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: minecraft:cave_vines_plant
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: minecraft:cave_vines
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: minecraft:spore_blossom
[18:34:52] [main/WARN]: [OptiFine] [Shaders] Invalid block ID mapping: block.10112=minecraft:spore_blossom
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: minecraft:flowing_lava
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: minecraft:glow_lichen
[18:34:52] [main/WARN]: [OptiFine] [Shaders] Invalid block ID mapping: block.10255=minecraft:glow_lichen
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: minecraft:cave_vines_plant
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: minecraft:cave_vines
[18:34:52] [main/WARN]: [OptiFine] [Shaders] Invalid block ID mapping: block.10256=minecraft:cave_vines_plant:berries=true minecraft:cave_vines:berries=true
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: minecraft:candle
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: minecraft:white_candle
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: minecraft:orange_candle
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: minecraft:magenta_candle
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: minecraft:light_blue_candle
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: minecraft:yellow_candle
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: minecraft:lime_candle
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: minecraft:pink_candle
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: minecraft:gray_candle
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: minecraft:light_gray_candle
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: minecraft:cyan_candle
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: minecraft:purple_candle
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: minecraft:blue_candle
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: minecraft:brown_candle
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: minecraft:green_candle
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: minecraft:red_candle
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: minecraft:black_candle
[18:34:52] [main/WARN]: [OptiFine] [Shaders] Invalid block ID mapping: block.10257=minecraft:candle:lit=true minecraft:white_candle:lit=true minecraft:orange_candle:lit=true minecraft:magenta_candle:lit=true minecraft:light_blue_candle:lit=true minecraft:yellow_candle:lit=true minecraft:lime_candle:lit=true minecraft:pink_candle:lit=true minecraft:gray_candle:lit=true minecraft:light_gray_candle:lit=true minecraft:cyan_candle:lit=true minecraft:purple_candle:lit=true minecraft:blue_candle:lit=true minecraft:brown_candle:lit=true minecraft:green_candle:lit=true minecraft:red_candle:lit=true minecraft:black_candle:lit=true
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: minecraft:sculk_sensor
[18:34:52] [main/WARN]: [OptiFine] [Shaders] Invalid block ID mapping: block.10258=minecraft:sculk_sensor
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: minecraft:small_amethyst_bud
[18:34:52] [main/WARN]: [OptiFine] [Shaders] Invalid block ID mapping: block.10260=minecraft:small_amethyst_bud
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: minecraft:medium_amethyst_bud
[18:34:52] [main/WARN]: [OptiFine] [Shaders] Invalid block ID mapping: block.10261=minecraft:medium_amethyst_bud
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: minecraft:large_amethyst_bud
[18:34:52] [main/WARN]: [OptiFine] [Shaders] Invalid block ID mapping: block.10262=minecraft:large_amethyst_bud
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: minecraft:amethyst_cluster
[18:34:52] [main/WARN]: [OptiFine] [Shaders] Invalid block ID mapping: block.10263=minecraft:amethyst_cluster
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: minecraft:flowing_water
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: minecraft:stained_glass
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: minecraft:stained_glass_pane
[18:34:52] [main/WARN]: [OptiFine] [Shaders] Invalid block ID mapping: block.10301=minecraft:stained_glass minecraft:stained_glass_pane
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: minecraft:tinted_glass
[18:34:52] [main/WARN]: [OptiFine] [Shaders] Invalid block ID mapping: block.10304=minecraft:tinted_glass
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: biomesoplenty:dune_grass
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: biomesoplenty:dead_grass
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: biomesoplenty:desert_grass
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: biomesoplenty:sprout
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: biomesoplenty:bush
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: biomesoplenty:rose
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: biomesoplenty:violet
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: biomesoplenty:lavender
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: biomesoplenty:wildflower
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: biomesoplenty:orange_cosmos
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: biomesoplenty:pink_daffodil
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: biomesoplenty:pink_hibiscus
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: biomesoplenty:glowflower
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: biomesoplenty:wilted_lily
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: biomesoplenty:burning_blossom
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: biomesoplenty:origin_sapling
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: biomesoplenty:flowering_oak_sapling
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: biomesoplenty:rainbow_birch_sapling
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: biomesoplenty:yellow_autumn_sapling
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: biomesoplenty:orange_autumn_sapling
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: biomesoplenty:maple_sapling
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: biomesoplenty:fir_sapling
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: biomesoplenty:redwood_sapling
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: biomesoplenty:white_cherry_sapling
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: biomesoplenty:pink_cherry_sapling
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: biomesoplenty:mahogany_sapling
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: biomesoplenty:jacaranda_sapling
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: biomesoplenty:palm_sapling
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: biomesoplenty:willow_sapling
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: biomesoplenty:dead_sapling
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: biomesoplenty:magic_sapling
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: biomesoplenty:umbran_sapling
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: biomesoplenty:hellbark_sapling
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:white_mystical_flower
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:gray_mystical_flower
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:orange_mystical_flower
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:magenta_mystical_flower
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:light_blue_mystical_flower
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:light_gray_mystical_flower
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:yellow_mystical_flower
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:lime_mystical_flower
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:pink_mystical_flower
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:cyan_mystical_flower
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:purple_mystical_flower
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:blue_mystical_flower
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:brown_mystical_flower
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:green_mystical_flower
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:red_mystical_flower
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:black_mystical_flower
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:white_mushroom
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:orange_mushroom
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:magenta_mushroom
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:light_blue_mushroom
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:yellow_mushroom
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:lime_mushroom
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:pink_mushroom
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:gray_mushroom
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:light_gray_mushroom
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:cyan_mushroom
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:purple_mushroom
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:blue_mushroom
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:brown_mushroom
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:green_mushroom
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:red_mushroom
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:black_mushroom
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:hydroangeas
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:manastar
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:pure_daisy
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:endoflame
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:thermalily
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:rosa_arcana
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:munchdew
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:entropinnyum
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:kekimurus
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:gourmaryllisbotania
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:spectrolus
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:dandelifeon
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:rafflowsia
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:shulk_me_not
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:bellethorn
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:bellethorn_chibi
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:bergamute
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:dreadthorn
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:heisei_dream
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:tigerseye
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:jaded_amaranthus
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:orechid
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:fallen_kanade
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:exoflame
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:agricarnation
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:agricarnation_chibi
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:hopperhock
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:hopperhock_chibi
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:tangleberrie
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:jiyuulia
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:rannuncarpus
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:rannuncarpus_chibi
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:hyacidus
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:pollidisiac
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:clayconia
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:clayconia_chibi
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:loonium
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:daffomill
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:vinculotus
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:spectranthemum
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:medumone
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:marimorphosis
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:marimorphosis_chibi
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:bubbell
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:bubbell_chibi
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:solegnolia
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:solegnolia_chibibotania
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: atmospheric:rosewood_sapling
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: atmospheric:morado_sapling
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: atmospheric:yucca_sapling
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: atmospheric:kousa_sapling
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: atmospheric:aspen_sapling
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: atmospheric:grimwood_sapling
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: atmospheric:warm_monkey_brush
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: atmospheric:hot_monkey_brush
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: atmospheric:scalding_monkey_brush
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: atmospheric:yucca_flower
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: atmospheric:gilia
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: autumnity:red_maple_sapling
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: autumnity:orange_maple_sapling
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: autumnity:yellow_maple_sapling
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: autumnity:maple_sapling
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: autumnity:autumn_crocus
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: earthmobsmod:buttercup
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: desolation:scorched_tuft
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: astralsorcery:glow_flower
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: environmental:mycelium_sprouts
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: environmental:willow_sapling
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: environmental:cherry_sapling
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: environmental:pink_wisteria_sapling
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: environmental:blue_wisteria_sapling
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: environmental:purple_wisteria_sapling
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: environmental:white_wisteria_sapling
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: environmental:cattail
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: environmental:cartwheel
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: environmental:bluebell
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: environmental:violet
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: environmental:dianthus
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: environmental:red_lotus_flower
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: environmental:white_lotus_flower
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: environmental:yellow_hibiscus
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: environmental:orange_hibiscus
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: environmental:red_hibiscus
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: environmental:pink_hibiscus
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: environmental:magenta_hibiscus
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: environmental:purple_hibiscus
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: farmersdelight:wild_cabbages
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: farmersdelight:wild_onions
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: farmersdelight:wild_tomatoes
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: farmersdelight:wild_carrots
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: farmersdelight:wild_potatoes
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: farmersdelight:wild_beetroots
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: neapolitan:small_banana_frond
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: neapolitan:banana_frond
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: neapolitan:large_banana_frond
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: neapolitan:strawberry_pips
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: upgrade_aquatic:blue_pickerelweed
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: upgrade_aquatic:purple_pickerelweed
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: upgrade_aquatic:river_sapling
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: upgrade_aquatic:beachgrass
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: upgrade_aquatic:white_searocket
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: upgrade_aquatic:pink_searocket
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: byg:beach_grass
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: byg:cattail
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: byg:clover_patch
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: byg:flower_patch
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: byg:horseweed
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: byg:leaf_pile
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: byg:prairie_grass
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: byg:reeds
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: byg:short_beach_grass
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: byg:short_grass
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: byg:tall_prairie_grass
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: byg:weed_grass
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: byg:wilted_grass
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: byg:winter_grass
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: ecotones:clover
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: ecotones:reeds
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: ecotones:sandy_grass
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: ecotones:short_grass
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: terrestria:cattail
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: terrestria:dead_grass
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: terrestria:sakura_leaf_pile
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: terrestria:tall_cattail
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: terrestria:tiny_cactus
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: wildworld:acacia_leaf_pile
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: wildworld:birch_leaf_pile
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: wildworld:dark_oak_leaf_pile
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: wildworld:jungle_leaf_pile
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: wildworld:oak_leaf_pile
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: wildworld:spruce_leaf_pile
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: buzzier_bees:buttercup
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: buzzier_bees:white_clover
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: buzzier_bees:pink_clover
[18:34:52] [main/WARN]: [OptiFine] [Shaders] Invalid block ID mapping: block.10701=biomesoplenty:dune_grass biomesoplenty:dead_grass biomesoplenty:desert_grass biomesoplenty:sprout biomesoplenty:bush biomesoplenty:rose biomesoplenty:violet biomesoplenty:lavender biomesoplenty:wildflower biomesoplenty:orange_cosmos biomesoplenty:pink_daffodil biomesoplenty:pink_hibiscus biomesoplenty:glowflower biomesoplenty:wilted_lily biomesoplenty:burning_blossom biomesoplenty:origin_sapling biomesoplenty:flowering_oak_sapling biomesoplenty:rainbow_birch_sapling biomesoplenty:yellow_autumn_sapling biomesoplenty:orange_autumn_sapling biomesoplenty:maple_sapling biomesoplenty:fir_sapling biomesoplenty:redwood_sapling biomesoplenty:white_cherry_sapling biomesoplenty:pink_cherry_sapling biomesoplenty:mahogany_sapling biomesoplenty:jacaranda_sapling biomesoplenty:palm_sapling biomesoplenty:willow_sapling biomesoplenty:dead_sapling biomesoplenty:magic_sapling biomesoplenty:umbran_sapling biomesoplenty:hellbark_sapling botania:white_mystical_flower botania:gray_mystical_flower botania:orange_mystical_flower botania:magenta_mystical_flower botania:light_blue_mystical_flower botania:light_gray_mystical_flower botania:yellow_mystical_flower botania:lime_mystical_flower botania:pink_mystical_flower botania:cyan_mystical_flower botania:purple_mystical_flower botania:blue_mystical_flower botania:brown_mystical_flower botania:green_mystical_flower botania:red_mystical_flower botania:black_mystical_flower botania:white_mushroom botania:orange_mushroom botania:magenta_mushroom botania:light_blue_mushroom botania:yellow_mushroom botania:lime_mushroom botania:pink_mushroom botania:gray_mushroom botania:light_gray_mushroom botania:cyan_mushroom botania:purple_mushroom botania:blue_mushroom botania:brown_mushroom botania:green_mushroom botania:red_mushroom botania:black_mushroom botania:hydroangeas botania:manastar botania:pure_daisy botania:endoflame botania:thermalily botania:rosa_arcana botania:munchdew botania:entropinnyum botania:kekimurus botania:gourmaryllisbotania:narslimmus botania:spectrolus botania:dandelifeon botania:rafflowsia botania:shulk_me_not botania:bellethorn botania:bellethorn_chibi botania:bergamute botania:dreadthorn botania:heisei_dream botania:tigerseye botania:jaded_amaranthus botania:orechid botania:fallen_kanade botania:exoflame botania:agricarnation botania:agricarnation_chibi botania:hopperhock botania:hopperhock_chibi botania:tangleberrie botania:jiyuulia botania:rannuncarpus botania:rannuncarpus_chibi botania:hyacidus botania:pollidisiac botania:clayconia botania:clayconia_chibi botania:loonium botania:daffomill botania:vinculotus botania:spectranthemum botania:medumone botania:marimorphosis botania:marimorphosis_chibi botania:bubbell botania:bubbell_chibi botania:solegnolia botania:solegnolia_chibibotania:orechid_ignem atmospheric:rosewood_sapling atmospheric:morado_sapling atmospheric:yucca_sapling atmospheric:kousa_sapling atmospheric:aspen_sapling atmospheric:grimwood_sapling atmospheric:warm_monkey_brush atmospheric:hot_monkey_brush atmospheric:scalding_monkey_brush atmospheric:yucca_flower atmospheric:gilia autumnity:red_maple_sapling autumnity:orange_maple_sapling autumnity:yellow_maple_sapling autumnity:maple_sapling autumnity:autumn_crocus earthmobsmod:buttercup desolation:scorched_tuft astralsorcery:glow_flower environmental:mycelium_sprouts environmental:willow_sapling environmental:cherry_sapling environmental:pink_wisteria_sapling environmental:blue_wisteria_sapling environmental:purple_wisteria_sapling environmental:white_wisteria_sapling environmental:cattail environmental:cartwheel environmental:bluebell environmental:violet environmental:dianthus environmental:red_lotus_flower environmental:white_lotus_flower environmental:yellow_hibiscus environmental:orange_hibiscus environmental:red_hibiscus environmental:pink_hibiscus environmental:magenta_hibiscus environmental:purple_hibiscus farmersdelight:wild_cabbages farmersdelight:wild_onions farmersdelight:wild_tomatoes farmersdelight:wild_carrots farmersdelight:wild_potatoes farmersdelight:wild_beetroots neapolitan:small_banana_frond neapolitan:banana_frond neapolitan:large_banana_frond neapolitan:strawberry_pips upgrade_aquatic:blue_pickerelweed upgrade_aquatic:purple_pickerelweed upgrade_aquatic:river_sapling upgrade_aquatic:beachgrass upgrade_aquatic:white_searocket upgrade_aquatic:pink_searocket byg:beach_grass byg:cattail byg:clover_patch byg:flower_patch byg:horseweed byg:leaf_pile byg:prairie_grass byg:reeds byg:short_beach_grass byg:short_grass byg:tall_prairie_grass byg:weed_grass byg:wilted_grass byg:winter_grass ecotones:clover ecotones:reeds ecotones:sandy_grass ecotones:short_grass terrestria:cattail terrestria:dead_grass terrestria:sakura_leaf_pile terrestria:tall_cattail terrestria:tiny_cactus wildworld:acacia_leaf_pile wildworld:birch_leaf_pile wildworld:dark_oak_leaf_pile wildworld:jungle_leaf_pile wildworld:oak_leaf_pile wildworld:spruce_leaf_pile buzzier_bees:buttercup buzzier_bees:white_clover buzzier_bees:pink_clover
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: atmospheric:water_hyacinth
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: atmospheric:tall_yucca_flower
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: environmental:tall_cattail
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: environmental:pink_delphinium
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: environmental:blue_delphinium
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: environmental:purple_delphinium
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: environmental:white_delphinium
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: environmental:bird_of_paradise
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: environmental:giant_tall_grass
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: farmersdelight:wild_rice
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: upgrade_aquatic:flowering_rush
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: upgrade_aquatic:tall_beachgrass
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: upgrade_aquatic:tall_blue_pickerelweed
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: upgrade_aquatic:tall_purple_pickerelweed
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: biomesoplenty:barley
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: biomesoplenty:goldenrod
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: biomesoplenty:blue_hydrangea
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: biomesoplenty:watergrass
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: biomesoplenty:reed
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: biomesoplenty:cattail
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:white_double_flower
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:orange_double_flower
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:magenta_double_flower
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:light_blue_double_flower
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:yellow_double_flower
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:lime_double_flower
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:pink_double_flower
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:gray_double_flower
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:light_gray_double_flower
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:cyan_double_flower
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:purple_double_flower
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:blue_double_flower
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:brown_double_flower
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:green_double_flower
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:red_double_flower
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:black_double_flower
[18:34:52] [main/WARN]: [OptiFine] [Shaders] Invalid block ID mapping: block.10702=atmospheric:water_hyacinth:half=lower atmospheric:tall_yucca_flower:half=lower environmental:tall_cattail:half=lower environmental:pink_delphinium:half=lower environmental:blue_delphinium:half=lower environmental:purple_delphinium:half=lower environmental:white_delphinium:half=lower environmental:bird_of_paradise:half=lower environmental:giant_tall_grass:half=lower farmersdelight:wild_rice:half=lower upgrade_aquatic:flowering_rush:half=lower upgrade_aquatic:tall_beachgrass:half=lower upgrade_aquatic:tall_blue_pickerelweed:half=lower upgrade_aquatic:tall_purple_pickerelweed:half=lower biomesoplenty:barley:half=lower biomesoplenty:goldenrod:half=lower biomesoplenty:blue_hydrangea:half=lower biomesoplenty:watergrass:half=lower biomesoplenty:reed:half=lower biomesoplenty:cattail:half=lower botania:white_double_flower:half=lower botania:orange_double_flower:half=lower botania:magenta_double_flower:half=lower botania:light_blue_double_flower:half=lower botania:yellow_double_flower:half=lower botania:lime_double_flower:half=lower botania:pink_double_flower:half=lower botania:gray_double_flower:half=lower botania:light_gray_double_flower:half=lower botania:cyan_double_flower:half=lower botania:purple_double_flower:half=lower botania:blue_double_flower:half=lower botania:brown_double_flower:half=upper botania:green_double_flower:half=upper botania:red_double_flower:half=upper botania:black_double_flower:half=lower
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: atmospheric:water_hyacinth
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: atmospheric:tall_yucca_flower
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: environmental:tall_cattail
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: environmental:pink_delphinium
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: environmental:blue_delphinium
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: environmental:purple_delphinium
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: environmental:white_delphinium
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: environmental:bird_of_paradise
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: environmental:giant_tall_grass
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: farmersdelight:wild_rice
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: upgrade_aquatic:flowering_rush
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: upgrade_aquatic:tall_beachgrass
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: upgrade_aquatic:tall_blue_pickerelweed
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: upgrade_aquatic:tall_purple_pickerelweed
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: biomesoplenty:barley
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: biomesoplenty:goldenrod
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: biomesoplenty:blue_hydrangea
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: biomesoplenty:watergrass
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: biomesoplenty:reed
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: biomesoplenty:cattail
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:white_double_flower
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:orange_double_flower
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:magenta_double_flower
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:light_blue_double_flower
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:yellow_double_flower
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:lime_double_flower
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:pink_double_flower
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:gray_double_flower
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:light_gray_double_flower
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:cyan_double_flower
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:purple_double_flower
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:blue_double_flower
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:brown_double_flower
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:green_double_flower
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:red_double_flower
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: botania:black_double_flower
[18:34:52] [main/WARN]: [OptiFine] [Shaders] Invalid block ID mapping: block.10703=atmospheric:water_hyacinth:half=upper atmospheric:tall_yucca_flower:half=upper environmental:tall_cattail:half=upper environmental:pink_delphinium:half=upper environmental:blue_delphinium:half=upper environmental:purple_delphinium:half=upper environmental:white_delphinium:half=upper environmental:bird_of_paradise:half=upper environmental:giant_tall_grass:half=upper farmersdelight:wild_rice:half=upper upgrade_aquatic:flowering_rush:half=upper upgrade_aquatic:tall_beachgrass:half=upper upgrade_aquatic:tall_blue_pickerelweed:half=upper upgrade_aquatic:tall_purple_pickerelweed:half=upper biomesoplenty:barley:half=upper biomesoplenty:goldenrod:half=upper biomesoplenty:blue_hydrangea:half=upper biomesoplenty:watergrass:half=upper biomesoplenty:reed:half=upper biomesoplenty:cattail:half=upper botania:white_double_flower:half=upper botania:orange_double_flower:half=upper botania:magenta_double_flower:half=upper botania:light_blue_double_flower:half=upper botania:yellow_double_flower:half=upper botania:lime_double_flower:half=upper botania:pink_double_flower:half=upper botania:gray_double_flower:half=upper botania:light_gray_double_flower:half=upper botania:cyan_double_flower:half=upper botania:purple_double_flower:half=upper botania:blue_double_flower:half=upper botania:brown_double_flower:half=upper botania:green_double_flower:half=upper botania:red_double_flower:half=upper botania:black_double_flower:half=upper
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: dynamictrees:oak_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: dynamictrees:birch_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: dynamictrees:spruce_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: dynamictrees:jungle_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: dynamictrees:acacia_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: dynamictrees:dark_oak_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: desolation:ash_bramble
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: desolation:charred_branches
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: quark:blue_blossom_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: quark:lavender_blossom_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: quark:orange_blossom_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: quark:pink_blossom_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: quark:yellow_blossom_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: biomesoplenty:origin_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: biomesoplenty:flowering_oak_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: biomesoplenty:rainbow_birch_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: biomesoplenty:yellow_autumn_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: biomesoplenty:orange_autumn_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: biomesoplenty:maple_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: biomesoplenty:fir_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: biomesoplenty:redwood_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: biomesoplenty:mahogany_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: biomesoplenty:palm_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: biomesoplenty:willow_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: biomesoplenty:dead_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: biomesoplenty:magic_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: biomesoplenty:umbran_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: biomesoplenty:hellbark_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: biomesoplenty:pink_cherry_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: biomesoplenty:white_cherry_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: biomesoplenty:jacaranda_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: atmospheric:rosewood_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: atmospheric:morado_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: atmospheric:flowering_morado_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: atmospheric:yucca_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: atmospheric:kousa_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: atmospheric:aspen_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: atmospheric:grimwood_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: autumnity:red_maple_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: autumnity:orange_maple_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: autumnity:yellow_maple_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: autumnity:maple_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: environmental:willow_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: environmental:cherry_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: environmental:pink_wisteria_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: environmental:blue_wisteria_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: environmental:purple_wisteria_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: environmental:white_wisteria_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: environmental:pink_hanging_wisteria_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: environmental:blue_hanging_wisteria_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: environmental:purple_hanging_wisteria_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: environmental:white_hanging_wisteria_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: environmental:hanging_willow_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: upgrade_aquatic:river_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: byg:aspen_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: byg:araucaria_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: byg:baobab_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: byg:blooming_witch_hazel_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: byg:blue_enchanted_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: byg:blue_spruce_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: byg:brown_birch_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: byg:brown_oak_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: byg:brown_zelkova_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: byg:cika_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: byg:cypress_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: byg:ebony_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: byg:fir_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: byg:flowering_orchard_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: byg:flowering_nightshade_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: byg:flowering_palo_verde_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: byg:green_apple_skyris_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: byg:green_enchanted_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: byg:holly_berry_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: byg:holly_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: byg:indigo_jacaranda_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: byg:jacaranda_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: byg:joshua_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: byg:mahogany_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: byg:mangrove_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: byg:maple_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: byg:orange_birch_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: byg:orange_oak_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: byg:orange_spruce_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: byg:orchard_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: byg:palo_verde_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: byg:pine_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: byg:pink_cherry_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: byg:rainbow_eucalyptus_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: byg:red_birch_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: byg:red_maple_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: byg:red_oak_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: byg:red_spruce_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: byg:redwood_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: byg:ripe_joshua_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: byg:ripe_orchard_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: byg:silver_maple_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: byg:skyris_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: byg:white_cherry_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: byg:willow_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: byg:witch_hazel_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: byg:yellow_birch_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: byg:yellow_spruce_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: byg:zelkova_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: ecotones:hazel_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: sakurarosea:alt_sakura_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: sakurarosea:sakura_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: sakurarosea:white_sakura_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: terrestria:cypress_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: terrestria:dark_japanese_maple_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: terrestria:hemlock_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: terrestria:japanese_maple_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: terrestria:japanese_maple_shrub_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: terrestria:jungle_palm_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: terrestria:rainbow_eucalyptus_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: terrestria:redwood_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: terrestria:rubber_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: terrestria:sakura_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: terrestria:willow_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: terrestria:yucca_palm_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: traverse:brown_autumnal_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: traverse:fir_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: traverse:orange_autumnal_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: traverse:red_autumnal_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: traverse:yellow_autumnal_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: vanillaenhanced:redwood_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: wild_explorer:autumn_oak_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: wild_explorer:autumn_birch_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: wild_explorer:pink_cherry_oak_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: wild_explorer:white_cherry_oak_leaves
[18:34:52] [main/WARN]: [OptiFine] Shaders: Block not found for name: wild_explorer:palm_leaves
[18:34:52] [main/WARN]: [OptiFine] [Shaders] Invalid block ID mapping: block.10704=dynamictrees:oak_leaves dynamictrees:birch_leaves dynamictrees:spruce_leaves dynamictrees:jungle_leaves dynamictrees:acacia_leaves dynamictrees:dark_oak_leaves desolation:ash_bramble desolation:charred_branches quark:blue_blossom_leaves quark:lavender_blossom_leaves quark:orange_blossom_leaves quark:pink_blossom_leaves quark:yellow_blossom_leaves biomesoplenty:origin_leaves biomesoplenty:flowering_oak_leaves biomesoplenty:rainbow_birch_leaves biomesoplenty:yellow_autumn_leaves biomesoplenty:orange_autumn_leaves biomesoplenty:maple_leaves biomesoplenty:fir_leaves biomesoplenty:redwood_leaves biomesoplenty:mahogany_leaves biomesoplenty:palm_leaves biomesoplenty:willow_leaves biomesoplenty:dead_leaves biomesoplenty:magic_leaves biomesoplenty:umbran_leaves biomesoplenty:hellbark_leaves biomesoplenty:pink_cherry_leaves biomesoplenty:white_cherry_leaves biomesoplenty:jacaranda_leaves atmospheric:rosewood_leaves atmospheric:morado_leaves atmospheric:flowering_morado_leaves atmospheric:yucca_leaves atmospheric:kousa_leaves atmospheric:aspen_leaves atmospheric:grimwood_leaves autumnity:red_maple_leaves autumnity:orange_maple_leaves autumnity:yellow_maple_leaves autumnity:maple_leaves environmental:willow_leaves environmental:cherry_leaves environmental:pink_wisteria_leaves environmental:blue_wisteria_leaves environmental:purple_wisteria_leaves environmental:white_wisteria_leaves environmental:pink_hanging_wisteria_leaves environmental:blue_hanging_wisteria_leaves environmental:purple_hanging_wisteria_leaves environmental:white_hanging_wisteria_leaves environmental:hanging_willow_leaves upgrade_aquatic:river_leaves byg:aspen_leaves byg:araucaria_leaves byg:baobab_leaves byg:blooming_witch_hazel_leaves byg:blue_enchanted_leaves byg:blue_spruce_leaves byg:brown_birch_leaves byg:brown_oak_leaves byg:brown_zelkova_leaves byg:cika_leaves byg:cypress_leaves byg:ebony_leaves byg:fir_leaves byg:flowering_orchard_leaves byg:flowering_nightshade_leaves byg:flowering_palo_verde_leaves byg:green_apple_skyris_leaves byg:green_enchanted_leaves byg:holly_berry_leaves byg:holly_leaves byg:indigo_jacaranda_leaves byg:jacaranda_leaves byg:joshua_leaves byg:mahogany_leaves byg:mangrove_leaves byg:maple_leaves byg:orange_birch_leaves byg:orange_oak_leaves byg:orange_spruce_leaves byg:orchard_leaves byg:palo_verde_leaves byg:pine_leaves byg:pink_cherry_leaves byg:rainbow_eucalyptus_leaves byg:red_birch_leaves byg:red_maple_leaves byg:red_oak_leaves byg:red_spruce_leaves byg:redwood_leaves byg:ripe_joshua_leaves byg:ripe_orchard_leaves byg:silver_maple_leaves byg:skyris_leaves byg:white_cherry_leaves byg:willow_leaves byg:witch_hazel_leaves byg:yellow_birch_leaves byg:yellow_spruce_leaves byg:zelkova_leaves ecotones:hazel_leaves sakurarosea:alt_sakura_leaves sakurarosea:sakura_leaves sakurarosea:white_sakura_leaves terrestria:cypress_leaves terrestria:dark_japanese_maple_leaves terrestria:hemlock_leaves terrestria:japanese_maple_leaves terrestria:japanese_maple_shrub_leaves terrestria:jungle_palm_leaves terrestria:rainbow_eucalyptus_leaves terrestria:redwood_leaves terrestria:rubber_leaves terrestria:sakura_leaves terrestria:willow_leaves terrestria:yucca_palm_leaves traverse:brown_autumnal_leaves traverse:fir_leaves traverse:orange_autumnal_leaves traverse:red_autumnal_leaves traverse:yellow_autumnal_leaves vanillaenhanced:redwood_leaves wild_explorer:autumn_oak_leaves wild_explorer:autumn_birch_leaves wild_explorer:pink_cherry_oak_leaves wild_explorer:white_cherry_oak_leaves wild_explorer:palm_leaves
[18:34:52] [main/INFO]: [OptiFine] [Shaders] Parsing item mappings: /shaders/item.properties
[18:34:52] [main/INFO]: [OptiFine] [Shaders] Parsing entity mappings: /shaders/entity.properties
[18:34:52] [main/WARN]: [OptiFine] Shaders: Entity not found: minecraft:glow_item_frame
[18:34:52] [main/WARN]: [OptiFine] Shaders: Entity not found: minecraft:glow_squid
[18:34:52] [main/WARN]: [OptiFine] Shaders: Entity not found: minecraft:goat
[18:34:52] [main/WARN]: [OptiFine] Shaders: Entity not found: minecraft:glow_squid
[18:34:52] [main/WARN]: [OptiFine] [Shaders] Invalid entity ID mapping: entity.18213=minecraft:glow_squid
[18:34:52] [main/INFO]: [Shaders] Custom texture: texture.gbuffers.colortex10 = tex/planet.png
[18:34:52] [main/INFO]: [Shaders] Custom texture: texture.gbuffers.colortex11 = tex/nebula.png
[18:34:52] [main/INFO]: [Shaders] Custom texture: texture.gbuffers.colortex12 = tex/galaxy.png
[18:34:52] [main/INFO]: [Shaders] Custom texture: texture.composite.depthtex2 = tex/dirt.png
[18:34:52] [main/INFO]: [Shaders] Custom variable: blindFactorSqrt
[18:34:52] [main/INFO]: [Shaders] Custom uniform: blindFactor
[18:34:52] [main/INFO]: [Shaders] Custom variable: yCold1
[18:34:52] [main/INFO]: [Shaders] Custom variable: yCold2
[18:34:52] [main/INFO]: [Shaders] Custom variable: yCold3
[18:34:52] [main/INFO]: [Shaders] Custom uniform: isCold
[18:34:52] [main/INFO]: [Shaders] Custom uniform: isDesert
[18:34:52] [main/INFO]: [Shaders] Custom uniform: isMesa
[18:34:52] [main/INFO]: [Shaders] Custom uniform: isSwamp
[18:34:52] [main/INFO]: [Shaders] Custom uniform: isMushroom
[18:34:52] [main/INFO]: [Shaders] Custom uniform: isSavanna
[18:34:52] [main/INFO]: [Shaders] Custom uniform: isValley
[18:34:52] [main/INFO]: [Shaders] Custom uniform: isCrimson
[18:34:52] [main/INFO]: [Shaders] Custom uniform: isWarped
[18:34:52] [main/INFO]: [Shaders] Custom uniform: isBasalt
[18:34:52] [main/INFO]: [Shaders] Custom variable: biomeHasRain
[18:34:52] [main/INFO]: [Shaders] Custom uniform: biomeHasRainSmooth
[18:34:52] [main/INFO]: [Shaders] Custom uniform: biomeisNotColdSmooth
[18:34:52] [main/INFO]: [Shaders] Custom uniform: biomeHasHeatSmooth
[18:34:52] [main/INFO]: [Shaders] Custom uniform: biomeHasHeatSmooth2
[18:34:52] [main/INFO]: [Shaders] Custom uniform: biomeHasHeatSmooth3
[18:34:52] [main/INFO]: [Shaders] Custom uniform: touchmybody
[18:34:52] [main/INFO]: [Shaders] Custom uniform: rainStrengthS
[18:34:52] [main/INFO]: [Shaders] Custom uniform: rainStrengthShiningStars
[18:34:52] [main/INFO]: [Shaders] Custom uniform: rainStrengthS2
[18:34:52] [main/INFO]: [Shaders] Custom uniform: rainStrengthS3
[18:34:52] [main/INFO]: [Shaders] Custom uniform: framemod8
[18:34:52] [main/INFO]: [Shaders] Custom variable: dx
[18:34:52] [main/INFO]: [Shaders] Custom variable: dy
[18:34:52] [main/INFO]: [Shaders] Custom variable: dz
[18:34:52] [main/INFO]: [Shaders] Custom variable: rawSpeed
[18:34:52] [main/INFO]: [Shaders] Custom variable: smoothSpeed
[18:34:52] [main/INFO]: [Shaders] Custom uniform: effectStrength
[18:34:52] [main/INFO]: [Shaders] Custom uniform: velocity
[18:34:52] [main/INFO]: [OptiFine] (Reflector) Field not present: net.minecraftforge.client.model.pipeline.LightUtil.itemConsumer
[18:34:52] [main/INFO]: [OptiFine] (Reflector) Field not present: net.minecraftforge.client.model.pipeline.LightUtil.tessellator
[18:34:52] [main/INFO]: Loaded client.properties
[18:34:55] [main/INFO]: Scanning classes for titanium
[18:34:55] [main/INFO]: Found FeaturePluginInstance for class IndustrialForegoingResourcePlugin for plugin resources
[18:34:55] [main/INFO]: Found FeaturePluginInstance for class DefaultResourceRegistryPlugin for plugin resources
[18:34:55] [modloading-worker-7/INFO]: Patching ModelBakery#<init>
[18:34:55] [modloading-worker-6/INFO]: Loading config: C:\Users\Jeremy\curseforge\minecraft\Instances\All the Mods 6 - ATM6 - 1.16.5\config\universalgrid-common.toml
[18:34:55] [modloading-worker-6/INFO]: Built config: C:\Users\Jeremy\curseforge\minecraft\Instances\All the Mods 6 - ATM6 - 1.16.5\config\universalgrid-common.toml
[18:34:55] [modloading-worker-6/INFO]: Loaded config: C:\Users\Jeremy\curseforge\minecraft\Instances\All the Mods 6 - ATM6 - 1.16.5\config\universalgrid-common.toml
[18:34:55] [modloading-worker-11/INFO]: Patching DataPackRegistries#<init>
[18:34:55] [modloading-worker-8/INFO]: Registered charge handler for type org.zeith.hammerlib.util.charging.fluid.FluidCharge - org.zeith.hammerlib.util.charging.impl.FluidChargeHandler@55428885
[18:34:55] [modloading-worker-8/INFO]: Registered charge handler for type org.zeith.hammerlib.util.charging.fe.FECharge - org.zeith.hammerlib.util.charging.impl.FEChargeHandler@654a68f
[18:34:55] [modloading-worker-2/INFO]: Adding 'cooldown_tracker_set' ASM patch...
[18:34:55] [modloading-worker-8/INFO]: Registered inventory lister org.zeith.hammerlib.util.charging.impl.VanillaPlayerInvLister
[18:34:55] [modloading-worker-9/INFO]: Registering mod: novillagerdm
[18:34:55] [modloading-worker-2/INFO]: Added 'cooldown_tracker_set' ASM patch!
[18:34:55] [modloading-worker-2/INFO]: Adding 'reach_set_server_entity_interact' ASM patch...
[18:34:55] [modloading-worker-2/INFO]: Added 'reach_set_server_entity_interact' ASM patch!
[18:34:55] [modloading-worker-2/INFO]: Adding 'allow_entity_interaction' ASM patch...
[18:34:55] [modloading-worker-2/INFO]: Added 'allow_entity_interaction' ASM patch!
[18:34:55] [modloading-worker-0/INFO]: Loading config: C:\Users\Jeremy\curseforge\minecraft\Instances\All the Mods 6 - ATM6 - 1.16.5\config\cabletiers-common.toml
[18:34:55] [modloading-worker-0/INFO]: Built config: C:\Users\Jeremy\curseforge\minecraft\Instances\All the Mods 6 - ATM6 - 1.16.5\config\cabletiers-common.toml
[18:34:55] [modloading-worker-9/INFO]: Scanning classes for industrialforegoing
[18:34:55] [modloading-worker-9/INFO]: Found FeaturePluginInstance for class ImmersiveEngineeringPlugin for plugin immersiveengineering
[18:34:55] [modloading-worker-9/INFO]: Found FeaturePluginInstance for class FTBChunksPlugin for plugin ftbchunks
[18:34:55] [modloading-worker-9/INFO]: Found FeaturePluginInstance for class AstralSorceryPlugin for plugin astralsorcery
[18:34:55] [modloading-worker-9/INFO]: Found FeaturePluginInstance for class CuriosPlugin for plugin curios
[18:34:55] [modloading-worker-0/INFO]: Loaded config: C:\Users\Jeremy\curseforge\minecraft\Instances\All the Mods 6 - ATM6 - 1.16.5\config\cabletiers-common.toml
[18:34:55] [modloading-worker-9/INFO]: Constructed class ImmersiveEngineeringPlugin for plugin immersiveengineering for mod industrialforegoing
[18:34:55] [modloading-worker-9/INFO]: Constructed class FTBChunksPlugin for plugin ftbchunks for mod industrialforegoing
[18:34:55] [modloading-worker-9/INFO]: Constructed class AstralSorceryPlugin for plugin astralsorcery for mod industrialforegoing
[18:34:55] [modloading-worker-9/INFO]: Constructed class CuriosPlugin for plugin curios for mod industrialforegoing
[18:34:55] [modloading-worker-9/INFO]: Executing phase CONSTRUCTION for plugin class ImmersiveEngineeringPlugin
[18:34:55] [modloading-worker-9/INFO]: Executing phase CONSTRUCTION for plugin class FTBChunksPlugin
[18:34:55] [modloading-worker-9/INFO]: Executing phase CONSTRUCTION for plugin class AstralSorceryPlugin
[18:34:55] [modloading-worker-9/INFO]: Executing phase CONSTRUCTION for plugin class CuriosPlugin
[18:34:55] [modloading-worker-9/INFO]: Executing phase PRE_INIT for plugin class ImmersiveEngineeringPlugin
[18:34:55] [modloading-worker-9/INFO]: Executing phase PRE_INIT for plugin class FTBChunksPlugin
[18:34:55] [modloading-worker-9/INFO]: Executing phase PRE_INIT for plugin class AstralSorceryPlugin
[18:34:55] [modloading-worker-9/INFO]: Executing phase PRE_INIT for plugin class CuriosPlugin
[18:34:55] [modloading-worker-1/INFO]: Scanning classes for portality
[18:34:55] [modloading-worker-8/INFO]: Injecting setup into class org.zeith.hammerlib.net.Network
[18:34:55] [modloading-worker-8/INFO]: Injecting setup into class org.zeith.hammerlib.core.test.machine.RecipeTestMachine
[18:34:56] [modloading-worker-0/WARN]: You have disabled Iron Furnaces's Update Checker, to re-enable: change the value of Update Checker in .minecraft->config->ironfurnaces-client.toml to 'true'.
[18:34:56] [modloading-worker-3/INFO]: Patching LootTableManager#apply
[18:34:56] [modloading-worker-14/INFO]: Found 3 RS API injection points
[18:34:56] [modloading-worker-14/INFO]: Injected RS API in com.YTrollman.UniversalGrid.UniversalGrid UNIVERSALGRIDAPI
[18:34:56] [modloading-worker-14/INFO]: Injected RS API in org.cyclops.integrateddynamicscompat.modcompat.refinedstorage.aspect.RefinedStorageAspects RS
[18:34:56] [modloading-worker-14/INFO]: Injected RS API in com.refinedmods.refinedstorageaddons.RSAddons RSAPI
[18:34:56] [modloading-worker-14/INFO]: InfuserSetup: register
[18:34:56] [modloading-worker-14/INFO]: SqueezerSetup: register
[18:34:56] [modloading-worker-14/INFO]: OracleSetup: register
[18:34:56] [Phosphophyllite Registry Worker/INFO]: Thread started
[18:34:56] [modloading-worker-3/INFO]: Engineer's Tools GIT id #1afec45.
[18:34:56] [modloading-worker-14/INFO]: FactorySetup: register
[18:34:56] [modloading-worker-14/INFO]: LayoutSetup: register
[18:34:56] [modloading-worker-14/INFO]: AnvilSetup: register
[18:34:56] [modloading-worker-14/INFO]: FluidSetup: register
[18:34:56] [modloading-worker-14/INFO]: ToolsSetup: register
[18:34:56] [modloading-worker-14/INFO]: DebugSetup: register
[18:34:56] [modloading-worker-14/INFO]: GenericSetup: register
[18:34:56] [modloading-worker-14/INFO]: FluidConvertor: register
[18:34:56] [modloading-worker-15/INFO]: 14 blocks registered.
[18:34:56] [modloading-worker-15/INFO]: 29 items registered.
[18:34:56] [modloading-worker-15/INFO]: 13 tiles registered.
[18:34:56] [modloading-worker-15/INFO]: 13 containers registered.
[18:34:56] [modloading-worker-1/INFO]: [yalter.mousetweaks.Logger:Log:6]: [Mouse Tweaks] Main.initialize()
[18:34:56] [modloading-worker-1/INFO]: [yalter.mousetweaks.Logger:Log:6]: [Mouse Tweaks] Reflecting GuiContainer...
[18:34:56] [modloading-worker-1/INFO]: [yalter.mousetweaks.Logger:Log:6]: [Mouse Tweaks] Detected obfuscation: FORGE.
[18:34:56] [modloading-worker-1/INFO]: [yalter.mousetweaks.Logger:Log:6]: [Mouse Tweaks] Success.
[18:34:56] [modloading-worker-1/INFO]: [yalter.mousetweaks.Logger:Log:6]: [Mouse Tweaks] Initialized.
[18:34:56] [modloading-worker-11/INFO]: Mod usefulrailroads is signed with a valid certificate.
[18:34:56] [modloading-worker-0/INFO]: Loading config: C:\Users\Jeremy\curseforge\minecraft\Instances\All the Mods 6 - ATM6 - 1.16.5\config\creativeapiary-common.toml
[18:34:56] [modloading-worker-0/INFO]: Built config: C:\Users\Jeremy\curseforge\minecraft\Instances\All the Mods 6 - ATM6 - 1.16.5\config\creativeapiary-common.toml
[18:34:56] [modloading-worker-0/INFO]: Loaded config: C:\Users\Jeremy\curseforge\minecraft\Instances\All the Mods 6 - ATM6 - 1.16.5\config\creativeapiary-common.toml
[18:34:56] [modloading-worker-1/INFO]: Optifine detected.
[18:34:56] [modloading-worker-14/INFO]: Loading config: C:\Users\Jeremy\curseforge\minecraft\Instances\All the Mods 6 - ATM6 - 1.16.5\config\creativecrafter-client.toml
[18:34:56] [modloading-worker-14/INFO]: Built config: C:\Users\Jeremy\curseforge\minecraft\Instances\All the Mods 6 - ATM6 - 1.16.5\config\creativecrafter-client.toml
[18:34:56] [modloading-worker-14/INFO]: Loaded config: C:\Users\Jeremy\curseforge\minecraft\Instances\All the Mods 6 - ATM6 - 1.16.5\config\creativecrafter-client.toml
[18:34:56] [modloading-worker-11/INFO]: AdvancedPeripherals says hello!
[18:34:56] [modloading-worker-10/INFO]: Items registered.
[18:34:56] [modloading-worker-10/INFO]: Blocks registered.
[18:34:56] [modloading-worker-10/INFO]: Global loot modifiers registered.
[18:34:56] [modloading-worker-9/INFO]: Executing phase INIT for plugin class ImmersiveEngineeringPlugin
[18:34:56] [modloading-worker-9/INFO]: Executing phase INIT for plugin class FTBChunksPlugin
[18:34:56] [modloading-worker-9/INFO]: Executing phase INIT for plugin class AstralSorceryPlugin
[18:34:56] [modloading-worker-9/INFO]: Executing phase INIT for plugin class CuriosPlugin
[18:34:56] [modloading-worker-0/INFO]: Registered condition serializer 'silentgear:not'
[18:34:56] [modloading-worker-0/INFO]: Registered condition serializer 'silentgear:and'
[18:34:56] [modloading-worker-0/INFO]: Registered condition serializer 'silentgear:or'
[18:34:56] [modloading-worker-0/INFO]: Registered condition serializer 'silentgear:gear_type'
[18:34:56] [modloading-worker-0/INFO]: Registered condition serializer 'silentgear:material_count'
[18:34:56] [modloading-worker-0/INFO]: Registered condition serializer 'silentgear:material_ratio'
[18:34:56] [modloading-worker-0/INFO]: Registered condition serializer 'silentgear:primary_material'
[18:34:56] [modloading-worker-0/INFO]: Registered serializer 'silentgear:simple_trait'
[18:34:56] [modloading-worker-0/INFO]: Registered serializer 'silentgear:damage_type_trait'
[18:34:56] [modloading-worker-0/INFO]: Registered serializer 'silentgear:durability_trait'
[18:34:56] [modloading-worker-0/INFO]: Registered serializer 'silentgear:enchantment_trait'
[18:34:56] [modloading-worker-0/INFO]: Registered serializer 'silentgear:nbt_trait'
[18:34:56] [modloading-worker-0/INFO]: Registered serializer 'silentgear:potion_effect_trait'
[18:34:56] [modloading-worker-11/INFO]: Gauges and Switches GIT id #900a6ee.
[18:34:56] [modloading-worker-0/INFO]: Registered serializer 'silentgear:stat_modifier_trait'
[18:34:56] [modloading-worker-0/INFO]: Registered serializer 'silentgear:attribute_trait'
[18:34:56] [modloading-worker-0/INFO]: Registered serializer 'silentgear:block_placer'
[18:34:56] [modloading-worker-0/INFO]: Registered serializer 'silentgear:block_filler'
[18:34:56] [modloading-worker-0/INFO]: Registered serializer 'silentgear:synergy'
[18:34:56] [modloading-worker-0/INFO]: Registered serializer 'silentgear:target_effect'
[18:34:56] [modloading-worker-0/INFO]: Registered serializer 'silentgear:bonus_drops'
[18:34:56] [modloading-worker-0/INFO]: Registered serializer 'silentgear:cancel_effects'
[18:34:56] [modloading-worker-0/INFO]: Registered serializer 'silentgear:self_repair'
[18:34:56] [modloading-worker-0/INFO]: Registered serializer 'silentgear:stellar'
[18:34:56] [modloading-worker-0/INFO]: Registered serializer 'managear:mana'
[18:34:56] [modloading-worker-0/INFO]: Registered serializer 'managear:manaburst'
[18:34:57] [modloading-worker-9/INFO]: Executing phase POST_INIT for plugin class ImmersiveEngineeringPlugin
[18:34:57] [modloading-worker-9/INFO]: Executing phase POST_INIT for plugin class FTBChunksPlugin
[18:34:57] [modloading-worker-9/INFO]: Executing phase POST_INIT for plugin class AstralSorceryPlugin
[18:34:57] [modloading-worker-9/INFO]: Executing phase POST_INIT for plugin class CuriosPlugin
[18:34:57] [modloading-worker-6/INFO]: Patching AnvilScreen#drawGuiContainerForegroundLayer
[18:34:57] [modloading-worker-11/INFO]: Mod uteamcore is signed with a valid certificate.
[18:34:57] [modloading-worker-14/INFO]: Adding 'add_enchantment_condition' ASM patch...
[18:34:57] [modloading-worker-14/INFO]: Added 'add_enchantment_condition' ASM patch!
[18:34:57] [modloading-worker-11/INFO]: Forge mod loading, version 36.2.26, for MC 1.16.5 with MCP 20210115.111550
[18:34:57] [modloading-worker-11/INFO]: MinecraftForge v36.2.26 Initialized
[18:34:57] [modloading-worker-10/INFO]: Environment: dev=false, stable=true, vanilla=false
[18:34:57] [modloading-worker-10/INFO]: Signature:  7b:73:d0:a2:c3:40:13:84:35:4f:c9:0e:2b:85:8c:08:ea:3c:3c:eb:f1:98:8b:5b:6e:ca:8a:a0:9a:cf:12:b3
[18:34:57] [modloading-worker-10/INFO]: Trust Data: CN=TerraForged self-signed
[18:34:57] [modloading-worker-10/INFO]: Initializing tags
[18:34:57] [modloading-worker-13/INFO]: Vanilla is real good, but chocolate is better, let's be honest. :)
[18:34:57] [modloading-worker-13/INFO]: Setting up config paths...
[18:34:57] [modloading-worker-4/INFO]: Mod usefulbackpacks is signed with a valid certificate.
[18:34:57] [modloading-worker-7/INFO]: Added Draconic Evolution compatibility to Solar Flux.
[18:34:57] [modloading-worker-9/INFO]: Optifine GUI option was successfully replaced.
[18:34:57] [modloading-worker-13/INFO]: Bee Registry Initialized...
[18:34:57] [modloading-worker-13/INFO]: Trait Registry Initialized...
[18:34:57] [modloading-worker-13/INFO]: Bee Registration Enabled...
[18:34:57] [modloading-worker-13/INFO]: Building Biome Dictionary...
[18:34:58] [modloading-worker-3/INFO]: Thirdparty integration activated for [theoneprobe,cofh_core,immersiveengineering,computercraft,jei,botania,mekanism,curios,patchouli,create,appliedenergistics2]
[18:34:58] [modloading-worker-5/WARN]: WARNING: block Block{minecraft:gold_ore} added to BlockSelector exceeds max probabiltiy of 1!
[18:34:58] [modloading-worker-13/INFO]: Registering Custom Bees...
[18:34:58] [modloading-worker-15/WARN]: Replacing net.minecraftforge.server.permission.DefaultPermissionHandler with dev.ftb.mods.ftbranks.forge.PermissionAPIWrapper
[18:34:58] [modloading-worker-13/INFO]: Registering Custom Honeys..
[18:34:58] [modloading-worker-5/INFO]: Registering class observable.net.BetterChannel$PartialPacketBegin
[18:34:58] [modloading-worker-11/INFO]: Adding 'add_player_field' ASM patch...
[18:34:58] [modloading-worker-11/INFO]: Added 'add_player_field' ASM patch!
[18:34:58] [modloading-worker-7/INFO]: Detected new forge version, registering events reflectively.
[18:34:58] [modloading-worker-10/INFO]: Loaded compatibility for mod immersiveengineering.
[18:34:58] [modloading-worker-1/INFO]: Adding 'post_process_vanilla' ASM patch...
[18:34:58] [modloading-worker-1/INFO]: Added 'post_process_vanilla' ASM patch!
[18:34:58] [modloading-worker-11/INFO]: Here we go! Launching Dungeon Crawl 2.3.5...
[18:34:58] [modloading-worker-2/INFO]: Detected new forge version, registering events reflectively.
[18:34:58] [modloading-worker-1/INFO]: Looking for KubeJS plugins...
[18:34:59] [modloading-worker-1/INFO]: Found kubejs plugin
[18:34:59] [modloading-worker-11/INFO]: Knock Knock...
[18:34:59] [modloading-worker-11/WARN]: Reactor detonation initiated.
[18:34:59] [modloading-worker-11/INFO]: Wait... NO! What?
[18:34:59] [modloading-worker-11/INFO]: Stop That! That's not how this works!
[18:34:59] [modloading-worker-11/WARN]: Calculating explosion ETA
[18:34:59] [modloading-worker-11/INFO]: Ahh... NO... NONONO! DONT DO THAT!!! STOP THIS NOW!
[18:34:59] [modloading-worker-11/WARN]: **Explosion Imminent!!!**
[18:34:59] [modloading-worker-11/INFO]: Well...... fork...
[18:34:59] [modloading-worker-1/INFO]: Found kubejs_thermal plugin
[18:34:59] [modloading-worker-1/INFO]: Found kubejs_create plugin
[18:34:59] [modloading-worker-1/INFO]: Found kubejs_immersive_engineering plugin
[18:34:59] [modloading-worker-1/INFO]: Found kubejs_mekanism plugin
[18:34:59] [modloading-worker-1/INFO]: Found kubejs_blood_magic plugin
[18:34:59] [modloading-worker-1/INFO]: Found ponderjs plugin
[18:34:59] [modloading-worker-1/INFO]: Found ftbchunks plugin
[18:34:59] [modloading-worker-1/INFO]: Done in 0 s
[18:34:59] [modloading-worker-9/INFO]: Scanning classes for titanium
[18:34:59] [modloading-worker-9/INFO]: Constructed class IndustrialForegoingResourcePlugin for plugin resources for mod titanium
[18:34:59] [modloading-worker-9/INFO]: Constructed class DefaultResourceRegistryPlugin for plugin resources for mod titanium
[18:34:59] [modloading-worker-9/INFO]: Executing phase CONSTRUCTION for plugin class IndustrialForegoingResourcePlugin
[18:34:59] [modloading-worker-9/INFO]: Executing phase CONSTRUCTION for plugin class DefaultResourceRegistryPlugin
[18:34:59] [modloading-worker-7/INFO]: M&A -> Config Loaded
[18:34:59] [modloading-worker-1/INFO]: Loaded common.properties
[18:34:59] [modloading-worker-13/INFO]: Loading config: C:\Users\Jeremy\curseforge\minecraft\Instances\All the Mods 6 - ATM6 - 1.16.5\config\ctiers-common.toml
[18:34:59] [modloading-worker-13/INFO]: Built config: C:\Users\Jeremy\curseforge\minecraft\Instances\All the Mods 6 - ATM6 - 1.16.5\config\ctiers-common.toml
[18:34:59] [modloading-worker-13/INFO]: Loaded config: C:\Users\Jeremy\curseforge\minecraft\Instances\All the Mods 6 - ATM6 - 1.16.5\config\ctiers-common.toml
[18:34:59] [modloading-worker-14/INFO]: Registered addon Forge
[18:34:59] [modloading-worker-13/INFO]: Loading config: C:\Users\Jeremy\curseforge\minecraft\Instances\All the Mods 6 - ATM6 - 1.16.5\config\creative_wireless_transmitter-client.toml
[18:34:59] [modloading-worker-13/INFO]: Built config: C:\Users\Jeremy\curseforge\minecraft\Instances\All the Mods 6 - ATM6 - 1.16.5\config\creative_wireless_transmitter-client.toml
[18:34:59] [modloading-worker-13/INFO]: Loaded config: C:\Users\Jeremy\curseforge\minecraft\Instances\All the Mods 6 - ATM6 - 1.16.5\config\creative_wireless_transmitter-client.toml
[18:34:59] [modloading-worker-8/INFO]: Registered plugin: com.blakebr0.mysticalagriculture.lib.ModCorePlugin
[18:34:59] [modloading-worker-8/INFO]: Registered plugin: com.blakebr0.mysticalcustomization.lib.ModCorePlugin
[18:34:59] [modloading-worker-14/INFO]: Registered addon Vanilla
[18:34:59] [modloading-worker-8/INFO]: Registered plugin: com.blakebr0.mysticalagradditions.lib.ModCorePlugin
[18:34:59] [modloading-worker-14/INFO]: Registered addon Storage Drawers
[18:34:59] [modloading-worker-10/INFO]: Registering mod: pylons
[18:34:59] [modloading-worker-14/INFO]: Registered addon Industrialforegoing
[18:34:59] [modloading-worker-6/INFO]: Engineer's Decor GIT id #3dbbf3d.
[18:34:59] [modloading-worker-14/INFO]: Registered addon Thermal_expansion
[18:34:59] [modloading-worker-8/INFO]: Detected new forge version, registering events reflectively.
[18:34:59] [modloading-worker-6/INFO]: ExpandAbility here, who dis?
[18:34:59] [modloading-worker-14/INFO]: Registered addon Bloodmagic
[18:34:59] [modloading-worker-0/INFO]: [wayoftime.bloodmagic.structures.DungeonRoomLoader:loadDungeons:217]: Loading schematic: bloodmagic:t_corridor
[18:34:59] [modloading-worker-0/INFO]: [wayoftime.bloodmagic.structures.DungeonRoomLoader:loadDungeons:219]: Resulting dungeon: wayoftime.bloodmagic.structures.DungeonRoom@70c18fcf
[18:34:59] [modloading-worker-0/INFO]: [wayoftime.bloodmagic.structures.DungeonRoomLoader:loadDungeons:217]: Loading schematic: bloodmagic:four_way_corridor_loot
[18:34:59] [modloading-worker-0/INFO]: [wayoftime.bloodmagic.structures.DungeonRoomLoader:loadDungeons:219]: Resulting dungeon: wayoftime.bloodmagic.structures.DungeonRoom@705ef85a
[18:34:59] [modloading-worker-0/INFO]: [wayoftime.bloodmagic.structures.DungeonRoomLoader:loadDungeons:217]: Loading schematic: bloodmagic:four_way_corridor
[18:34:59] [modloading-worker-0/INFO]: [wayoftime.bloodmagic.structures.DungeonRoomLoader:loadDungeons:219]: Resulting dungeon: wayoftime.bloodmagic.structures.DungeonRoom@dd7cbfb
[18:34:59] [modloading-worker-0/INFO]: [wayoftime.bloodmagic.structures.DungeonRoomLoader:loadDungeons:217]: Loading schematic: bloodmagic:ore_hold_1
[18:34:59] [modloading-worker-0/INFO]: [wayoftime.bloodmagic.structures.DungeonRoomLoader:loadDungeons:219]: Resulting dungeon: wayoftime.bloodmagic.structures.DungeonRoom@4eae0e2
[18:34:59] [modloading-worker-0/INFO]: [wayoftime.bloodmagic.structures.DungeonRoomLoader:loadDungeons:217]: Loading schematic: bloodmagic:straight_corridor
[18:34:59] [modloading-worker-0/INFO]: [wayoftime.bloodmagic.structures.DungeonRoomLoader:loadDungeons:219]: Resulting dungeon: wayoftime.bloodmagic.structures.DungeonRoom@2a8d0ed2
[18:34:59] [modloading-worker-0/INFO]: [wayoftime.bloodmagic.structures.DungeonRoomLoader:loadDungeons:217]: Loading schematic: bloodmagic:spiral_staircase
[18:34:59] [modloading-worker-0/INFO]: [wayoftime.bloodmagic.structures.DungeonRoomLoader:loadDungeons:219]: Resulting dungeon: wayoftime.bloodmagic.structures.DungeonRoom@3245990d
[18:34:59] [modloading-worker-0/INFO]: [wayoftime.bloodmagic.structures.DungeonRoomLoader:loadDungeons:217]: Loading schematic: bloodmagic:t3_entrance
[18:34:59] [modloading-worker-0/INFO]: [wayoftime.bloodmagic.structures.DungeonRoomLoader:loadDungeons:219]: Resulting dungeon: wayoftime.bloodmagic.structures.DungeonRoom@42749d06
[18:34:59] [modloading-worker-14/INFO]: Detected new forge version, registering events reflectively.
[18:34:59] [modloading-worker-0/INFO]: [wayoftime.bloodmagic.structures.DungeonRoomLoader:loadDungeons:217]: Loading schematic: bloodmagic:mini_dungeon/library
[18:34:59] [modloading-worker-0/INFO]: [wayoftime.bloodmagic.structures.DungeonRoomLoader:loadDungeons:219]: Resulting dungeon: wayoftime.bloodmagic.structures.DungeonRoom@de832d4
[18:34:59] [modloading-worker-0/INFO]: [wayoftime.bloodmagic.structures.DungeonRoomLoader:loadDungeons:217]: Loading schematic: bloodmagic:mini_dungeon/armoury
[18:34:59] [modloading-worker-0/INFO]: [wayoftime.bloodmagic.structures.DungeonRoomLoader:loadDungeons:219]: Resulting dungeon: wayoftime.bloodmagic.structures.DungeonRoom@244f21b1
[18:34:59] [modloading-worker-0/INFO]: [wayoftime.bloodmagic.structures.DungeonRoomLoader:loadDungeons:217]: Loading schematic: bloodmagic:mini_dungeon/farm
[18:34:59] [modloading-worker-0/INFO]: [wayoftime.bloodmagic.structures.DungeonRoomLoader:loadDungeons:219]: Resulting dungeon: wayoftime.bloodmagic.structures.DungeonRoom@40e8fd88
[18:34:59] [modloading-worker-0/INFO]: [wayoftime.bloodmagic.structures.DungeonRoomLoader:loadDungeons:217]: Loading schematic: bloodmagic:mini_dungeon/portal_nether
[18:34:59] [modloading-worker-0/INFO]: [wayoftime.bloodmagic.structures.DungeonRoomLoader:loadDungeons:219]: Resulting dungeon: wayoftime.bloodmagic.structures.DungeonRoom@1a515ce7
[18:34:59] [modloading-worker-0/INFO]: [wayoftime.bloodmagic.structures.DungeonRoomLoader:loadDungeons:217]: Loading schematic: bloodmagic:mini_dungeon/crypt
[18:34:59] [modloading-worker-0/INFO]: [wayoftime.bloodmagic.structures.DungeonRoomLoader:loadDungeons:219]: Resulting dungeon: wayoftime.bloodmagic.structures.DungeonRoom@1b836101
[18:34:59] [modloading-worker-0/INFO]: [wayoftime.bloodmagic.structures.DungeonRoomLoader:loadDungeons:223]: # schematics: 12
[18:35:00] [modloading-worker-3/INFO]: Patching vazkii/quark/content/tools/module/AncientTomesModule
[18:35:00] [modloading-worker-3/INFO]: Patching vazkii/quark/content/tools/item/AncientTomeItem
[18:35:01] [modloading-worker-1/INFO]: Loaded script startup_scripts:custom_items.js in 0.169 s
[18:35:01] [modloading-worker-1/INFO]: Loaded script startup_scripts:modification.js in 0.023 s
[18:35:01] [modloading-worker-1/INFO]: Loaded script startup_scripts:worldgen.js in 0.001 s
[18:35:01] [modloading-worker-1/INFO]: Loaded 3/3 KubeJS startup scripts in 1.31 s
[18:35:01] [modloading-worker-7/INFO]: M&A -> Mod Event Bus Handlers Registered
[18:35:01] [modloading-worker-1/INFO]: Loaded script client_scripts:jei_additions.js in 0.001 s
[18:35:01] [modloading-worker-1/INFO]: Loaded script client_scripts:jei_info.js in 0.001 s
[18:35:01] [modloading-worker-1/INFO]: Loaded script client_scripts:jei_removals.js in 0.015 s
[18:35:01] [modloading-worker-1/INFO]: Loaded script client_scripts:ponderjs/atm_shard_creation.js in 0.002 s
[18:35:01] [modloading-worker-1/INFO]: Loaded script client_scripts:ponderjs/creative_cube_creation.js in 0.001 s
[18:35:01] [modloading-worker-1/INFO]: Loaded script client_scripts:tooltips.js in 0.004 s
[18:35:01] [modloading-worker-1/INFO]: Loaded 6/6 KubeJS client scripts in 0.03 s
[18:35:02] [modloading-worker-5/INFO]: Registered class observable.net.BetterChannel$PartialPacketBegin
[18:35:02] [modloading-worker-5/INFO]: Registering class observable.net.BetterChannel$PartialPacketData
[18:35:02] [modloading-worker-5/INFO]: Registered class observable.net.BetterChannel$PartialPacketData
[18:35:02] [modloading-worker-5/INFO]: Registering class observable.net.C2SPacket$InitTPSProfile
[18:35:02] [modloading-worker-5/INFO]: Registered class observable.net.C2SPacket$InitTPSProfile
[18:35:02] [modloading-worker-5/INFO]: Registering class observable.net.C2SPacket$RequestTeleport
[18:35:02] [modloading-worker-5/INFO]: Registered class observable.net.C2SPacket$RequestTeleport
[18:35:02] [modloading-worker-5/INFO]: Registering class observable.net.C2SPacket$RequestAvailability
[18:35:02] [modloading-worker-5/INFO]: Registered class observable.net.C2SPacket$RequestAvailability
[18:35:02] [modloading-worker-5/INFO]: Registering class observable.net.S2CPacket$ProfilingStarted
[18:35:02] [modloading-worker-5/INFO]: Registered class observable.net.S2CPacket$ProfilingStarted
[18:35:02] [modloading-worker-5/INFO]: Registering class observable.net.S2CPacket$ProfilingCompleted
[18:35:02] [modloading-worker-5/INFO]: Registered class observable.net.S2CPacket$ProfilingCompleted
[18:35:02] [modloading-worker-5/INFO]: Registering class observable.net.S2CPacket$ProfilerInactive
[18:35:02] [modloading-worker-5/INFO]: Registered class observable.net.S2CPacket$ProfilerInactive
[18:35:02] [modloading-worker-5/INFO]: Registering class observable.net.S2CPacket$ProfilingResult
[18:35:02] [modloading-worker-5/INFO]: Registered class observable.net.S2CPacket$ProfilingResult
[18:35:02] [modloading-worker-5/INFO]: Registering class observable.net.S2CPacket$Availability
[18:35:02] [modloading-worker-5/INFO]: Registered class observable.net.S2CPacket$Availability
[18:35:02] [main/INFO]: Finished registering registries!
[18:35:03] [main/INFO]: missing extension for "Oh Biome You'll Go" recipes
[18:35:03] [main/INFO]: registerBlocks
[18:35:04] [main/INFO]: Registered 3 blocks.
[18:35:06] [main/INFO]: BYG: Blocks registered!
[18:35:06] [main/INFO]: Registered 94 blocks.
[18:35:06] [main/INFO]: Registered 45 Block entries in 0.31ms.
[18:35:06] [main/INFO]: Registered 34 Block entries in 0.14ms.
[18:35:07] [main/INFO]: HELLO from Register Block
[18:35:09] [main/WARN]: Registry minecraft:block: The object Block{immersivepetroleum:distillationtower} has been registered twice for the same name immersivepetroleum:distillationtower.
[18:35:09] [main/WARN]: Registry minecraft:block: The object Block{immersivepetroleum:pumpjack} has been registered twice for the same name immersivepetroleum:pumpjack.
[18:35:09] [main/WARN]: Registry minecraft:block: The object Block{immersivepetroleum:cokerunit} has been registered twice for the same name immersivepetroleum:cokerunit.
[18:35:09] [main/WARN]: Registry minecraft:block: The object Block{immersivepetroleum:hydrotreater} has been registered twice for the same name immersivepetroleum:hydrotreater.
[18:35:09] [main/INFO]: mysticalcustomization tried to register a duplicate crop with name fluorite, skipping
[18:35:09] [main/INFO]: mysticalcustomization tried to register a duplicate crop with name uraninite, skipping
[18:35:10] [main/INFO]: Immersive Engineering also installed ...
[18:35:10] [main/INFO]: Registered 118 blocks.
[18:35:10] [main/INFO]: registerItems
[18:35:10] [main/INFO]: Registered 17 items.
[18:35:11] [main/INFO]: BYG: Items registered!
[18:35:11] [main/INFO]: Registered 1 items.
[18:35:11] [main/WARN]: Registry minecraft:item: The object debug has been registered twice for the same name citadel:debug.
[18:35:11] [main/WARN]: Registry minecraft:item: The object citadel_book has been registered twice for the same name citadel:citadel_book.
[18:35:11] [main/WARN]: Registry minecraft:item: The object effect_item has been registered twice for the same name citadel:effect_item.
[18:35:11] [main/WARN]: Registry minecraft:item: The object fancy_item has been registered twice for the same name citadel:fancy_item.
[18:35:11] [main/WARN]: Registry minecraft:item: The object air has been registered twice for the same name minecraft:air.
[18:35:11] [main/WARN]: Registry minecraft:item: The object air has been registered twice for the same name minecraft:air.
[18:35:11] [main/WARN]: Registry minecraft:item: The object air has been registered twice for the same name minecraft:air.
[18:35:11] [main/INFO]: Registered 53 Item entries in 0.19ms.
[18:35:11] [main/INFO]: Registered 34 Item entries in 0.11ms.
[18:35:12] [main/INFO]: Loaded book jsons on Thread[Render thread,10,main] in 608 ms
[18:35:14] [main/INFO]: M&A -> Block Items Registered
[18:35:14] [main/INFO]: [wayoftime.bloodmagic.core.AnointmentRegistrar:parseDefinition:126]: Attempting to load Anointment: modjar://bloodmagic/data/bloodmagic/anointment/melee_damage.json, path: /data/bloodmagic/anointment/melee_damage.json
[18:35:14] [main/INFO]: [wayoftime.bloodmagic.core.AnointmentRegistrar:parseDefinition:126]: Attempting to load Anointment: modjar://bloodmagic/data/bloodmagic/anointment/holy_water.json, path: /data/bloodmagic/anointment/holy_water.json
[18:35:14] [main/INFO]: [wayoftime.bloodmagic.core.AnointmentRegistrar:parseDefinition:126]: Attempting to load Anointment: modjar://bloodmagic/data/bloodmagic/anointment/hidden_knowledge.json, path: /data/bloodmagic/anointment/hidden_knowledge.json
[18:35:14] [main/INFO]: [wayoftime.bloodmagic.core.AnointmentRegistrar:parseDefinition:126]: Attempting to load Anointment: modjar://bloodmagic/data/bloodmagic/anointment/quick_draw.json, path: /data/bloodmagic/anointment/quick_draw.json
[18:35:14] [main/INFO]: [wayoftime.bloodmagic.core.AnointmentRegistrar:parseDefinition:126]: Attempting to load Anointment: modjar://bloodmagic/data/bloodmagic/anointment/bow_power.json, path: /data/bloodmagic/anointment/bow_power.json
[18:35:14] [main/INFO]: [wayoftime.bloodmagic.core.AnointmentRegistrar:parseDefinition:126]: Attempting to load Anointment: modjar://bloodmagic/data/bloodmagic/anointment/bow_velocity.json, path: /data/bloodmagic/anointment/bow_velocity.json
[18:35:15] [main/INFO]: [wayoftime.bloodmagic.core.LivingArmorRegistrar:parseDefinition:188]: Attempting to load Living Armour Upgrade: modjar://bloodmagic/data/bloodmagic/living_armor/arrow_protect.json, path: /data/bloodmagic/living_armor/arrow_protect.json
[18:35:15] [main/INFO]: [wayoftime.bloodmagic.core.LivingArmorRegistrar:parseDefinition:188]: Attempting to load Living Armour Upgrade: modjar://bloodmagic/data/bloodmagic/living_armor/fall_protect.json, path: /data/bloodmagic/living_armor/fall_protect.json
[18:35:15] [main/INFO]: [wayoftime.bloodmagic.core.LivingArmorRegistrar:parseDefinition:188]: Attempting to load Living Armour Upgrade: modjar://bloodmagic/data/bloodmagic/living_armor/physical_protect.json, path: /data/bloodmagic/living_armor/physical_protect.json
[18:35:15] [main/INFO]: [wayoftime.bloodmagic.core.LivingArmorRegistrar:parseDefinition:188]: Attempting to load Living Armour Upgrade: modjar://bloodmagic/data/bloodmagic/living_armor/jump.json, path: /data/bloodmagic/living_armor/jump.json
[18:35:15] [main/INFO]: [wayoftime.bloodmagic.core.LivingArmorRegistrar:parseDefinition:188]: Attempting to load Living Armour Upgrade: modjar://bloodmagic/data/bloodmagic/living_armor/health.json, path: /data/bloodmagic/living_armor/health.json
[18:35:15] [main/INFO]: [wayoftime.bloodmagic.core.LivingArmorRegistrar:parseDefinition:188]: Attempting to load Living Armour Upgrade: modjar://bloodmagic/data/bloodmagic/living_armor/experienced.json, path: /data/bloodmagic/living_armor/experienced.json
[18:35:15] [main/INFO]: [wayoftime.bloodmagic.core.LivingArmorRegistrar:parseDefinition:188]: Attempting to load Living Armour Upgrade: modjar://bloodmagic/data/bloodmagic/living_armor/sprint_attack.json, path: /data/bloodmagic/living_armor/sprint_attack.json
[18:35:15] [main/INFO]: [wayoftime.bloodmagic.core.LivingArmorRegistrar:parseDefinition:188]: Attempting to load Living Armour Upgrade: modjar://bloodmagic/data/bloodmagic/living_armor/self_sacrifice.json, path: /data/bloodmagic/living_armor/self_sacrifice.json
[18:35:15] [main/INFO]: [wayoftime.bloodmagic.core.LivingArmorRegistrar:parseDefinition:188]: Attempting to load Living Armour Upgrade: modjar://bloodmagic/data/bloodmagic/living_armor/speed.json, path: /data/bloodmagic/living_armor/speed.json
[18:35:15] [main/INFO]: [wayoftime.bloodmagic.core.LivingArmorRegistrar:parseDefinition:188]: Attempting to load Living Armour Upgrade: modjar://bloodmagic/data/bloodmagic/living_armor/poison_resist.json, path: /data/bloodmagic/living_armor/poison_resist.json
[18:35:15] [main/INFO]: [wayoftime.bloodmagic.core.LivingArmorRegistrar:parseDefinition:188]: Attempting to load Living Armour Upgrade: modjar://bloodmagic/data/bloodmagic/living_armor/fire_resist.json, path: /data/bloodmagic/living_armor/fire_resist.json
[18:35:15] [main/INFO]: [wayoftime.bloodmagic.core.LivingArmorRegistrar:parseDefinition:188]: Attempting to load Living Armour Upgrade: modjar://bloodmagic/data/bloodmagic/living_armor/digging.json, path: /data/bloodmagic/living_armor/digging.json
[18:35:15] [main/INFO]: [wayoftime.bloodmagic.core.LivingArmorRegistrar:parseDefinition:188]: Attempting to load Living Armour Upgrade: modjar://bloodmagic/data/bloodmagic/living_armor/knockback_resist.json, path: /data/bloodmagic/living_armor/knockback_resist.json
[18:35:15] [main/INFO]: [wayoftime.bloodmagic.core.LivingArmorRegistrar:parseDefinition:188]: Attempting to load Living Armour Upgrade: modjar://bloodmagic/data/bloodmagic/living_armor/elytra.json, path: /data/bloodmagic/living_armor/elytra.json
[18:35:15] [main/INFO]: [wayoftime.bloodmagic.core.LivingArmorRegistrar:parseDefinition:188]: Attempting to load Living Armour Upgrade: modjar://bloodmagic/data/bloodmagic/living_armor/curios_socket.json, path: /data/bloodmagic/living_armor/curios_socket.json
[18:35:15] [main/INFO]: [wayoftime.bloodmagic.core.LivingArmorRegistrar:parseDefinition:188]: Attempting to load Living Armour Upgrade: modjar://bloodmagic/data/bloodmagic/living_armor/downgrade/quenched.json, path: /data/bloodmagic/living_armor/downgrade/quenched.json
[18:35:15] [main/INFO]: registerLootModifierSerializer
[18:35:15] [main/INFO]: Registered 11 GlobalLootModifierSerializer entries in 0.04ms.
[18:35:15] [main/INFO]: Registering level types
[18:35:15] [main/INFO]: M&A -> Ritual Effects Registered
[18:35:16] [main/INFO]: registerTileEntities
[18:35:16] [main/INFO]: Registered 0 tile entities.
[18:35:16] [main/INFO]: BYG: Block Entities registered!
[18:35:16] [main/INFO]: Registered 10 tile entities.
[18:35:16] [main/INFO]: Registered 2 TileEntityType entries in 0.01ms.
[18:35:16] [main/INFO]: Registered 1 TileEntityType entries in 0.01ms.
[18:35:16] [main/INFO]: Attempting to register Tile Entities
[18:35:17] [main/INFO]: Registered 18 tile entities.
[18:35:17] [main/INFO]: registerEnchantments
[18:35:17] [main/WARN]: Called deprecated GlobalEntityTypeAttributes#put for farmingforblockheads:merchant, use EntityAttributeCreationEvent instead.
[18:35:17] [main/INFO]: BYG: Entities registered!
[18:35:17] [main/WARN]: Called deprecated GlobalEntityTypeAttributes#put for elementalcraft:earthgolem, use EntityAttributeCreationEvent instead.
[18:35:17] [main/INFO]: Registered 1 entities bound to blocks.
[18:35:17] [main/INFO]: BYG: Block Entities registered!
[18:35:18] [main/INFO]: M&A -> Containers Registered
[18:35:18] [main/INFO]: Registered 8 containers bound to tile entities.
[18:35:19] [main/INFO]: [com.hollingsworth.arsnouveau.client.particle.ModParticles:registerParticles:23]: Rendering particles
[18:35:19] [main/INFO]: M&A -> Villager POI Registered
[18:35:20] [main/INFO]: registerRecipeSerializer
[18:35:20] [main/INFO]: Registered 22 ingredient serializers.
[18:35:20] [main/INFO]: Registered 5 IRecipeSerializer entries in 0.03ms.
[18:35:20] [main/INFO]: Registered 3 IRecipeSerializer entries in 0.01ms.
[18:35:21] [main/INFO]: Loading sounds.
[18:35:21] [main/INFO]: BYG: Sounds registered!
[18:35:21] [main/INFO]: M&A -> Villager Professions Registered
[18:35:22] [main/INFO]: BYG: Biomes registered!
[18:35:22] [main/INFO]: BYG: Registering block placer types!
[18:35:23] [main/INFO]: BYG: Decorators registered!
[18:35:23] [main/INFO]: Registering decorators
[18:35:23] [main/INFO]: BYG: Features registered!
[18:35:23] [main/INFO]: Registering features
[18:35:23] [main/INFO]: BYG: Structures registered!
[18:35:23] [main/INFO]: BYG: Surface builders Registered!
[18:35:23] [main/INFO]: M&A -> Block Colors Registered
[18:35:24] [main/INFO]: Adding 'add_enchantment_helper_levels' ASM patch...
[18:35:24] [main/INFO]: Added 'add_enchantment_helper_levels' ASM patch!
[18:35:24] [main/INFO]: Adding 'add_enchantment_helper_enchantments' ASM patch...
[18:35:24] [main/INFO]: Added 'add_enchantment_helper_enchantments' ASM patch!
[18:35:24] [main/INFO]: Adding 'add_enchantment_helper_apply_modifier' ASM patch...
[18:35:24] [main/INFO]: Added 'add_enchantment_helper_apply_modifier' ASM patch!
[18:35:24] [main/INFO]: Patching EnchantmentHelper#getEnchantmentModifierDamage
[18:35:24] [main/INFO]: Patching EnchantmentHelper#getModifierForCreature
[18:35:24] [main/INFO]: Patching EnchantmentHelper#applyThornEnchantments
[18:35:24] [main/INFO]: Patching EnchantmentHelper#applyArthropodEnchantments
[18:35:24] [main/INFO]: Patching buildEnchantmentList for the Enchantability affix.
[18:35:24] [main/INFO]: Patching EnchantmentHelper#getEnchantmentDatas
[18:35:24] [main/INFO]: Patching vazkii/quark/content/tools/module/AncientTomesModule
[18:35:25] [main/INFO]: [com.hollingsworth.arsnouveau.client.particle.ModParticles:registerFactories:36]: Rendering factories
[18:35:25] [main/INFO]: M&A -> Particle Factories Registered
[18:35:26] [main/INFO]: Narrator library for x64 successfully loaded
[18:35:26] [main/INFO]: Reloading ResourceManager: Default, Mod Resources, resources, quark-emote-pack, resources.zip, Solar Flux Generated Resources, KubeJS Resource Pack [assets]
[18:35:26] [main/INFO]: [OptiFine] *** Reloading textures ***
[18:35:26] [main/INFO]: [OptiFine] Resource packs: Mod Resources, resources, quark-emote-pack, resources.zip, Solar Flux Generated Resources
[18:35:26] [main/INFO]: [OptiFine] EmissiveTextures: Loading optifine/emissive.properties
[18:35:26] [main/INFO]: [OptiFine] *** Reflector Forge ***
[18:35:26] [main/INFO]: [OptiFine] (Reflector) Class not present: mods.betterfoliage.client.BetterFoliageClient
[18:35:26] [main/INFO]: [OptiFine] (Reflector) Class not present: net.minecraftforge.fml.common.ModContainer
[18:35:26] [Thread-1/FATAL]: theoneprobe config just got changed on the file system!
[18:35:26] [main/INFO]: [OptiFine] *** Reflector Vanilla ***
[18:35:26] [modloading-worker-7/INFO]: CLIENT CONFIG LOADED
[18:35:26] [modloading-worker-7/INFO]: Client config re-baked
[18:35:26] [modloading-worker-7/INFO]: Loading config file engineerstools-common.toml
[18:35:26] [modloading-worker-7/INFO]: **********************************************
[18:35:26] [modloading-worker-7/INFO]: All The Mods 6 Pack Version:1.8.19 loading
[18:35:26] [modloading-worker-7/INFO]: **********************************************
[18:35:26] [Thread-1/INFO]: **********************************************
[18:35:26] [Thread-1/INFO]: All The Mods 6 Pack Version:1.8.19 loading
[18:35:26] [Thread-1/INFO]: **********************************************
[18:35:26] [Thread-1/INFO]: **********************************************
[18:35:26] [Thread-1/INFO]: All The Mods 6 Pack Version:1.8.19 loading
[18:35:26] [Thread-1/INFO]: **********************************************
[18:35:26] [modloading-worker-7/INFO]: Executing phase CONFIG_LOAD for plugin class ImmersiveEngineeringPlugin
[18:35:26] [modloading-worker-7/INFO]: Executing phase CONFIG_LOAD for plugin class FTBChunksPlugin
[18:35:26] [modloading-worker-7/INFO]: Executing phase CONFIG_LOAD for plugin class AstralSorceryPlugin
[18:35:26] [modloading-worker-7/INFO]: Executing phase CONFIG_LOAD for plugin class CuriosPlugin
[18:35:26] [Thread-1/INFO]: Executing phase CONFIG_RELOAD for plugin class ImmersiveEngineeringPlugin
[18:35:26] [Thread-1/INFO]: Executing phase CONFIG_RELOAD for plugin class FTBChunksPlugin
[18:35:26] [Thread-1/INFO]: Executing phase CONFIG_RELOAD for plugin class AstralSorceryPlugin
[18:35:26] [Thread-1/INFO]: Executing phase CONFIG_RELOAD for plugin class CuriosPlugin
[18:35:26] [modloading-worker-7/INFO]: Executing phase CONFIG_LOAD for plugin class ImmersiveEngineeringPlugin
[18:35:26] [modloading-worker-7/INFO]: Executing phase CONFIG_LOAD for plugin class FTBChunksPlugin
[18:35:26] [modloading-worker-7/INFO]: Executing phase CONFIG_LOAD for plugin class AstralSorceryPlugin
[18:35:26] [modloading-worker-7/INFO]: Executing phase CONFIG_LOAD for plugin class CuriosPlugin
[18:35:26] [modloading-worker-7/INFO]: Executing phase CONFIG_LOAD for plugin class ImmersiveEngineeringPlugin
[18:35:26] [modloading-worker-7/INFO]: Executing phase CONFIG_LOAD for plugin class FTBChunksPlugin
[18:35:26] [modloading-worker-7/INFO]: Executing phase CONFIG_LOAD for plugin class AstralSorceryPlugin
[18:35:26] [modloading-worker-7/INFO]: Executing phase CONFIG_LOAD for plugin class CuriosPlugin
[18:35:26] [modloading-worker-7/INFO]: Executing phase CONFIG_LOAD for plugin class ImmersiveEngineeringPlugin
[18:35:26] [modloading-worker-7/INFO]: Executing phase CONFIG_LOAD for plugin class FTBChunksPlugin
[18:35:26] [modloading-worker-7/INFO]: Executing phase CONFIG_LOAD for plugin class AstralSorceryPlugin
[18:35:26] [modloading-worker-7/INFO]: Executing phase CONFIG_LOAD for plugin class CuriosPlugin
[18:35:26] [modloading-worker-7/INFO]: Executing phase CONFIG_LOAD for plugin class ImmersiveEngineeringPlugin
[18:35:26] [modloading-worker-7/INFO]: Executing phase CONFIG_LOAD for plugin class FTBChunksPlugin
[18:35:26] [modloading-worker-7/INFO]: Executing phase CONFIG_LOAD for plugin class AstralSorceryPlugin
[18:35:26] [modloading-worker-7/INFO]: Executing phase CONFIG_LOAD for plugin class CuriosPlugin
[18:35:27] [Worker-Main-5/INFO]: Reloading material model files
[18:35:27] [Worker-Main-7/INFO]: 75 material render infos loaded
[18:35:27] [modloading-worker-7/INFO]: BLACKLIST RELOADED
[18:35:27] [modloading-worker-7/INFO]: COMMON CONFIG LOADED
[18:35:27] [modloading-worker-7/INFO]: Common config re-baked
[18:35:27] [modloading-worker-7/INFO]: Loading Module Chain Linkage
[18:35:27] [modloading-worker-7/INFO]: Loading Module Chains Connect Blocks
[18:35:27] [modloading-worker-7/INFO]: Loading Module Chute
[18:35:27] [modloading-worker-7/INFO]: Loading Module Color Slime
[18:35:27] [modloading-worker-7/INFO]: Loading Module Dispensers Place Blocks
[18:35:27] [modloading-worker-7/INFO]: Loading Module Ender Watcher
[18:35:27] [modloading-worker-7/INFO]: Loading Module Endermites Form Shulkers
[18:35:27] [modloading-worker-7/INFO]: Loading Module Feeding Trough
[18:35:27] [modloading-worker-7/INFO]: Loading Module Gravisand
[18:35:27] [modloading-worker-7/INFO]: Loading Module Iron Rod
[18:35:27] [modloading-worker-7/INFO]: Loading Module Jukebox Automation
[18:35:27] [modloading-worker-7/INFO]: Loading Module Metal Buttons
[18:35:27] [modloading-worker-7/INFO]: Loading Module Obsidian Plate
[18:35:27] [modloading-worker-7/INFO]: Loading Module Pistons Move Tile Entities
[18:35:27] [modloading-worker-7/INFO]: Loading Module Redstone Circuit
[18:35:27] [modloading-worker-7/INFO]: Loading Module Weather Sensor
[18:35:27] [modloading-worker-7/INFO]: Loading Module Bamboo Mat
[18:35:27] [modloading-worker-7/INFO]: Loading Module Burn Vines
[18:35:27] [modloading-worker-7/INFO]: Loading Module Celebratory Lamps
[18:35:27] [modloading-worker-7/INFO]: Loading Module Cobblestone Bricks
[18:35:27] [modloading-worker-7/INFO]: Loading Module Compressed Blocks
[18:35:27] [modloading-worker-7/INFO]: Loading Module Duskbound Blocks
[18:35:27] [modloading-worker-7/INFO]: Loading Module Framed Glass
[18:35:27] [modloading-worker-7/INFO]: Loading Module Gold Bars
[18:35:27] [modloading-worker-7/INFO]: Loading Module Grate
[18:35:27] [modloading-worker-7/INFO]: Loading Module Hedges
[18:35:27] [modloading-worker-7/INFO]: Loading Module Iron Plates
[18:35:27] [modloading-worker-7/INFO]: Loading Module Item Frames
[18:35:27] [modloading-worker-7/INFO]: Loading Module Leaf Carpet
[18:35:27] [modloading-worker-7/INFO]: Loading Module Lit Lamp
[18:35:27] [modloading-worker-7/INFO]: Loading Module Midori
[18:35:27] [modloading-worker-7/INFO]: Loading Module More Brick Types
[18:35:27] [modloading-worker-7/INFO]: Loading Module More Potted Plants
[18:35:27] [modloading-worker-7/INFO]: Loading Module More Stone Variants
[18:35:27] [modloading-worker-7/INFO]: Loading Module Nether Brick Fence Gate
[18:35:27] [modloading-worker-7/INFO]: Loading Module Paper Decor
[18:35:27] [modloading-worker-7/INFO]: Loading Module Quilted Wool
[18:35:27] [modloading-worker-7/INFO]: Loading Module Rope
[18:35:27] [modloading-worker-7/INFO]: Loading Module Shallow Dirt
[18:35:27] [modloading-worker-7/INFO]: Loading Module Shingles
[18:35:27] [modloading-worker-7/INFO]: Loading Module Soul Sandstone
[18:35:27] [modloading-worker-7/INFO]: Loading Module Stained Planks
[18:35:27] [modloading-worker-7/INFO]: Loading Module Stools
[18:35:27] [modloading-worker-7/INFO]: Loading Module Sturdy Stone
[18:35:27] [modloading-worker-7/INFO]: Loading Module Tallow And Candles
[18:35:27] [modloading-worker-7/INFO]: Loading Module Thatch
[18:35:27] [modloading-worker-7/INFO]: Loading Module Tie Leads To Fences
[18:35:27] [modloading-worker-7/INFO]: Loading Module Turf
[18:35:27] [modloading-worker-7/INFO]: Loading Module Variant Bookshelves
[18:35:27] [modloading-worker-7/INFO]: Loading Module Variant Chests
[18:35:27] [modloading-worker-7/INFO]: Loading Module Variant Ladders
[18:35:27] [modloading-worker-7/INFO]: Loading Module Vertical Planks
[18:35:27] [modloading-worker-7/INFO]: Loading Module Vertical Slabs
[18:35:27] [modloading-worker-7/INFO]: Loading Module Wooden Posts
[18:35:27] [modloading-worker-7/INFO]: Loading Module Chests In Boats
[18:35:27] [modloading-worker-7/INFO]: Loading Module Easy Transfering
[18:35:27] [modloading-worker-7/INFO]: Loading Module Hotbar Changer
[18:35:27] [modloading-worker-7/INFO]: Loading Module Inventory Sorting
[18:35:27] [modloading-worker-7/INFO]: Loading Module Item Sharing
[18:35:27] [modloading-worker-7/INFO]: Loading Module Right Click Armor
[18:35:27] [modloading-worker-7/INFO]: Loading Module Shulker Box Right Click
[18:35:27] [modloading-worker-7/INFO]: Loading Module Endermosh Music Disc
[18:35:27] [modloading-worker-7/INFO]: Loading Module Abacus
[18:35:27] [modloading-worker-7/INFO]: Loading Module Ambient Discs
[18:35:27] [modloading-worker-7/INFO]: Loading Module Ancient Tomes
[18:35:27] [modloading-worker-7/INFO]: Loading Module Bottled Cloud
[18:35:27] [modloading-worker-7/INFO]: Loading Module Camera
[18:35:27] [modloading-worker-7/INFO]: Loading Module Color Runes
[18:35:27] [modloading-worker-7/INFO]: Loading Module Pathfinder Maps
[18:35:27] [modloading-worker-7/INFO]: Loading Module Pickarang
[18:35:27] [modloading-worker-7/INFO]: Loading Module Seed Pouch
[18:35:27] [modloading-worker-7/INFO]: Loading Module Slime In A Bucket
[18:35:27] [modloading-worker-7/INFO]: Loading Module Trowel
[18:35:27] [modloading-worker-7/INFO]: Loading Module Skull Pikes
[18:35:27] [modloading-worker-7/INFO]: Loading Module Armed Armor Stands
[18:35:27] [modloading-worker-7/INFO]: Loading Module Automatic Recipe Unlock
[18:35:27] [modloading-worker-7/INFO]: Loading Module Axe Leaf Harvesting
[18:35:27] [modloading-worker-7/INFO]: Loading Module Better Elytra Rocket
[18:35:27] [modloading-worker-7/INFO]: Loading Module Campfires Boost Elytra
[18:35:27] [modloading-worker-7/INFO]: Loading Module Compasses Work Everywhere
[18:35:27] [modloading-worker-7/INFO]: Loading Module Dirt To Path
[18:35:27] [modloading-worker-7/INFO]: Loading Module Double Door Opening
[18:35:27] [modloading-worker-7/INFO]: Loading Module Dragon Scales
[18:35:27] [modloading-worker-7/INFO]: Loading Module Emotes
[18:35:27] [modloading-worker-7/INFO]: Loading Module Enhanced Ladders
[18:35:27] [modloading-worker-7/INFO]: Loading Module Glass Shard
[18:35:27] [modloading-worker-7/INFO]: Loading Module Hoe Harvesting
[18:35:27] [modloading-worker-7/INFO]: Loading Module Improved Sleeping
[18:35:27] [modloading-worker-7/INFO]: Loading Module Infinity Bucket
[18:35:27] [modloading-worker-7/INFO]: Loading Module Lava Bucket As Trash
[18:35:27] [modloading-worker-7/INFO]: Loading Module Lock Rotation
[18:35:27] [modloading-worker-7/INFO]: Loading Module More Banner Layers
[18:35:27] [modloading-worker-7/INFO]: Loading Module Note Block Mob Sounds
[18:35:27] [modloading-worker-7/INFO]: Loading Module Pat The Dogs
[18:35:27] [modloading-worker-7/INFO]: Loading Module Poison Potato Usage
[18:35:27] [modloading-worker-7/INFO]: Loading Module Reacharound Placing
[18:35:27] [modloading-worker-7/INFO]: Loading Module Replace Scaffolding
[18:35:27] [modloading-worker-7/INFO]: Loading Module Sign Editing
[18:35:27] [modloading-worker-7/INFO]: Loading Module Simple Harvest
[18:35:27] [modloading-worker-7/INFO]: Loading Module Snow Golem Player Heads
[18:35:27] [modloading-worker-7/INFO]: Loading Module Springy Slime
[18:35:27] [modloading-worker-7/INFO]: Loading Module Utility Recipes
[18:35:27] [modloading-worker-7/INFO]: Loading Module Villagers Follow Emeralds
[18:35:27] [modloading-worker-7/INFO]: Loading Module Big Dungeon
[18:35:27] [modloading-worker-7/INFO]: Loading Module Big Stone Clusters
[18:35:27] [modloading-worker-7/INFO]: Loading Module Biotite
[18:35:27] [modloading-worker-7/INFO]: Loading Module Blossom Trees
[18:35:27] [modloading-worker-7/INFO]: Loading Module Cave Roots
[18:35:27] [modloading-worker-7/INFO]: Loading Module Chorus Vegetation
[18:35:27] [modloading-worker-7/INFO]: Loading Module Crevices
[18:35:27] [modloading-worker-7/INFO]: Loading Module Deepslate
[18:35:27] [modloading-worker-7/INFO]: Loading Module Fairy Rings
[18:35:27] [modloading-worker-7/INFO]: Loading Module Mega Caves
[18:35:27] [modloading-worker-7/INFO]: Loading Module Monster Box
[18:35:27] [modloading-worker-7/INFO]: Loading Module Nether Obsidian Spikes
[18:35:27] [modloading-worker-7/INFO]: Loading Module New Stone Types
[18:35:27] [modloading-worker-7/INFO]: Loading Module Realistic World Gen
[18:35:27] [modloading-worker-7/INFO]: Loading Module Speleothems
[18:35:27] [modloading-worker-7/INFO]: Loading Module Spiral Spires
[18:35:27] [modloading-worker-7/INFO]: Loading Module Underground Clay
[18:35:27] [modloading-worker-7/INFO]: Loading Module Brimstone Underground Biome
[18:35:27] [modloading-worker-7/INFO]: Loading Module Cave Crystal Underground Biome
[18:35:27] [modloading-worker-7/INFO]: Loading Module Elder Prismarine Underground Biome
[18:35:27] [modloading-worker-7/INFO]: Loading Module Glowshroom Underground Biome
[18:35:27] [modloading-worker-7/INFO]: Loading Module Lush Underground Biome
[18:35:27] [modloading-worker-7/INFO]: Loading Module Overgrown Underground Biome
[18:35:27] [modloading-worker-7/INFO]: Loading Module Permafrost Underground Biome
[18:35:27] [modloading-worker-7/INFO]: Loading Module Sandstone Underground Biome
[18:35:27] [modloading-worker-7/INFO]: Loading Module Slime Underground Biome
[18:35:27] [modloading-worker-7/INFO]: Loading Module Spider Nest Underground Biome
[18:35:27] [modloading-worker-7/INFO]: Loading Module Crabs
[18:35:27] [modloading-worker-7/INFO]: Loading Module Forgotten
[18:35:27] [modloading-worker-7/INFO]: Loading Module Foxhound
[18:35:27] [modloading-worker-7/INFO]: Loading Module Frogs
[18:35:27] [modloading-worker-7/INFO]: Loading Module Stonelings
[18:35:27] [modloading-worker-7/INFO]: Loading Module Toretoise
[18:35:27] [modloading-worker-7/INFO]: Loading Module Wraith
[18:35:27] [modloading-worker-7/INFO]: Loading Module Auto Walk Keybind
[18:35:27] [modloading-worker-7/INFO]: Loading Module Back Button Keybind
[18:35:27] [modloading-worker-7/INFO]: Loading Module Chest Searching
[18:35:27] [modloading-worker-7/INFO]: Loading Module Greener Grass
[18:35:27] [modloading-worker-7/INFO]: Loading Module Improved Mount Hud
[18:35:27] [modloading-worker-7/INFO]: Loading Module Improved Tooltips
[18:35:27] [modloading-worker-7/INFO]: Loading Module Usage Ticker
[18:35:27] [modloading-worker-7/INFO]: Loading Module Variant Animal Textures
[18:35:27] [modloading-worker-7/INFO]: Loading Module Backpack
[18:35:27] [modloading-worker-7/INFO]: Loading Module Crate
[18:35:27] [modloading-worker-7/INFO]: Loading Module Magnets
[18:35:27] [modloading-worker-7/INFO]: Loading Module Matrix Enchanting
[18:35:27] [modloading-worker-7/INFO]: Loading Module Pipes
[18:35:27] [modloading-worker-7/INFO]: Loading Module Totem Of Holding
[18:35:27] [modloading-worker-7/INFO]: Loading Module Adjustable Chat
[18:35:27] [modloading-worker-7/INFO]: Loading Module Custom Underground Biome
[18:35:27] [modloading-worker-7/INFO]: Loading Module Game Nerfs
[18:35:27] [modloading-worker-7/INFO]: Loading Module Microcrafting Helper
[18:35:27] [modloading-worker-7/INFO]: Loading Module Narrator Readout
[18:35:27] [modloading-worker-7/INFO]: Loading Module Overlay Shader
[18:35:27] [modloading-worker-7/INFO]: Loading Module Pallet
[18:35:27] [modloading-worker-7/INFO]: Loading Module Shiba
[18:35:27] [Worker-Main-5/INFO]: Reloading part model files
[18:35:27] [Worker-Main-7/INFO]: Setup HammerLib networking!
[18:35:27] [Worker-Main-5/INFO]: Registered packet handler.
[18:35:27] [Worker-Main-7/INFO]: [OptiFine] Multitexture: false
[18:35:27] [Worker-Main-3/INFO]: [OptiFine] Multitexture: false
[18:35:27] [Worker-Main-4/INFO]: [OptiFine] Multitexture: false
[18:35:28] [Worker-Main-8/INFO]: [OptiFine] Multitexture: false
[18:35:28] [Worker-Main-6/INFO]: [OptiFine] Multitexture: false
[18:35:32] [Worker-Main-2/INFO]: [OptiFine] Multitexture: false
[18:35:48] [Worker-Main-5/WARN]: [OptiFine] Unknown resource pack type: org.zeith.solarflux.client.SolarFluxResourcePack@348748d7
[18:35:48] [Worker-Main-5/WARN]: [OptiFine] Unknown resource pack type: org.zeith.solarflux.client.SolarFluxResourcePack@348748d7
[18:35:48] [Worker-Main-5/WARN]: [OptiFine] Unknown resource pack type: org.zeith.solarflux.client.SolarFluxResourcePack@348748d7
[18:35:48] [Worker-Main-5/WARN]: [OptiFine] Unknown resource pack type: org.zeith.solarflux.client.SolarFluxResourcePack@348748d7
[18:35:48] [Worker-Main-5/WARN]: [OptiFine] Unknown resource pack file: mod_resources
[18:35:48] [Worker-Main-5/WARN]: [OptiFine] Unknown resource pack file: mod_resources
[18:35:48] [Worker-Main-5/WARN]: [OptiFine] Unknown resource pack file: mod_resources
[18:35:48] [Worker-Main-5/WARN]: [OptiFine] Unknown resource pack file: mod_resources
[18:36:02] [Worker-Main-5/INFO]: Textures for fragment model
[18:36:02] [Worker-Main-5/INFO]: - silentgear:item/fragment/wood
[18:36:02] [Worker-Main-5/INFO]: - silentgear:item/fragment/cloth
[18:36:02] [Worker-Main-5/INFO]: - silentgear:item/fragment/metal
[18:36:02] [Worker-Main-5/INFO]: - silentgear:item/fragment/dust
[18:36:02] [Worker-Main-5/INFO]: - silentgear:item/error
[18:36:07] [Worker-Main-5/INFO]: [OptiFine] Multitexture: false
[18:36:07] [Worker-Main-5/WARN]: [OptiFine] Unknown resource pack type: org.zeith.solarflux.client.SolarFluxResourcePack@348748d7
[18:36:07] [Worker-Main-5/INFO]: [OptiFine] Multipass connected textures: false
[18:36:07] [Worker-Main-5/INFO]: [OptiFine] Multipass connected textures: false
[18:36:08] [Worker-Main-5/INFO]: [OptiFine] Multipass connected textures: false
[18:36:08] [Worker-Main-5/INFO]: [OptiFine] Multipass connected textures: false
[18:36:08] [Worker-Main-5/WARN]: [OptiFine] Unknown resource pack file: mod_resources
[18:36:08] [Worker-Main-5/INFO]: [OptiFine] Multipass connected textures: false
[18:36:08] [Worker-Main-5/INFO]: [OptiFine] ConnectedTextures: optifine/ctm/default/00_glass_white/glass_pane_white.properties
[18:36:08] [Worker-Main-5/INFO]: [OptiFine] ConnectedTextures: optifine/ctm/default/00_glass_white/glass_white.properties
[18:36:08] [Worker-Main-5/INFO]: [OptiFine] ConnectedTextures: optifine/ctm/default/01_glass_orange/glass_orange.properties
[18:36:08] [Worker-Main-5/INFO]: [OptiFine] ConnectedTextures: optifine/ctm/default/01_glass_orange/glass_pane_orange.properties
[18:36:08] [Worker-Main-5/INFO]: [OptiFine] ConnectedTextures: optifine/ctm/default/02_glass_magenta/glass_magenta.properties
[18:36:09] [Worker-Main-5/INFO]: [OptiFine] ConnectedTextures: optifine/ctm/default/02_glass_magenta/glass_pane_magenta.properties
[18:36:09] [Worker-Main-5/INFO]: [OptiFine] ConnectedTextures: optifine/ctm/default/03_glass_light_blue/glass_light_blue.properties
[18:36:09] [Worker-Main-5/INFO]: [OptiFine] ConnectedTextures: optifine/ctm/default/03_glass_light_blue/glass_pane_light_blue.properties
[18:36:09] [Worker-Main-5/INFO]: [OptiFine] ConnectedTextures: optifine/ctm/default/04_glass_yellow/glass_pane_yellow.properties
[18:36:09] [Worker-Main-5/INFO]: [OptiFine] ConnectedTextures: optifine/ctm/default/04_glass_yellow/glass_yellow.properties
[18:36:09] [Worker-Main-5/INFO]: [OptiFine] ConnectedTextures: optifine/ctm/default/05_glass_lime/glass_lime.properties
[18:36:09] [Worker-Main-5/INFO]: [OptiFine] ConnectedTextures: optifine/ctm/default/05_glass_lime/glass_pane_lime.properties
[18:36:09] [Worker-Main-5/INFO]: [OptiFine] ConnectedTextures: optifine/ctm/default/06_glass_pink/glass_pane_pink.properties
[18:36:10] [Worker-Main-5/INFO]: [OptiFine] ConnectedTextures: optifine/ctm/default/06_glass_pink/glass_pink.properties
[18:36:10] [Worker-Main-5/INFO]: [OptiFine] ConnectedTextures: optifine/ctm/default/07_glass_gray/glass_gray.properties
[18:36:10] [Worker-Main-5/INFO]: [OptiFine] ConnectedTextures: optifine/ctm/default/07_glass_gray/glass_pane_gray.properties
[18:36:10] [Worker-Main-5/INFO]: [OptiFine] ConnectedTextures: optifine/ctm/default/08_glass_light_gray/glass_light_gray.properties
[18:36:10] [Worker-Main-5/INFO]: [OptiFine] ConnectedTextures: optifine/ctm/default/08_glass_light_gray/glass_pane_light_gray.properties
[18:36:10] [Worker-Main-5/INFO]: [OptiFine] ConnectedTextures: optifine/ctm/default/09_glass_cyan/glass_cyan.properties
[18:36:10] [Worker-Main-5/INFO]: [OptiFine] ConnectedTextures: optifine/ctm/default/09_glass_cyan/glass_pane_cyan.properties
[18:36:11] [Worker-Main-5/INFO]: [OptiFine] ConnectedTextures: optifine/ctm/default/10_glass_purple/glass_pane_purple.properties
[18:36:11] [Worker-Main-5/INFO]: [OptiFine] ConnectedTextures: optifine/ctm/default/10_glass_purple/glass_purple.properties
[18:36:11] [Worker-Main-5/INFO]: [OptiFine] ConnectedTextures: optifine/ctm/default/11_glass_blue/glass_blue.properties
[18:36:11] [Worker-Main-5/INFO]: [OptiFine] ConnectedTextures: optifine/ctm/default/11_glass_blue/glass_pane_blue.properties
[18:36:11] [Worker-Main-5/INFO]: [OptiFine] ConnectedTextures: optifine/ctm/default/12_glass_brown/glass_brown.properties
[18:36:11] [Worker-Main-5/INFO]: [OptiFine] ConnectedTextures: optifine/ctm/default/12_glass_brown/glass_pane_brown.properties
[18:36:11] [Worker-Main-5/INFO]: [OptiFine] ConnectedTextures: optifine/ctm/default/13_glass_green/glass_green.properties
[18:36:12] [Worker-Main-5/INFO]: [OptiFine] ConnectedTextures: optifine/ctm/default/13_glass_green/glass_pane_green.properties
[18:36:12] [Worker-Main-5/INFO]: [OptiFine] ConnectedTextures: optifine/ctm/default/14_glass_red/glass_pane_red.properties
[18:36:12] [Worker-Main-5/INFO]: [OptiFine] ConnectedTextures: optifine/ctm/default/14_glass_red/glass_red.properties
[18:36:12] [Worker-Main-5/INFO]: [OptiFine] ConnectedTextures: optifine/ctm/default/15_glass_black/glass_black.properties
[18:36:12] [Worker-Main-5/INFO]: [OptiFine] ConnectedTextures: optifine/ctm/default/15_glass_black/glass_pane_black.properties
[18:36:12] [Worker-Main-5/INFO]: [OptiFine] ConnectedTextures: optifine/ctm/default/20_glass/glass.properties
[18:36:12] [Worker-Main-5/INFO]: [OptiFine] ConnectedTextures: optifine/ctm/default/20_glass/glass_pane.properties
[18:36:12] [Worker-Main-5/INFO]: [OptiFine] ConnectedTextures: optifine/ctm/default/30_bookshelf/bookshelf.properties
[18:36:12] [Worker-Main-5/INFO]: [OptiFine] ConnectedTextures: optifine/ctm/default/40_sandstone/sandstone.properties
[18:36:12] [Worker-Main-5/INFO]: [OptiFine] ConnectedTextures: optifine/ctm/default/41_red_sandstone/red_sandstone.properties
[18:36:12] [Worker-Main-5/INFO]: [OptiFine] Multipass connected textures: false
[18:36:12] [Worker-Main-5/INFO]: [OptiFine] BetterGrass: Parsing default configuration optifine/bettergrass.properties
[18:38:25] [Worker-Main-5/INFO]: Stitching Revolver Textures!
[18:38:25] [Worker-Main-9/INFO]: --- LootTable import: Start ---
[18:38:25] [Worker-Main-9/INFO]: [SUCCESS] Line 13: Added loot to table: Strainer: strainer_survivalist - Item: minecraft:sand - Count: 1 - Group: null - Chance: 30 - Subchance: 100 - NBT: null
[18:38:25] [Worker-Main-9/INFO]: [SUCCESS] Line 14: Added loot to table: Strainer: strainer_survivalist - Item: minecraft:dirt - Count: 1 - Group: null - Chance: 20 - Subchance: 100 - NBT: null
[18:38:25] [Worker-Main-9/INFO]: [SUCCESS] Line 15: Added loot to table: Strainer: strainer_survivalist - Item: minecraft:stick - Count: 1 - Group: null - Chance: 20 - Subchance: 100 - NBT: null
[18:38:25] [Worker-Main-9/INFO]: [SUCCESS] Line 16: Added loot to table: Strainer: strainer_survivalist - Item: minecraft:clay_ball - Count: 1 - Group: null - Chance: 15 - Subchance: 100 - NBT: null
[18:38:25] [Worker-Main-9/INFO]: [SUCCESS] Line 17: Added loot to table: Strainer: strainer_survivalist - Item: minecraft:gravel - Count: 1 - Group: null - Chance: 13 - Subchance: 100 - NBT: null
[18:38:25] [Worker-Main-9/INFO]: [SUCCESS] Line 18: Added loot to table: Strainer: strainer_survivalist - Item: minecraft:iron_nugget - Count: 1 - Group: NUGGET - Chance: 2 - Subchance: 75 - NBT: null
[18:38:25] [Worker-Main-9/INFO]: [SUCCESS] Line 19: Added loot to table: Strainer: strainer_survivalist - Item: minecraft:gold_nugget - Count: 1 - Group: NUGGET - Chance: 2 - Subchance: 25 - NBT: null
[18:38:25] [Worker-Main-9/INFO]: [SUCCESS] Line 21: Copied loot table data from <parent> 'strainer_survivalist' to <child> 'strainer_survivalist_solid'
[18:38:25] [Worker-Main-9/INFO]: [SUCCESS] Line 22: Copied loot table data from <parent> 'strainer_survivalist' to <child> 'strainer_survivalist_reinforced'
[18:38:25] [Worker-Main-9/INFO]: [SUCCESS] Line 25: Added loot to table: Strainer: strainer_fisherman - Item: minecraft:cod - Count: 1 - Group: FISH - Chance: 100 - Subchance: 60 - NBT: null
[18:38:25] [Worker-Main-9/INFO]: [SUCCESS] Line 26: Added loot to table: Strainer: strainer_fisherman - Item: minecraft:salmon - Count: 1 - Group: FISH - Chance: 100 - Subchance: 25 - NBT: null
[18:38:25] [Worker-Main-9/INFO]: [SUCCESS] Line 27: Added loot to table: Strainer: strainer_fisherman - Item: minecraft:pufferfish - Count: 1 - Group: FISH - Chance: 100 - Subchance: 13 - NBT: null
[18:38:25] [Worker-Main-9/INFO]: [SUCCESS] Line 28: Added loot to table: Strainer: strainer_fisherman - Item: minecraft:tropical_fish - Count: 1 - Group: FISH - Chance: 100 - Subchance: 2 - NBT: null
[18:38:25] [Worker-Main-9/INFO]: [SUCCESS] Line 29: Added loot to table: Strainer: strainer_fisherman - Item: minecraft:stick - Count: 1 - Group: JUNK - Chance: 30 - Subchance: 22 - NBT: null
[18:38:25] [Worker-Main-9/INFO]: [SUCCESS] Line 30: Added loot to table: Strainer: strainer_fisherman - Item: minecraft:string - Count: 1 - Group: JUNK - Chance: 30 - Subchance: 13 - NBT: null
[18:38:25] [Worker-Main-9/INFO]: [SUCCESS] Line 31: Added loot to table: Strainer: strainer_fisherman - Item: minecraft:leather - Count: 1 - Group: JUNK - Chance: 30 - Subchance: 13 - NBT: null
[18:38:25] [Worker-Main-9/INFO]: [SUCCESS] Line 32: Added loot to table: Strainer: strainer_fisherman - Item: minecraft:rotten_flesh - Count: 1 - Group: JUNK - Chance: 30 - Subchance: 13 - NBT: null
[18:38:25] [Worker-Main-9/INFO]: [SUCCESS] Line 33: Added loot to table: Strainer: strainer_fisherman - Item: minecraft:bone - Count: 1 - Group: JUNK - Chance: 30 - Subchance: 13 - NBT: null
[18:38:25] [Worker-Main-9/INFO]: [SUCCESS] Line 34: Added loot to table: Strainer: strainer_fisherman - Item: minecraft:glass_bottle - Count: 1 - Group: JUNK - Chance: 30 - Subchance: 12 - NBT: null
[18:38:25] [Worker-Main-9/INFO]: [SUCCESS] Line 35: Added loot to table: Strainer: strainer_fisherman - Item: minecraft:lily_pad - Count: 1 - Group: JUNK - Chance: 30 - Subchance: 7 - NBT: null
[18:38:25] [Worker-Main-9/INFO]: [SUCCESS] Line 36: Added loot to table: Strainer: strainer_fisherman - Item: minecraft:vine - Count: 1 - Group: JUNK - Chance: 30 - Subchance: 7 - NBT: null
[18:38:25] [Worker-Main-9/INFO]: [SUCCESS] Line 37: Added loot to table: Strainer: strainer_fisherman - Item: minecraft:enchanted_book - Count: 1 - Group: null - Chance: 1 - Subchance: 100 - NBT: null
[18:38:25] [Worker-Main-9/INFO]: [SUCCESS] Line 38: Added loot to table: Strainer: strainer_fisherman - Item: $BLANK$ - Count: 1 - Group: null - Chance: 69 - Subchance: 100 - NBT: null
[18:38:25] [Worker-Main-9/INFO]: [SUCCESS] Line 40: Copied loot table data from <parent> 'strainer_fisherman' to <child> 'strainer_fisherman_solid'
[18:38:25] [Worker-Main-9/INFO]: [SUCCESS] Line 41: Copied loot table data from <parent> 'strainer_fisherman' to <child> 'strainer_fisherman_reinforced'
[18:38:25] [Worker-Main-9/INFO]: Result: Found 0 errors
[18:38:25] [Worker-Main-9/INFO]: --- LootTable import: End ---
[18:38:25] [Worker-Main-9/INFO]: Zooming chunks initiated!
[18:38:25] [Worker-Main-9/INFO]: Executing phase COMMON_SETUP for plugin class ImmersiveEngineeringPlugin
[18:38:25] [Worker-Main-9/INFO]: Executing phase COMMON_SETUP for plugin class FTBChunksPlugin
[18:38:25] [Worker-Main-9/INFO]: Executing phase COMMON_SETUP for plugin class AstralSorceryPlugin
[18:38:25] [Worker-Main-9/INFO]: Executing phase COMMON_SETUP for plugin class CuriosPlugin
[18:38:25] [Worker-Main-3/INFO]: [OptiFine] Scaled non power of 2: jei:gui/icons/recipe_transfer, 7 -> 14
[18:38:25] [Worker-Main-4/INFO]: ConstructionWand says hello - may the odds be ever in your favor.
[18:38:25] [Worker-Main-9/INFO]: Loading compat module for mod patchouli
[18:38:25] [Worker-Main-9/INFO]: Loading compat module for mod curios
[18:38:25] [Worker-Main-4/INFO]: Botania integration added
[18:38:26] [Worker-Main-4/INFO]: Trait: codechicken/multipart/trait/TTileChangeTile
[18:38:26] [Worker-Main-4/INFO]:     Marker: codechicken/multipart/api/part/INeighborTileChangePart, Side: SERVER
[18:38:26] [Worker-Main-4/INFO]: Trait: codechicken/multipart/trait/TTickableTile
[18:38:26] [Worker-Main-4/INFO]:     Marker: codechicken/multipart/api/part/ITickablePart, Side: COMMON
[18:38:26] [Worker-Main-4/INFO]: Trait: codechicken/multipart/trait/TSlottedTile
[18:38:26] [Worker-Main-4/INFO]:     Marker: codechicken/multipart/api/part/TSlottedPart, Side: COMMON
[18:38:26] [Worker-Main-4/INFO]: Trait: codechicken/multipart/trait/TRedstoneTile
[18:38:26] [Worker-Main-4/INFO]:     Marker: codechicken/multipart/api/part/redstone/IRedstonePart, Side: COMMON
[18:38:26] [Worker-Main-4/INFO]: Trait: codechicken/multipart/trait/TPartialOcclusionTile
[18:38:26] [Worker-Main-4/INFO]:     Marker: codechicken/multipart/api/part/TPartialOcclusionPart, Side: COMMON
[18:38:26] [Worker-Main-4/INFO]: Trait: codechicken/multipart/trait/TInventoryTile
[18:38:26] [Worker-Main-4/INFO]:     Marker: net/minecraft/inventory/IInventory, Side: COMMON
[18:38:26] [Worker-Main-4/INFO]:     Marker: net/minecraft/inventory/ISidedInventory, Side: COMMON
[18:38:26] [Worker-Main-4/INFO]: Trait: codechicken/multipart/trait/TInventoryTile
[18:38:26] [Worker-Main-4/INFO]:     Marker: net/minecraft/inventory/IInventory, Side: COMMON
[18:38:26] [Worker-Main-4/INFO]: Trait: codechicken/multipart/trait/TInventoryTile
[18:38:26] [Worker-Main-4/INFO]:     Marker: net/minecraft/inventory/ISidedInventory, Side: COMMON
[18:38:26] [Worker-Main-4/INFO]: Trait: codechicken/multipart/trait/TCapabilityTile
[18:38:26] [Worker-Main-4/INFO]:     Marker: codechicken/multipart/api/ICapabilityProviderPart, Side: COMMON
[18:38:26] [Worker-Main-4/INFO]: Trait: codechicken/multipart/trait/TAnimateTickTile
[18:38:26] [Worker-Main-4/INFO]:     Marker: codechicken/multipart/api/part/AnimateTickPart, Side: CLIENT
[18:38:26] [Worker-Main-9/INFO]: -- Nature's Aura Fake Player Information --
[18:38:26] [Worker-Main-9/INFO]: Name: [Minecraft]
[18:38:26] [Worker-Main-9/INFO]: UUID: 41C82C87-7AfB-4024-BA57-13D2C99CAE77
[18:38:26] [Worker-Main-9/INFO]: -------------------------------------------
[18:38:26] [Worker-Main-9/INFO]: Trait: mrtjp/projectred/illumination/LightMicroblock
[18:38:26] [Worker-Main-9/INFO]:     Marker: mrtjp/projectred/illumination/ILightMicroblockMixinMarker, Side: COMMON
[18:38:26] [Worker-Main-9/INFO]: Blacklisting capturing of all entities from cyberware
[18:38:26] [Worker-Main-9/INFO]: Blacklisting capturing of all entities from withercrumbs
[18:38:26] [Worker-Main-9/INFO]: Blacklisting capturing of twighlightforest:knight_phantom
[18:38:26] [Worker-Main-9/INFO]: Blacklisting capturing of twighlightforest:lich
[18:38:26] [Worker-Main-9/INFO]: Blacklisting capturing of twighlightforest:quest_ram
[18:38:26] [Worker-Main-9/INFO]: Blacklisting capturing of iceandfire:myrmex_worker
[18:38:26] [Worker-Main-9/INFO]: Blacklisting capturing of iceandfire:myrmex_soldier
[18:38:26] [Worker-Main-9/INFO]: Blacklisting capturing of iceandfire:myrmex_sentinel
[18:38:26] [Worker-Main-9/INFO]: Blacklisting capturing of iceandfire:myrmex_royal
[18:38:26] [Worker-Main-9/INFO]: Blacklisting capturing of iceandfire:myrmex_queen
[18:38:26] [Worker-Main-9/INFO]: Blacklisting learning of all items from cyberware
[18:38:26] [Worker-Main-9/INFO]: Blacklisting learning of all items from ebwizardry
[18:38:26] [Worker-Main-9/INFO]: Blacklisting learning of all items from eplus
[18:38:26] [Worker-Main-9/INFO]: Blacklisting learning of all items from everlastingabilities
[18:38:26] [Worker-Main-9/INFO]: Blacklisting learning of rftoolsdim:empty_dimlet
[18:38:26] [Worker-Main-9/INFO]: Blacklisting learning of rftoolsdim:empty_terrain_dimlet
[18:38:26] [Worker-Main-9/INFO]: Blacklisting learning of rftoolsdim:empty_attribute_dimlet
[18:38:26] [Worker-Main-9/INFO]: Blacklisting learning of rftoolsdim:empty_feature_dimlet
[18:38:26] [Worker-Main-9/INFO]: Blacklisting learning of rftoolsdim:empty_biome_dimlet
[18:38:26] [Worker-Main-9/INFO]: Blacklisting learning of rftoolsdim:empty_biome_controller_dimlet
[18:38:26] [Worker-Main-9/INFO]: Blacklisting learning of rftoolsdim:empty_biome_controller_dimlet
[18:38:26] [Worker-Main-9/INFO]: Blacklisting learning of rftoolsdim:empty_block_dimlet
[18:38:26] [Worker-Main-9/INFO]: Blacklisting learning of rftoolsdim:empty_fluid_dimlet
[18:38:26] [Worker-Main-9/INFO]: Blacklisting learning of rftoolsdim:empty_time_dimlet
[18:38:26] [Worker-Main-9/INFO]: Blacklisting learning of rftoolsdim:terrain_dimlet
[18:38:26] [Worker-Main-9/INFO]: Blacklisting learning of rftoolsdim:attribute_dimlet
[18:38:26] [Worker-Main-9/INFO]: Blacklisting learning of rftoolsdim:feature_dimlet
[18:38:26] [Worker-Main-9/INFO]: Blacklisting learning of rftoolsdim:biome_dimlet
[18:38:26] [Worker-Main-9/INFO]: Blacklisting learning of rftoolsdim:biome_controller_dimlet
[18:38:26] [Worker-Main-9/INFO]: Blacklisting learning of rftoolsdim:block_dimlet
[18:38:26] [Worker-Main-9/INFO]: Blacklisting learning of rftoolsdim:fluid_dimlet
[18:38:26] [Worker-Main-9/INFO]: Blacklisting learning of rftoolsdim:time_dimlet
[18:38:26] [Worker-Main-9/INFO]: Blacklisting learning of rftoolsdim:digit_dimlet
[18:38:26] [Worker-Main-9/INFO]: Blacklisting learning of rftoolsdim:admin_dimlet
[18:38:26] [Worker-Main-9/INFO]: Blacklisting learning of all items from cyberware
[18:38:26] [Worker-Main-9/INFO]: C:\Users\Jeremy\curseforge\minecraft\Instances\All the Mods 6 - ATM6 - 1.16.5\woot\loot.json
[18:38:26] [Worker-Main-9/INFO]: Added integer override of minecraft:ender_dragon:PERK_MASS_2_COUNT -> 3
[18:38:26] [Worker-Main-9/INFO]: Added integer override of minecraft:wither:PERK_MASS_2_COUNT -> 3
[18:38:26] [Worker-Main-9/INFO]: Added integer override of botania:doppleganger:PERK_MASS_2_COUNT -> 3
[18:38:26] [Worker-Main-9/INFO]: Added integer override of iceandfire:ice_dragon:PERK_MASS_2_COUNT -> 3
[18:38:26] [Worker-Main-9/INFO]: Added integer override of iceandfire:fire_dragon:PERK_MASS_2_COUNT -> 3
[18:38:26] [Worker-Main-9/INFO]: Added integer override of iceandfire:lightning_dragon:PERK_MASS_2_COUNT -> 3
[18:38:26] [Worker-Main-9/INFO]: Added integer override of minecraft:ender_dragon:HEALTH -> 500
[18:38:26] [Worker-Main-9/INFO]: Added integer override of botania:doppleganger:HEALTH -> 250
[18:38:26] [Worker-Main-9/INFO]: Added integer override of iceandfire:ice_dragon:HEALTH -> 500
[18:38:26] [Worker-Main-9/INFO]: Added integer override of iceandfire:fire_dragon:HEALTH -> 500
[18:38:26] [Worker-Main-9/INFO]: Added integer override of iceandfire:lightning_dragon:HEALTH -> 500
[18:38:26] [Worker-Main-9/INFO]: Added integer override of minecraft:iron_golem:XP -> 20
[18:38:26] [Worker-Main-9/INFO]: Added integer override of minecraft:bat:XP -> 1
[18:38:26] [Worker-Main-9/INFO]: Added integer override of minecraft:snow_golem:XP -> 1
[18:38:26] [Worker-Main-9/INFO]: Added integer override of minecraft:villager:XP -> 2
[18:38:26] [Worker-Main-9/INFO]: Added integer override of minecraft:wandering_villager:XP -> 2
[18:38:26] [Worker-Main-9/INFO]: Added integer override of minecraft:ender_dragon:XP -> 500
[18:38:26] [Worker-Main-9/INFO]: Added integer override of botania:doppleganger:XP -> 1
[18:38:26] [Worker-Main-9/INFO]: Added integer override of iceandfire:ice_dragon:XP -> 1
[18:38:26] [Worker-Main-9/INFO]: Added integer override of iceandfire:fire_dragon:XP -> 1
[18:38:26] [Worker-Main-9/INFO]: Added integer override of iceandfire:lightning_dragon:XP -> 1
[18:38:26] [Worker-Main-9/INFO]: Added integer override of minecraft:ender_dragon:PERK_MASS_3_COUNT -> 4
[18:38:26] [Worker-Main-9/INFO]: Added integer override of minecraft:wither:PERK_MASS_3_COUNT -> 4
[18:38:26] [Worker-Main-9/INFO]: Added integer override of botania:doppleganger:PERK_MASS_3_COUNT -> 4
[18:38:26] [Worker-Main-9/INFO]: Added integer override of iceandfire:ice_dragon:PERK_MASS_3_COUNT -> 4
[18:38:26] [Worker-Main-9/INFO]: Added integer override of iceandfire:fire_dragon:PERK_MASS_3_COUNT -> 4
[18:38:26] [Worker-Main-9/INFO]: Added integer override of iceandfire:lightning_dragon:PERK_MASS_3_COUNT -> 4
[18:38:26] [Worker-Main-9/INFO]: Added integer override of minecraft:wither:SPAWN_TICKS -> 1200
[18:38:26] [Worker-Main-9/INFO]: Added integer override of minecraft:ender_dragon:SPAWN_TICKS -> 12000
[18:38:26] [Worker-Main-9/INFO]: Added integer override of botania:doppleganger:SPAWN_TICKS -> 12000
[18:38:26] [Worker-Main-9/INFO]: Added integer override of iceandfire:ice_dragon:SPAWN_TICKS -> 12000
[18:38:26] [Worker-Main-9/INFO]: Added integer override of iceandfire:fire_dragon:SPAWN_TICKS -> 12000
[18:38:26] [Worker-Main-9/INFO]: Added integer override of iceandfire:lightning_dragon:SPAWN_TICKS -> 12000
[18:38:26] [Worker-Main-9/INFO]: Added integer override of minecraft:wither_skeleton:TIER -> 4
[18:38:26] [Worker-Main-9/INFO]: Added integer override of minecraft:villager:TIER -> 4
[18:38:26] [Worker-Main-9/INFO]: Added integer override of minecraft:magma_cube:TIER -> 3
[18:38:26] [Worker-Main-9/INFO]: Added integer override of minecraft:enderman:TIER -> 4
[18:38:26] [Worker-Main-9/INFO]: Added integer override of minecraft:villager_golem:TIER -> 4
[18:38:26] [Worker-Main-9/INFO]: Added integer override of minecraft:guardian:TIER -> 4
[18:38:26] [Worker-Main-9/INFO]: Added integer override of minecraft:blaze:TIER -> 3
[18:38:26] [Worker-Main-9/INFO]: Added integer override of minecraft:witch:TIER -> 3
[18:38:26] [Worker-Main-9/INFO]: Added integer override of minecraft:ghast:TIER -> 3
[18:38:26] [Worker-Main-9/INFO]: Added integer override of minecraft:zombie_pigman:TIER -> 3
[18:38:26] [Worker-Main-9/INFO]: Added integer override of minecraft:ender_dragon:TIER -> 5
[18:38:26] [Worker-Main-9/INFO]: Added integer override of minecraft:wither:TIER -> 5
[18:38:26] [Worker-Main-9/INFO]: Added integer override of botania:doppleganger:TIER -> 5
[18:38:26] [Worker-Main-9/INFO]: Added integer override of iceandfire:ice_dragon:TIER -> 5
[18:38:26] [Worker-Main-9/INFO]: Added integer override of iceandfire:fire_dragon:TIER -> 5
[18:38:26] [Worker-Main-9/INFO]: Added integer override of iceandfire:lightning_dragon:TIER -> 5
[18:38:26] [Worker-Main-9/INFO]: Added integer override of minecraft:ender_dragon:PERK_MASS_1_COUNT -> 2
[18:38:26] [Worker-Main-9/INFO]: Added integer override of minecraft:wither:PERK_MASS_1_COUNT -> 2
[18:38:26] [Worker-Main-9/INFO]: Added integer override of botania:doppleganger:PERK_MASS_1_COUNT -> 2
[18:38:26] [Worker-Main-9/INFO]: Added integer override of iceandfire:ice_dragon:PERK_MASS_1_COUNT -> 2
[18:38:26] [Worker-Main-9/INFO]: Added integer override of iceandfire:fire_dragon:PERK_MASS_1_COUNT -> 2
[18:38:26] [Worker-Main-9/INFO]: Added integer override of iceandfire:lightning_dragon:PERK_MASS_1_COUNT -> 2
[18:38:26] [Worker-Main-9/INFO]: SkullGenerator: minecraft:skeleton -> 1 skeleton_skull
[18:38:26] [Worker-Main-9/INFO]: SkullGenerator: minecraft:wither_skeleton -> 1 wither_skeleton_skull
[18:38:26] [Worker-Main-9/INFO]: SkullGenerator: minecraft:zombie -> 1 zombie_head
[18:38:26] [Worker-Main-9/INFO]: SkullGenerator: minecraft:creeper -> 1 creeper_head
[18:38:26] [Worker-Main-4/INFO]: Version 10.1.1 initializing...
[18:38:26] [Worker-Main-9/INFO]: Registering recipe condition processor ...
[18:38:26] [Worker-Main-9/INFO]: PneumaticCraft: Repressurized is loading!
[18:38:26] [Worker-Main-4/INFO]: Fake player readout: UUID = 46e82cd0-d480-3d48-800a-77431ede078e, name = [Mekanism]
[18:38:26] [Worker-Main-4/INFO]: Loading complete.
[18:38:26] [Worker-Main-4/INFO]: Mod loaded.
[18:38:26] [Worker-Main-4/INFO]: Loading MythicBotany
[18:38:26] [Worker-Main-4/INFO]: Shields up!
[18:38:26] [Worker-Main-4/INFO]: Registered packet handler.
[18:38:26] [Worker-Main-9/INFO]: Registered packet handler.
[18:38:26] [Worker-Main-9/INFO]: BYG: "Common Setup" Event Complete!
[18:38:26] [Worker-Main-4/INFO]: Found preferred client: ANY
[18:38:26] [Worker-Main-9/INFO]: ManaGear Installed -  Please ensure you downloaded from CurseForge!
[18:38:26] [Worker-Main-9/INFO]: Connectivity initialized
[18:38:26] [Worker-Main-9/INFO]: Registering recipe condition processor ...
[18:38:26] [Worker-Main-4/INFO]: Enabling support for Lost Cities
[18:38:26] [Worker-Main-4/INFO]: Enabling support for Lost Cities
[18:38:26] [Worker-Main-9/INFO]: Common setup
[18:38:26] [Worker-Main-4/INFO]: Reading rules from spawn.json
[18:38:26] [Worker-Main-4/INFO]: Reading rules from summonaid.json
[18:38:26] [Worker-Main-4/INFO]: Reading rules from potentialspawn.json
[18:38:26] [Worker-Main-4/INFO]: Reading rules from loot.json
[18:38:26] [Worker-Main-4/INFO]: Reading rules from experience.json
[18:38:26] [Worker-Main-4/INFO]: Reading rules from phases.json
[18:38:26] [Worker-Main-4/INFO]: Reading rules from spawner.json
[18:38:26] [Worker-Main-4/INFO]: Registering 3 command argument types.
[18:38:26] [Worker-Main-4/INFO]: Registering 13 loot conditions.
[18:38:26] [Worker-Main-9/INFO]: Loaded 'Mekanism Generators' module.
[18:38:26] [Worker-Main-4/INFO]: Generation Potion Mixes
[18:38:26] [Worker-Main-4/INFO]: Generating Potion Recipe for: resourcefulbees:calming
[18:38:26] [Worker-Main-4/INFO]: Generating Potion Recipe for: resourcefulbees:long_calming
[18:38:26] [Worker-Main-4/INFO]: Loaded 'Mekanism: Additions' module.
[18:38:26] [Worker-Main-9/INFO]: [com.hollingsworth.arsnouveau.common.capability.ManaCapability:register:62]: Finished Registering ManaCapability
[18:38:26] [Worker-Main-9/INFO]: [com.hollingsworth.arsnouveau.api.familiar.FamiliarCap:register:97]: Finished Registering FamiliarCap
[18:38:26] [Worker-Main-9/INFO]: [com.hollingsworth.arsnouveau.common.network.Networking:registerMessages:27]: Registering packets!!
[18:38:26] [Worker-Main-4/INFO]: HELLO FROM PREINIT
[18:38:26] [Worker-Main-4/INFO]: DIRT BLOCK >> minecraft:dirt
[18:38:26] [Worker-Main-4/INFO]: Creating standard profiles into 'config/lostcities/profiles'
[18:38:26] [Worker-Main-4/INFO]: Reading existing profiles from 'config/lostcities/profiles'
[18:38:26] [Worker-Main-9/INFO]: Loaded 'Mekanism: Tools' module.
[18:38:27] [Worker-Main-9/INFO]: [scala.Console$:println:268]: Loading ProjectRed compatibility: ComputerCraft
[18:38:27] [AstralSorcery Patreon Effect Loader/WARN]: Skipped 1 patreon effects during loading due to malformed data!
[18:38:27] [AstralSorcery Patreon Effect Loader/INFO]: Patreon effect loading finished.
[18:38:27] [Worker-Main-9/INFO]: Hello
[18:38:27] [Worker-Main-4/INFO]: Post Initialization ( started )
[18:38:27] [Worker-Main-4/INFO]: Post Initialization ( ended after 13ms )
[18:38:27] [Worker-Main-6/INFO]: Common Setup
[18:38:27] [Worker-Main-6/INFO]: Whitelisted Dimensions:
[18:38:27] [Worker-Main-6/INFO]: minecraft:overworld
[18:38:27] [Worker-Main-6/INFO]: Loading TravelAnchors
[18:38:27] [Worker-Main-9/INFO]: XNet Detected RFTools Control: enabling support
[18:38:27] [Worker-Main-9/INFO]: RFTools Storage Detected XNet: enabling support
[18:38:27] [Worker-Main-9/INFO]: Sound Device Options is starting
[18:38:27] [Immersive Engineering Contributors Thread/INFO]: Attempting to download special revolvers from GitHub
[18:38:27] [Worker-Main-9/INFO]: M&A -> Network Messages Registered
[18:38:27] [Worker-Main-9/INFO]: Mana And Artifice >> Registered loot functions
[18:38:27] [Worker-Main-6/WARN]: Called deprecated GlobalEntityTypeAttributes#put for quark:crab, use EntityAttributeCreationEvent instead.
[18:38:27] [Worker-Main-6/WARN]: Called deprecated GlobalEntityTypeAttributes#put for quark:wrapped, use EntityAttributeCreationEvent instead.
[18:38:27] [Worker-Main-6/WARN]: Called deprecated GlobalEntityTypeAttributes#put for quark:foxhound, use EntityAttributeCreationEvent instead.
[18:38:27] [Worker-Main-6/WARN]: Called deprecated GlobalEntityTypeAttributes#put for quark:shiba, use EntityAttributeCreationEvent instead.
[18:38:27] [Worker-Main-6/WARN]: Called deprecated GlobalEntityTypeAttributes#put for quark:stoneling, use EntityAttributeCreationEvent instead.
[18:38:27] [Worker-Main-6/WARN]: Called deprecated GlobalEntityTypeAttributes#put for quark:forgotten, use EntityAttributeCreationEvent instead.
[18:38:27] [Worker-Main-6/WARN]: Called deprecated GlobalEntityTypeAttributes#put for quark:frog, use EntityAttributeCreationEvent instead.
[18:38:27] [Worker-Main-9/INFO]: M&A -> Capabilities Registered
[18:38:27] [Worker-Main-9/INFO]: M&A -> Flower Pots Registered
[18:38:27] [Worker-Main-6/WARN]: Called deprecated GlobalEntityTypeAttributes#put for quark:leash_knot_fake, use EntityAttributeCreationEvent instead.
[18:38:27] [Worker-Main-6/WARN]: Called deprecated GlobalEntityTypeAttributes#put for quark:wraith, use EntityAttributeCreationEvent instead.
[18:38:27] [Worker-Main-6/WARN]: Called deprecated GlobalEntityTypeAttributes#put for quark:toretoise, use EntityAttributeCreationEvent instead.
[18:38:27] [Worker-Main-4/INFO]: New compacting rule 4 clay_ball = 1 clay
[18:38:27] [Worker-Main-4/INFO]: New compacting rule 4 snowball = 1 snow_block
[18:38:27] [Worker-Main-4/INFO]: New compacting rule 4 glowstone_dust = 1 glowstone
[18:38:27] [Worker-Main-4/INFO]: New compacting rule 4 brick = 1 bricks
[18:38:27] [Worker-Main-4/INFO]: New compacting rule 4 nether_brick = 1 nether_bricks
[18:38:27] [Worker-Main-4/INFO]: New compacting rule 9 nether_wart = 1 nether_wart_block
[18:38:27] [Worker-Main-4/INFO]: New compacting rule 4 quartz = 1 quartz_block
[18:38:27] [Worker-Main-4/INFO]: New compacting rule 9 melon_slice = 1 melon
[18:38:27] [Worker-Main-4/INFO]: New compacting rule 4 sand = 1 sandstone
[18:38:27] [Worker-Main-4/INFO]: New compacting rule 4 red_sand = 1 red_sandstone
[18:38:27] [Worker-Main-4/INFO]: New compacting rule 4 clay_ball = 1 clay
[18:38:27] [Worker-Main-4/INFO]: New compacting rule 2 uraninite_raw = 1 uraninite_raw_dense
[18:38:27] [Worker-Main-4/INFO]: New compacting rule 2 uraninite_raw_poor = 1 uraninite_raw
[18:38:27] [Worker-Main-4/INFO]: New compacting rule 9 sand_1 = 1 sand_2
[18:38:27] [Worker-Main-4/INFO]: New compacting rule 9 sand = 1 sand_1
[18:38:27] [Worker-Main-9/INFO]: Registering recipe condition processor ...
[18:38:27] [Worker-Main-9/INFO]: Modular Routers is loading!
[18:38:27] [Worker-Main-9/WARN]: Called deprecated GlobalEntityTypeAttributes#put for forbidden_arcanus:pixie, use EntityAttributeCreationEvent instead.
[18:38:27] [Worker-Main-9/INFO]: [OptiFine] Multitexture: false
[18:38:27] [Worker-Main-6/INFO]: [OptiFine] Multitexture: false
[18:38:28] [Worker-Main-4/INFO]: [OptiFine] Multitexture: false
[18:38:30] [Worker-Main-6/INFO]: [OptiFine] Scaled too small texture: astralsorcery:mob_effect/bleed, 1 -> 8
[18:38:30] [Worker-Main-6/INFO]: [OptiFine] Scaled too small texture: astralsorcery:mob_effect/cheat_death, 1 -> 8
[18:38:30] [Worker-Main-6/INFO]: [OptiFine] Scaled too small texture: astralsorcery:mob_effect/drop_modifier, 1 -> 8
[18:38:30] [main/WARN]: Successfully loaded integration for mekanismgenerators
[18:38:30] [main/WARN]: Successfully loaded integration for mekanism
[18:38:30] [main/WARN]: Successfully loaded integration for botania
[18:38:30] [main/WARN]: Successfully loaded integration for immersiveengineering
[18:38:30] [main/WARN]: Successfully loaded integration for integrateddynamics
[18:38:30] [main/WARN]: Successfully loaded integration for storagedrawers
[18:38:30] [main/WARN]: Successfully loaded integration for create
[18:38:30] [main/WARN]: Failed to load integration for draconicevolution
[18:38:30] [main/INFO]: [elucent.eidolon.Registry:addBrewingRecipes:402]: calling addBrewingRecipes
[18:38:30] [main/WARN]: Called deprecated GlobalEntityTypeAttributes#put for eidolon:zombie_brute, use EntityAttributeCreationEvent instead.
[18:38:30] [main/WARN]: Called deprecated GlobalEntityTypeAttributes#put for eidolon:wraith, use EntityAttributeCreationEvent instead.
[18:38:30] [main/WARN]: Called deprecated GlobalEntityTypeAttributes#put for eidolon:necromancer, use EntityAttributeCreationEvent instead.
[18:38:31] [main/INFO]: Registering Structure Piece Types
[18:38:31] [main/INFO]: M&A -> Recipe Types Registered
[18:38:31] [Worker-Main-6/INFO]: Skipping TESR for tile null as it is not registered.
[18:38:31] [Worker-Main-6/INFO]: Got game settings net.minecraft.client.GameSettings@b96f582
[18:38:31] [Worker-Main-3/INFO]: Executing phase CLIENT_SETUP for plugin class ImmersiveEngineeringPlugin
[18:38:31] [Worker-Main-3/INFO]: Executing phase CLIENT_SETUP for plugin class FTBChunksPlugin
[18:38:31] [Worker-Main-3/INFO]: Executing phase CLIENT_SETUP for plugin class AstralSorceryPlugin
[18:38:31] [Worker-Main-3/INFO]: Executing phase CLIENT_SETUP for plugin class CuriosPlugin
[18:38:31] [Worker-Main-4/INFO]: Initialized HolidayManager.
[18:38:31] [Worker-Main-10/INFO]: BYG: "Client Setup" Event Complete!
[18:38:31] [Worker-Main-9/INFO]: Optifine found. Enabling compat.
[18:38:31] [Worker-Main-6/INFO]: Binding Renderer for Redstone Panel tile entity.
[18:38:31] [Worker-Main-8/INFO]: Client setup
[18:38:31] [Placebo Patreon Wing Loader/INFO]: Loading patreon wing data...
[18:38:31] [Placebo Patreon Trail Loader/INFO]: Loading patreon trails data...
[18:38:31] [Placebo Patreon Trail Loader/INFO]: Loaded 12 patreon trails.
[18:38:31] [Placebo Patreon Wing Loader/INFO]: Loaded 10 patreon wings.
[18:38:31] [Worker-Main-6/INFO]: Got game settings net.minecraft.client.GameSettings@b96f582
[18:38:31] [Worker-Main-8/INFO]: JEI loading delay setup
[18:38:31] [Worker-Main-4/WARN]: Could not load /assets/iceandfire/models/tabula/firedragon/firedragon_Swimming.tbl: in is null
[18:38:32] [Worker-Main-4/WARN]: Could not load /assets/iceandfire/models/tabula/firedragon/firedragon_Swim5.tbl: in is null
[18:38:32] [Worker-Main-10/INFO]: M&A -> Gui Screens Registered
[18:38:32] [Worker-Main-10/INFO]: M&A -> Keybindings Registered
[18:38:32] [Worker-Main-10/INFO]: M&A -> Tile Entity Renderers Registered
[18:38:32] [Worker-Main-10/INFO]: M&A -> Block Render Layers Set
[18:38:32] [Worker-Main-8/INFO]: [com.mrh0.createaddition.index.CAEntities:registerRenderers:36]: REGCLIENT
[18:38:32] [Worker-Main-10/INFO]: M&A -> Entity Renderers Registered
[18:38:32] [Worker-Main-5/INFO]: [OptiFine] Scaled too small texture: tinyredstone:block/redstone_torch_top_off, 2 -> 8
[18:38:32] [Worker-Main-5/INFO]: [OptiFine] Scaled too small texture: tinyredstone:block/redstone_torch, 2 -> 8
[18:38:32] [Worker-Main-5/INFO]: [OptiFine] Scaled too small texture: tinyredstone:block/lever, 2 -> 8
[18:38:32] [Worker-Main-5/INFO]: [OptiFine] Scaled too small texture: tinyredstone:block/redstone_torch_top, 2 -> 8
[18:38:32] [Worker-Main-5/INFO]: [OptiFine] Scaled too small texture: tinyredstone:block/redstone_torch_off, 2 -> 8
[18:38:32] [Worker-Main-5/INFO]: [OptiFine] Scaled too small texture: moreminecarts:block/organic_glass_pane_top, 2 -> 8
[18:38:32] [Worker-Main-5/INFO]: [OptiFine] Scaled too small texture: tinyredstone:block/lever_top, 2 -> 8
[18:38:33] [main/INFO]: Found KubeJS lang, reading!
[18:38:33] [main/INFO]: Wrote 0 KubeJS lang keys
[18:38:39] [Worker-Main-5/INFO]: [OptiFine] Multitexture: false
[18:38:40] [Worker-Main-5/INFO]: [OptiFine] Multitexture: false
[18:38:40] [Worker-Main-5/INFO]: [OptiFine] Multitexture: false
[18:38:40] [Worker-Main-5/INFO]: [OptiFine] Multitexture: false
[18:38:41] [Worker-Main-5/INFO]: [OptiFine] Multitexture: false
[18:38:41] [Worker-Main-5/INFO]: [OptiFine] Multitexture: false
[18:38:41] [Worker-Main-5/INFO]: [OptiFine] Multitexture: false
[18:38:42] [main/INFO]: Loaded 10 buttons from resources.
[18:38:43] [main/INFO]: Loading context 'flywheel:context/crumbling'
[18:38:43] [main/INFO]: Loading context 'flywheel:context/world'
[18:38:43] [main/INFO]: Loading context 'create:context/contraption'
[18:38:43] [main/INFO]: Loading context 'create:context/contraption'
[18:38:43] [main/INFO]: Loaded all shader programs.
[18:38:43] [main/INFO]: [AssetLibrary] Refreshing and Invalidating Resources
[18:38:43] [main/INFO]: [AssetLibrary] Successfully reloaded library.
[18:38:45] [main/INFO]: [stepsword.mahoutsukai.render.shader.ShaderHelper:shadersOn:146]: config found
[18:38:45] [main/INFO]: [stepsword.mahoutsukai.render.shader.ShaderHelper:loadShaders:84]: Mahou Shaders disabled
[18:38:45] [Worker-Main-10/INFO]: Hello world from the MDK
[18:38:45] [Worker-Main-10/INFO]: Got IMC [Hello world]
[18:38:45] [Worker-Main-10/INFO]: refinedstorage has registered com.refinedmods.refinedstorage.container.GridContainer for CraftingTweaks
[18:38:45] [Worker-Main-4/INFO]: Enabling support The One Probe
[18:38:45] [Worker-Main-4/INFO]: Enabled support for The One Probe
[18:38:45] [Worker-Main-10/INFO]: craftingstation has registered com.tfar.craftingstation.CraftingStationContainer for CraftingTweaks
[18:38:45] [Worker-Main-4/INFO]: Enabled support for The One Probe
[18:38:45] [Worker-Main-4/INFO]: Enabled support for The One Probe
[18:38:45] [Worker-Main-4/INFO]: Enabled support for The One Probe
[18:38:45] [Worker-Main-4/INFO]: Integration TOP
[18:38:45] [Worker-Main-7/INFO]: Added coolant fluid: minecraft:water, with coldness of: 1 per mb
[18:38:45] [Worker-Main-7/INFO]: Added block: minecraft:lava, with heat of: 1000
[18:38:45] [Worker-Main-7/INFO]: Added block: minecraft:magma_block, with heat of: 800
[18:38:45] [Worker-Main-7/INFO]: Added block: powah:blazing_crystal_block, with heat of: 2800
[18:38:45] [Worker-Main-7/INFO]: Added fluid: minecraft:lava, with heat of: 10000 per 100 mb
[18:38:45] [Worker-Main-6/INFO]: Applying mega torch entity block list overrides...
[18:38:45] [Worker-Main-6/INFO]: Applying dread lamp entity block list overrides...
[18:38:45] [Worker-Main-4/INFO]: Loaded TerraForged version 0.2.16-BETA-2
[18:38:45] [Worker-Main-10/INFO]: Registering Default Bee Traits...
[18:38:45] [Worker-Main-7/INFO]: Creating config GUI factories...
[18:38:45] [Worker-Main-9/INFO]: [com.mrh0.buildersaddition.BuildersAddition:postInit:80]: Builders Addition Initialized!
[18:38:45] [Worker-Main-10/INFO]: Registering Custom Traits...
[18:38:45] [Worker-Main-10/ERROR]: Trait is already registered or registration is closed: starry
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod betterdungeons. Found 0 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod quarryplus. Found 1 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod lazierae2. Found 0 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod integratedterminals. Found 1 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod modnametooltip. Found 1 client config(s) and 0 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod thermal. Found 1 client config(s) and 0 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod rftoolsbase. Found 0 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod ironjetpacks. Found 1 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod forgeendertech. Found 1 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod xnet. Found 1 client config(s) and 0 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod powah. Found 0 client config(s) and 15 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod cabletiers. Found 0 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod jumbofurnace. Found 0 client config(s) and 0 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod rangedpumps. Found 0 client config(s) and 0 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod wstweaks. Found 0 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod xreliquary. Found 1 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod universalgrid. Found 0 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod waterstrainer. Found 0 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod dynview. Found 0 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod jeresources. Found 0 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod tmechworks. Found 0 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod mysticalagradditions. Found 0 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod shetiphiancore. Found 1 client config(s) and 0 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod refinedstorage. Found 1 client config(s) and 0 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod advancementplaques. Found 0 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod alltheores. Found 0 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod industrialforegoing. Found 0 client config(s) and 5 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod torchmaster. Found 0 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod repurposed_structures. Found 0 client config(s) and 18 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod biomesoplenty. Found 1 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod ironfurnaces. Found 1 client config(s) and 0 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod silentgear. Found 1 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod botania. Found 1 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod portality. Found 0 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod curios. Found 1 client config(s) and 0 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod corail_woodcutter. Found 0 client config(s) and 0 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod topaddons. Found 1 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod framedblocks. Found 1 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod rftoolsdim. Found 1 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod constructionwand. Found 1 client config(s) and 0 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod naturesaura. Found 0 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod cfm. Found 1 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod globalxp. Found 1 client config(s) and 0 common config(s)
[18:38:45] [Worker-Main-4/WARN]: FMLLoadCompleteEvent
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod adchimneys. Found 1 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod fastleafdecay. Found 0 client config(s) and 0 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod bettermineshafts. Found 0 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod clienttweaks. Found 1 client config(s) and 0 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod nomowanderer. Found 0 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod bagofyurting. Found 1 client config(s) and 0 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod woot. Found 1 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod jei. Found 1 client config(s) and 0 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod attributefix. Found 0 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod mekanism. Found 1 client config(s) and 0 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod upgrade_aquatic. Found 1 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod allthecompressed. Found 0 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod invtweaks. Found 1 client config(s) and 0 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod naturescompass. Found 1 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod compactmachines. Found 0 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod botanypots. Found 1 client config(s) and 0 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod engineerstools. Found 0 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod farmingforblockheads. Found 1 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod cofh_core. Found 1 client config(s) and 0 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod pneumaticcraft. Found 1 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod iceandfire. Found 1 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod ars_nouveau. Found 0 client config(s) and 73 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod rftoolspower. Found 1 client config(s) and 0 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod extradisks. Found 0 client config(s) and 0 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod immersivepetroleum. Found 1 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Ignoring Forge's client config since OptiFine was detected
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod forge. Found 0 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod integratedcrafting. Found 0 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod mythicbotany. Found 1 client config(s) and 0 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod logprot. Found 0 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod theoneprobe. Found 1 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod immersiveengineering. Found 1 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod psi. Found 1 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod usefulrailroads. Found 0 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod creativeapiary. Found 0 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod pamhc2crops. Found 0 client config(s) and 0 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod ding. Found 1 client config(s) and 0 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod rftoolsbuilder. Found 1 client config(s) and 0 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod jeiintegration. Found 1 client config(s) and 0 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod pipez. Found 1 client config(s) and 0 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod flywheel. Found 1 client config(s) and 0 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod mantle. Found 1 client config(s) and 0 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod integrateddynamics. Found 1 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod ftbbackups. Found 0 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod integratedterminalscompat. Found 0 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod structurize. Found 1 client config(s) and 0 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod creativecrafter. Found 1 client config(s) and 0 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod pickletweaks. Found 1 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod appleskin. Found 1 client config(s) and 0 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod lootr. Found 0 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod allthetweaks. Found 0 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod aquaculture. Found 0 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod extremesoundmuffler. Found 1 client config(s) and 0 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod cosmeticarmorreworked. Found 1 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod defaultoptions. Found 0 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod xpbook. Found 0 client config(s) and 0 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod rsrequestify. Found 0 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod cyclopscore. Found 1 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod astralsorcery. Found 1 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod advancedperipherals. Found 0 client config(s) and 4 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod aiotbotania. Found 1 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod tinyredstone. Found 1 client config(s) and 0 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod eidolon. Found 1 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod jecalculation. Found 0 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod findme. Found 1 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod rsgauges. Found 0 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod cookingforblockheads. Found 1 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod citadel. Found 0 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod dankstorage. Found 1 client config(s) and 0 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod moreminecarts. Found 0 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod culinaryconstruct. Found 0 client config(s) and 0 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod sophisticatedbackpacks. Found 1 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod jeed. Found 1 client config(s) and 0 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod lightingwand. Found 0 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod mekanismgenerators. Found 0 client config(s) and 0 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod xnetgases. Found 0 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod dummmmmmy. Found 1 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod twilightforest. Found 1 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod rsinfinitybooster. Found 0 client config(s) and 0 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod equipmentcompare. Found 0 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod chocolate. Found 0 client config(s) and 0 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod resourcefulbees. Found 1 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod usefulbackpacks. Found 0 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod commoncapabilities. Found 0 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod endertanks. Found 1 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod crashutilities. Found 0 client config(s) and 0 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod getittogetherdrops. Found 0 client config(s) and 0 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod mekanismadditions. Found 1 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod patchouli. Found 1 client config(s) and 0 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod rftoolsstorage. Found 1 client config(s) and 0 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod collective. Found 0 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod rftoolscontrol. Found 1 client config(s) and 0 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod tiab. Found 0 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod integratedtunnels. Found 0 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod elevatorid. Found 0 client config(s) and 0 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod lostcities. Found 1 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod betterstrongholds. Found 0 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod starterkit. Found 0 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod mekanismtools. Found 1 client config(s) and 0 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod computercraft. Found 1 client config(s) and 0 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod tramplestopper. Found 0 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod bwncr. Found 0 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod smallships. Found 0 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod betteradvancements. Found 1 client config(s) and 0 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod cucumber. Found 1 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod trashslot. Found 1 client config(s) and 0 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod pamhc2trees. Found 0 client config(s) and 0 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod craftingstation. Found 0 client config(s) and 0 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod elementalcraft. Found 1 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod platforms. Found 1 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod abnormals_core. Found 1 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod ponderjs. Found 1 client config(s) and 0 common config(s)
[18:38:45] [Phosphophyllite Registry Worker/INFO]: Thread stopped
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod ensorcellation. Found 0 client config(s) and 0 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod waystones. Found 1 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod zycraft. Found 1 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod appliedenergistics2. Found 1 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod comforts. Found 0 client config(s) and 0 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod artifacts. Found 1 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod configured. Found 1 client config(s) and 0 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod dimstorage. Found 0 client config(s) and 0 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod demagnetize. Found 0 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod travel_anchors. Found 1 client config(s) and 0 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod mcjtylib. Found 1 client config(s) and 0 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod explorerscompass. Found 1 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod mahoutsukai. Found 1 client config(s) and 0 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod integrateddynamicscompat. Found 0 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod toastcontrol. Found 0 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod mininggadgets. Found 1 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod akashictome. Found 0 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod bloodmagic. Found 1 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod scuba_gear. Found 0 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod immersiveposts. Found 0 client config(s) and 0 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod mysticalagriculture. Found 1 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod craftingtweaks. Found 1 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod tconstruct. Found 1 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod rftoolsutility. Found 1 client config(s) and 0 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod enchdesc. Found 1 client config(s) and 0 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod titanium. Found 0 client config(s) and 2 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod toolbelt. Found 1 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod mana-and-artifice. Found 1 client config(s) and 0 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod exchangers. Found 0 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod ctiers. Found 0 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod forbidden_arcanus. Found 1 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod archers_paradox. Found 1 client config(s) and 0 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod omgourd. Found 1 client config(s) and 0 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod legendarytooltips. Found 0 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod creativewirelesstransmitter. Found 1 client config(s) and 0 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod fluxnetworks. Found 1 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod storagedrawers. Found 1 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod enderchests. Found 1 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod minecolonies. Found 1 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod pylons. Found 0 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod engineersdecor. Found 1 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod solcarrot. Found 1 client config(s) and 0 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod modularrouters. Found 1 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod refinedstorageaddons. Found 0 client config(s) and 0 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod botanicalmachinery. Found 1 client config(s) and 0 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod overloadedarmorbar. Found 1 client config(s) and 0 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod valhelsia_core. Found 1 client config(s) and 0 common config(s)
[18:38:45] [Worker-Main-7/INFO]: Registering config factory for mod morphtool. Found 0 client config(s) and 1 common config(s)
[18:38:45] [Worker-Main-7/INFO]: [com.mrh0.createaddition.CreateAddition:postInit:141]: Create Crafts & Addition Initialized!
[18:38:45] [Worker-Main-4/WARN]: Register mappings
[18:38:45] [Worker-Main-6/INFO]: M&A API initialized, it is now useable
[18:38:46] [main/INFO]: BYG: Compostible Blocks Added!
[18:38:46] [main/INFO]: BYG: Added Hoeable Blocks!
[18:38:46] [main/INFO]: BYG: Added Flammables!
[18:38:46] [main/INFO]: BYG: Added strippable Blocks...
[18:38:46] [main/INFO]: Initializing Psi shaders!
[18:39:09] [main/ERROR]: java.io.FileNotFoundException: Source 'C:\Users\Jeremy\curseforge\minecraft\Instances\All the Mods 6 - ATM6 - 1.16.5\config\defaultoptions\servers.dat' does not exist
[18:39:12] [main/WARN]: Missing sound for event: twilightforest:entity.twilightforest.termite.twilightforest.ambient
[18:39:12] [main/WARN]: Missing sound for event: twilightforest:entity.twilightforest.termite.twilightforest.death
[18:39:12] [main/WARN]: Missing sound for event: twilightforest:entity.twilightforest.termite.twilightforest.hurt
[18:39:12] [main/WARN]: Missing sound for event: twilightforest:entity.twilightforest.termite.twilightforest.step
[18:39:12] [main/INFO]: SoundManager loading on device null
[18:39:12] [main/INFO]: OpenAL initialized.
[18:39:12] [main/INFO]: Sound engine started
[18:39:12] [main/INFO]: [Shaders] Allocate texture map normal: 256x128, mipmaps: 0
[18:39:12] [main/INFO]: [Shaders] Allocate texture map specular: 256x128, mipmaps: 0
[18:39:12] [main/INFO]: [OptiFine] Animated sprites: 2
[18:39:12] [main/INFO]: [Shaders] Allocate texture map normal: 256x256, mipmaps: 0
[18:39:12] [main/INFO]: [Shaders] Allocate texture map specular: 256x256, mipmaps: 0
[18:39:12] [main/INFO]: [OptiFine] Animated sprites: 2
[18:39:12] [main/INFO]: [Shaders] Allocate texture map normal: 128x128, mipmaps: 0
[18:39:12] [main/INFO]: [Shaders] Allocate texture map specular: 128x128, mipmaps: 0
[18:39:12] [main/INFO]: [OptiFine] Animated sprites: 4
[18:39:12] [main/INFO]: Endimation Data Manager has loaded 0 Endimations
[18:39:12] [main/INFO]: [Shaders] Allocate texture map normal: 1024x2048, mipmaps: 0
[18:39:12] [main/INFO]: [Shaders] Allocate texture map specular: 1024x2048, mipmaps: 0
[18:39:12] [main/INFO]: [OptiFine] Animated sprites: 2
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 128, icon: brandonscore:gui/light/button_borderless_invert
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 129, icon: brandonscore:gui/light/button_borderless_invert
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 130, icon: brandonscore:gui/light/button_borderless_invert
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 128, icon: brandonscore:gui/light/button_borderless_invert
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 129, icon: brandonscore:gui/light/button_borderless_invert
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 130, icon: brandonscore:gui/light/button_borderless_invert
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 128, icon: brandonscore:gui/light/button_borderless_invert
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 129, icon: brandonscore:gui/light/button_borderless_invert
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 130, icon: brandonscore:gui/light/button_borderless_invert
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 128, icon: brandonscore:gui/light/button_borderless_invert
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 129, icon: brandonscore:gui/light/button_borderless_invert
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 130, icon: brandonscore:gui/light/button_borderless_invert
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 128, icon: brandonscore:gui/light/button_borderless_invert
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 129, icon: brandonscore:gui/light/button_borderless_invert
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 130, icon: brandonscore:gui/light/button_borderless_invert
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 128, icon: brandonscore:gui/light/button_borderless_invert
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 129, icon: brandonscore:gui/light/button_borderless_invert
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 130, icon: brandonscore:gui/light/button_borderless_invert
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 128, icon: brandonscore:gui/light/button_borderless_invert
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 129, icon: brandonscore:gui/light/button_borderless_invert
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 130, icon: brandonscore:gui/light/button_borderless_invert
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 128, icon: brandonscore:gui/light/button_borderless_invert
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 129, icon: brandonscore:gui/light/button_borderless_invert
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 130, icon: brandonscore:gui/light/button_borderless_invert
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 128, icon: brandonscore:gui/light/button_highlight
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 129, icon: brandonscore:gui/light/button_highlight
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 130, icon: brandonscore:gui/light/button_highlight
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 128, icon: brandonscore:gui/light/button_highlight
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 129, icon: brandonscore:gui/light/button_highlight
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 130, icon: brandonscore:gui/light/button_highlight
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 128, icon: brandonscore:gui/light/button_highlight
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 129, icon: brandonscore:gui/light/button_highlight
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 130, icon: brandonscore:gui/light/button_highlight
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 128, icon: brandonscore:gui/light/button_highlight
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 129, icon: brandonscore:gui/light/button_highlight
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 130, icon: brandonscore:gui/light/button_highlight
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 128, icon: brandonscore:gui/light/button_highlight
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 129, icon: brandonscore:gui/light/button_highlight
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 130, icon: brandonscore:gui/light/button_highlight
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 128, icon: brandonscore:gui/light/button_highlight
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 129, icon: brandonscore:gui/light/button_highlight
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 130, icon: brandonscore:gui/light/button_highlight
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 128, icon: brandonscore:gui/light/button_highlight
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 129, icon: brandonscore:gui/light/button_highlight
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 130, icon: brandonscore:gui/light/button_highlight
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 128, icon: brandonscore:gui/light/button_highlight
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 129, icon: brandonscore:gui/light/button_highlight
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 130, icon: brandonscore:gui/light/button_highlight
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 128, icon: brandonscore:gui/light/button_disabled
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 129, icon: brandonscore:gui/light/button_disabled
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 130, icon: brandonscore:gui/light/button_disabled
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 128, icon: brandonscore:gui/light/button_disabled
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 129, icon: brandonscore:gui/light/button_disabled
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 130, icon: brandonscore:gui/light/button_disabled
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 128, icon: brandonscore:gui/light/button_disabled
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 129, icon: brandonscore:gui/light/button_disabled
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 130, icon: brandonscore:gui/light/button_disabled
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 128, icon: brandonscore:gui/light/button_disabled
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 129, icon: brandonscore:gui/light/button_disabled
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 130, icon: brandonscore:gui/light/button_disabled
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 128, icon: brandonscore:gui/light/button_disabled
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 129, icon: brandonscore:gui/light/button_disabled
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 130, icon: brandonscore:gui/light/button_disabled
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 128, icon: brandonscore:gui/light/button_disabled
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 129, icon: brandonscore:gui/light/button_disabled
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 130, icon: brandonscore:gui/light/button_disabled
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 128, icon: brandonscore:gui/light/button_disabled
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 129, icon: brandonscore:gui/light/button_disabled
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 130, icon: brandonscore:gui/light/button_disabled
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 128, icon: brandonscore:gui/light/button_disabled
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 129, icon: brandonscore:gui/light/button_disabled
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 130, icon: brandonscore:gui/light/button_disabled
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 128, icon: brandonscore:gui/dark/button_borderless
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 129, icon: brandonscore:gui/dark/button_borderless
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 130, icon: brandonscore:gui/dark/button_borderless
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 128, icon: brandonscore:gui/dark/button_borderless
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 129, icon: brandonscore:gui/dark/button_borderless
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 130, icon: brandonscore:gui/dark/button_borderless
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 128, icon: brandonscore:gui/dark/button_borderless
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 129, icon: brandonscore:gui/dark/button_borderless
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 130, icon: brandonscore:gui/dark/button_borderless
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 128, icon: brandonscore:gui/dark/button_borderless
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 129, icon: brandonscore:gui/dark/button_borderless
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 130, icon: brandonscore:gui/dark/button_borderless
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 128, icon: brandonscore:gui/dark/button_borderless
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 129, icon: brandonscore:gui/dark/button_borderless
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 130, icon: brandonscore:gui/dark/button_borderless
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 128, icon: brandonscore:gui/dark/button_borderless
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 129, icon: brandonscore:gui/dark/button_borderless
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 130, icon: brandonscore:gui/dark/button_borderless
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 128, icon: brandonscore:gui/dark/button_borderless
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 129, icon: brandonscore:gui/dark/button_borderless
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 130, icon: brandonscore:gui/dark/button_borderless
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 128, icon: brandonscore:gui/dark/button_borderless
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 129, icon: brandonscore:gui/dark/button_borderless
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 130, icon: brandonscore:gui/dark/button_borderless
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 128, icon: brandonscore:gui/dark/button_borderless_invert
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 129, icon: brandonscore:gui/dark/button_borderless_invert
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 130, icon: brandonscore:gui/dark/button_borderless_invert
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 128, icon: brandonscore:gui/dark/button_borderless_invert
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 129, icon: brandonscore:gui/dark/button_borderless_invert
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 130, icon: brandonscore:gui/dark/button_borderless_invert
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 128, icon: brandonscore:gui/dark/button_borderless_invert
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 129, icon: brandonscore:gui/dark/button_borderless_invert
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 130, icon: brandonscore:gui/dark/button_borderless_invert
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 128, icon: brandonscore:gui/dark/button_borderless_invert
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 129, icon: brandonscore:gui/dark/button_borderless_invert
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 130, icon: brandonscore:gui/dark/button_borderless_invert
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 128, icon: brandonscore:gui/dark/button_borderless_invert
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 129, icon: brandonscore:gui/dark/button_borderless_invert
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 130, icon: brandonscore:gui/dark/button_borderless_invert
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 128, icon: brandonscore:gui/dark/button_borderless_invert
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 129, icon: brandonscore:gui/dark/button_borderless_invert
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 130, icon: brandonscore:gui/dark/button_borderless_invert
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 128, icon: brandonscore:gui/dark/button_borderless_invert
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 129, icon: brandonscore:gui/dark/button_borderless_invert
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 130, icon: brandonscore:gui/dark/button_borderless_invert
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 128, icon: brandonscore:gui/dark/button_borderless_invert
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 129, icon: brandonscore:gui/dark/button_borderless_invert
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 130, icon: brandonscore:gui/dark/button_borderless_invert
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 128, icon: brandonscore:gui/dark/button_borderless_invert
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 129, icon: brandonscore:gui/dark/button_borderless_invert
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 130, icon: brandonscore:gui/dark/button_borderless_invert
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 128, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 129, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 130, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 131, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 132, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 133, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 134, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 135, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 128, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 129, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 130, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 131, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 132, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 133, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 134, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 135, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 128, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 129, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 130, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 131, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 132, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 133, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 134, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 135, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 128, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 129, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 130, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 131, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 132, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 133, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 134, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 135, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 128, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 129, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 130, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 131, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 132, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 133, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 134, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 135, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 128, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 129, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 130, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 131, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 132, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 133, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 134, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 135, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 128, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 129, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 130, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 131, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 132, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 133, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 134, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 135, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 128, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 129, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 130, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 131, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 132, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 133, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 134, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 135, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 128, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 129, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 130, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 131, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 132, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 133, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 134, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 135, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 128, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 129, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 130, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 131, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 132, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 133, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 134, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 135, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 128, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 129, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 130, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 131, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 132, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 133, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 134, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 135, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 128, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 129, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 130, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 131, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 132, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 133, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 134, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 135, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 128, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 129, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 130, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 131, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 132, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 133, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 134, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 135, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 128, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 129, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 130, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 131, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 132, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 133, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 134, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 135, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 128, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 129, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 130, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 131, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 132, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 133, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 134, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 135, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 128, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 129, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 130, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 131, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 132, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 133, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 134, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 135, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 128, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 129, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 130, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 131, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 132, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 133, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 134, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 135, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 128, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 129, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 130, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 131, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 132, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 133, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 134, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 135, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 128, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 129, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 130, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 131, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 132, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 133, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 134, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 135, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 128, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 129, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 130, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 131, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 132, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 133, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 134, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 135, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 128, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 129, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 130, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 131, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 132, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 133, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 134, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 135, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 128, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 129, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 130, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 131, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 132, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 133, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 134, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 135, icon: brandonscore:gui/dark/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 128, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 129, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 130, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 131, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 132, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 133, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 134, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 135, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 128, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 129, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 130, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 131, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 132, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 133, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 134, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 135, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 128, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 129, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 130, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 131, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 132, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 133, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 134, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 135, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 128, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 129, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 130, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 131, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 132, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 133, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 134, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 135, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 128, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 129, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 130, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 131, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 132, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 133, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 134, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 135, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 128, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 129, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 130, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 131, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 132, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 133, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 134, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 135, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 128, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 129, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 130, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 131, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 132, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 133, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 134, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 135, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 128, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 129, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 130, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 131, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 132, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 133, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 134, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 135, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 128, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 129, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 130, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 131, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 132, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 133, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 134, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 135, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 128, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 129, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 130, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 131, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 132, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 133, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 134, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 135, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 128, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 129, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 130, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 131, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 132, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 133, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 134, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 135, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 128, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 129, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 130, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 131, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 132, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 133, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 134, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 135, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 128, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 129, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 130, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 131, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 132, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 133, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 134, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 135, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 128, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 129, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 130, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 131, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 132, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 133, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 134, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 135, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 128, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 129, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 130, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 131, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 132, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 133, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 134, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 135, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 128, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 129, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 130, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 131, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 132, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 133, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 134, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 135, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 128, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 129, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 130, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 131, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 132, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 133, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 134, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 135, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 128, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 129, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 130, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 131, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 132, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 133, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 134, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 135, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 128, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 129, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 130, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 131, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 132, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 133, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 134, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 135, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 128, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 129, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 130, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 131, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 132, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 133, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 134, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 135, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 128, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 129, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 130, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 131, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 132, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 133, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 134, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 135, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 128, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 129, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 130, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 131, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 132, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 133, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 134, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/WARN]: [OptiFine] Invalid grid V: 135, icon: brandonscore:gui/light/background-176x166
[18:39:12] [main/INFO]: [Shaders] Allocate texture map normal: 256x128, mipmaps: 0
[18:39:12] [main/INFO]: [Shaders] Allocate texture map specular: 256x128, mipmaps: 0
[18:39:12] [main/INFO]: [OptiFine] Animated sprites: 2
[18:39:12] [main/INFO]: [Shaders] Allocate texture map normal: 8192x4096, mipmaps: 0
[18:39:12] [main/INFO]: [Shaders] Allocate texture map specular: 8192x4096, mipmaps: 0
[18:39:12] [main/INFO]: [OptiFine] Animated sprites: 1143
[18:39:12] [main/INFO]: [Shaders] Allocate texture map normal: 1024x512, mipmaps: 0
[18:39:12] [main/INFO]: [Shaders] Allocate texture map specular: 1024x512, mipmaps: 0
[18:39:12] [main/INFO]: [OptiFine] Animated sprites: 2
[18:39:12] [main/INFO]: [Shaders] Allocate texture map normal: 1024x512, mipmaps: 0
[18:39:12] [main/INFO]: [Shaders] Allocate texture map specular: 1024x512, mipmaps: 0
[18:39:12] [main/INFO]: [OptiFine] Animated sprites: 2
[18:39:13] [main/INFO]: [Shaders] Allocate texture map normal: 1024x512, mipmaps: 0
[18:39:13] [main/INFO]: [Shaders] Allocate texture map specular: 1024x512, mipmaps: 0
[18:39:13] [main/INFO]: [OptiFine] Animated sprites: 2
[18:39:13] [main/INFO]: [Shaders] Allocate texture map normal: 1024x512, mipmaps: 0
[18:39:13] [main/INFO]: [Shaders] Allocate texture map specular: 1024x512, mipmaps: 0
[18:39:13] [main/INFO]: [OptiFine] Animated sprites: 2
[18:39:13] [main/INFO]: [Shaders] Allocate texture map normal: 256x256, mipmaps: 0
[18:39:13] [main/INFO]: [Shaders] Allocate texture map specular: 256x256, mipmaps: 0
[18:39:13] [main/INFO]: [OptiFine] Animated sprites: 2
[18:39:13] [main/INFO]: [Shaders] Allocate texture map normal: 512x256, mipmaps: 0
[18:39:13] [main/INFO]: [Shaders] Allocate texture map specular: 512x256, mipmaps: 0
[18:39:13] [main/INFO]: [OptiFine] Animated sprites: 2
[18:39:13] [main/INFO]: [Shaders] Allocate texture map normal: 512x256, mipmaps: 0
[18:39:13] [main/INFO]: [Shaders] Allocate texture map specular: 512x256, mipmaps: 0
[18:39:13] [main/INFO]: [OptiFine] Animated sprites: 2
[18:39:39] [main/INFO]: Model replacement took 0 ms
[18:39:58] [main/INFO]: Textures for fragment model
[18:39:58] [main/INFO]: - silentgear:item/fragment/wood
[18:39:58] [main/INFO]: - silentgear:item/fragment/cloth
[18:39:58] [main/INFO]: - silentgear:item/fragment/metal
[18:39:58] [main/INFO]: - silentgear:item/fragment/dust
[18:39:58] [main/INFO]: - silentgear:item/error
[18:40:08] [main/INFO]: Starting model bake at 2.0904063E13
[18:40:08] [main/INFO]: Model bake finished in 0.34393293 seconds
[18:40:09] [main/INFO]: Model replacement took 7 ms
[18:40:12] [main/INFO]: [Shaders] Allocate texture map normal: 512x512, mipmaps: 0
[18:40:12] [main/INFO]: [Shaders] Allocate texture map specular: 512x512, mipmaps: 0
[18:40:12] [main/INFO]: [OptiFine] Animated sprites: 2
[18:40:12] [main/INFO]: [Shaders] Allocate texture map normal: 1024x1024, mipmaps: 0
[18:40:12] [main/INFO]: [Shaders] Allocate texture map specular: 1024x1024, mipmaps: 0
[18:40:12] [main/INFO]: [OptiFine] Animated sprites: 4
[18:40:12] [main/INFO]: [Shaders] Allocate texture map normal: 512x256, mipmaps: 0
[18:40:12] [main/INFO]: [Shaders] Allocate texture map specular: 512x256, mipmaps: 0
[18:40:12] [main/INFO]: [OptiFine] Animated sprites: 2
[18:40:12] [main/INFO]: [Shaders] Allocate texture map normal: 512x512, mipmaps: 0
[18:40:12] [main/INFO]: [Shaders] Allocate texture map specular: 512x512, mipmaps: 0
[18:40:12] [main/INFO]: [OptiFine] Animated sprites: 2
[18:40:12] [main/INFO]: [OptiFine] *** Reloading custom textures ***
[18:40:12] [main/WARN]: [OptiFine] Unknown resource pack file: mod_resources
[18:40:12] [main/WARN]: [OptiFine] Unknown resource pack type: org.zeith.solarflux.client.SolarFluxResourcePack@348748d7
[18:40:13] [main/WARN]: [OptiFine] Unknown resource pack file: mod_resources
[18:40:13] [main/WARN]: [OptiFine] Unknown resource pack type: org.zeith.solarflux.client.SolarFluxResourcePack@348748d7
[18:40:13] [main/WARN]: [OptiFine] Unknown resource pack file: mod_resources
[18:40:13] [main/WARN]: [OptiFine] Unknown resource pack type: org.zeith.solarflux.client.SolarFluxResourcePack@348748d7
[18:42:42] [main/WARN]: [OptiFine] Unknown resource pack file: mod_resources
[18:42:42] [main/WARN]: [OptiFine] Unknown resource pack type: org.zeith.solarflux.client.SolarFluxResourcePack@348748d7
[18:42:46] [main/WARN]: [OptiFine] Unknown resource pack type: org.zeith.solarflux.client.SolarFluxResourcePack@348748d7
[18:42:46] [main/WARN]: [OptiFine] Unknown resource pack file: mod_resources
[18:42:46] [main/WARN]: [OptiFine] Unknown resource pack file: mod_resources
[18:42:46] [main/WARN]: [OptiFine] Unknown resource pack type: org.zeith.solarflux.client.SolarFluxResourcePack@348748d7
[18:42:46] [main/INFO]: [OptiFine] Disable Forge light pipeline
[18:42:46] [main/INFO]: [OptiFine] Set ForgeConfig.CLIENT.forgeLightPipelineEnabled=false
[18:45:06] [main/INFO]: Adding DataPackFinder
[18:45:06] [main/INFO]: Patching net/minecraft/command/impl/EnchantCommand
[18:45:06] [main/INFO]: Registering /terra command
[18:45:07] [main/INFO]: onRegisterCommandsEvent
[18:45:07] [main/INFO]: Loading command nodes...
[18:45:07] [main/INFO]: Loaded 2901 command nodes
[18:45:07] [main/INFO]: Adding Reload Listener: 'resourcefulbees recipe manager'
[18:45:07] [main/INFO]: Loaded script server_scripts:mod_specific/envirotech/envirotech.js in 0.011 s
[18:45:07] [main/INFO]: Loaded script server_scripts:tags.js in 0.004 s
[18:45:07] [main/INFO]: Loaded script server_scripts:unify.js in 0.01 s
[18:45:07] [main/INFO]: Loaded script server_scripts:constants.js in 0.001 s
[18:45:07] [main/INFO]: Loaded script server_scripts:advanced_interactions/atm_shards.js in 0.001 s
[18:45:07] [main/INFO]: Loaded script server_scripts:advanced_interactions/multiblock.js in 0.001 s
[18:45:07] [main/INFO]: Loaded script server_scripts:advanced_interactions/turtles.js in 0.001 s
[18:45:07] [main/INFO]: Loaded script server_scripts:mod_specific/akashic_tome/akashic_tome.js in 0.001 s
[18:45:07] [main/INFO]: Loaded script server_scripts:mod_specific/angelring/angelring.js in 0.0 s
[18:45:07] [main/INFO]: Loaded script server_scripts:mod_specific/apotheosis/apotheosis.js in 0.0 s
[18:45:07] [main/INFO]: Loaded script server_scripts:mod_specific/applied_energistics2/applied_energistics2.js in 0.001 s
[18:45:07] [main/INFO]: Loaded script server_scripts:mod_specific/ars_nouveau/ars.js in 0.0 s
[18:45:07] [main/INFO]: Loaded script server_scripts:mod_specific/astralsorcery/astralsorcery.js in 0.0 s
[18:45:07] [main/INFO]: Loaded script server_scripts:mod_specific/bagofyurting/bagofyurting.js in 0.001 s
[18:45:07] [main/INFO]: Loaded script server_scripts:mod_specific/biggerreactors/biggerreactors.js in 0.0 s
[18:45:07] [main/INFO]: Loaded script server_scripts:mod_specific/biomesoplenty/biomesoplenty.js in 0.0 s
[18:45:07] [main/INFO]: Loaded script server_scripts:mod_specific/botania/botania.js in 0.001 s
[18:45:07] [main/INFO]: Loaded script server_scripts:mod_specific/botania/mjollnir.js in 0.0 s
[18:45:07] [main/INFO]: Loaded script server_scripts:mod_specific/botany_pots/botany_pots.js in 0.003 s
[18:45:07] [main/INFO]: Loaded script server_scripts:mod_specific/buildinggadgets/buildinggadgets.js in 0.0 s
[18:45:07] [main/INFO]: Loaded script server_scripts:mod_specific/byg/byg.js in 0.001 s
[18:45:07] [main/INFO]: Loaded script server_scripts:mod_specific/comforts/comforts.js in 0.0 s
[18:45:07] [main/INFO]: Loaded script server_scripts:mod_specific/compact_machines/compct_machines.js in 0.0 s
[18:45:07] [main/INFO]: Loaded script server_scripts:mod_specific/computercraft/computercraft.js in 0.0 s
[18:45:07] [main/INFO]: Loaded script server_scripts:mod_specific/create/create.js in 0.001 s
[18:45:07] [main/INFO]: Loaded script server_scripts:mod_specific/cyclic/cyclic.js in 0.0 s
[18:45:07] [main/INFO]: Loaded script server_scripts:mod_specific/entangled/entangled.js in 0.0 s
[18:45:07] [main/INFO]: Loaded script server_scripts:mod_specific/explorerscompass/explorerscompass.js in 0.001 s
[18:45:07] [main/INFO]: Loaded script server_scripts:mod_specific/forbidden_arcanus/forbidden_arcanus.js in 0.0 s
[18:45:07] [main/INFO]: Loaded script server_scripts:mod_specific/framedblocks/framedblocks.js in 0.001 s
[18:45:07] [main/INFO]: Loaded script server_scripts:mod_specific/iceandfire/iceandfire.js in 0.001 s
[18:45:07] [main/INFO]: Loaded script server_scripts:mod_specific/immersive_engineering/cloche.js in 0.001 s
[18:45:07] [main/INFO]: Loaded script server_scripts:mod_specific/immersive_engineering/immersive_engineering.js in 0.001 s
[18:45:07] [main/INFO]: Loaded script server_scripts:mod_specific/integrated_dynamics/integrated_dynamics.js in 0.0 s
[18:45:07] [main/INFO]: Loaded script server_scripts:mod_specific/iron_jetpacks/iron_jetpacks.js in 0.001 s
[18:45:07] [main/INFO]: Loaded script server_scripts:mod_specific/macaw/macaw.js in 0.0 s
[18:45:07] [main/INFO]: Loaded script server_scripts:mod_specific/mekanism/mekanism.js in 0.001 s
[18:45:07] [main/INFO]: Loaded script server_scripts:mod_specific/metalbarrels/metalbarrels.js in 0.0 s
[18:45:07] [main/INFO]: Loaded script server_scripts:mod_specific/mininggadgets/mininggadgets.js in 0.0 s
[18:45:07] [main/INFO]: Loaded script server_scripts:mod_specific/mysticalagriculture/mysticalagriculture.js in 0.001 s
[18:45:07] [main/INFO]: Loaded script server_scripts:mod_specific/pams_harvestcraft/pams.js in 0.0 s
[18:45:07] [main/INFO]: Loaded script server_scripts:mod_specific/pedestals/pedestals.js in 0.001 s
[18:45:07] [main/INFO]: Loaded script server_scripts:mod_specific/pneumaticcraft/pneumaticcraft.js in 0.001 s
[18:45:07] [main/INFO]: Loaded script server_scripts:mod_specific/powah/powah.js in 0.001 s
[18:45:07] [main/INFO]: Loaded script server_scripts:mod_specific/projectred/projectred.js in 0.0 s
[18:45:07] [main/INFO]: Loaded script server_scripts:mod_specific/quark/quark.js in 0.0 s
[18:45:07] [main/INFO]: Loaded script server_scripts:mod_specific/quarryplus/quarryplus.js in 0.001 s
[18:45:07] [main/INFO]: Loaded script server_scripts:mod_specific/refinedstorage/refinedstorage.js in 0.001 s
[18:45:07] [main/INFO]: Loaded script server_scripts:mod_specific/resourcefulbees/comb_recipes.js in 0.002 s
[18:45:07] [main/INFO]: Loaded script server_scripts:mod_specific/resourcefulbees/resourcefulbees.js in 0.0 s
[18:45:07] [main/INFO]: Loaded script server_scripts:mod_specific/rftools/dimension_builder.js in 0.0 s
[18:45:07] [main/INFO]: Loaded script server_scripts:mod_specific/rftools/rftools.js in 0.0 s
[18:45:07] [main/INFO]: Loaded script server_scripts:mod_specific/solarflux/solarflux.js in 0.001 s
[18:45:07] [main/INFO]: Loaded script server_scripts:mod_specific/storage_drawers/storage_drawers.js in 0.0 s
[18:45:07] [main/INFO]: Loaded script server_scripts:mod_specific/tconstruct/tconstruct.js in 0.001 s
[18:45:07] [main/INFO]: Loaded script server_scripts:mod_specific/thermal/thermal.js in 0.002 s
[18:45:07] [main/INFO]: Loaded script server_scripts:mod_specific/tombstone/tombstone.js in 0.0 s
[18:45:07] [main/INFO]: Loaded script server_scripts:mod_specific/universal_grid/universal_grid.js in 0.0 s
[18:45:07] [main/INFO]: Loaded script server_scripts:mod_specific/woot/woot.js in 0.001 s
[18:45:07] [main/INFO]: Loaded script server_scripts:mod_specific/xreliquary/xreliquary.js in 0.0 s
[18:45:07] [main/INFO]: Loaded script server_scripts:mod_specific/zycraft/zycraft.js in 0.0 s
[18:45:07] [main/INFO]: Loaded script server_scripts:mod_specific/_allthemods/allthemodium.js in 0.001 s
[18:45:07] [main/INFO]: Loaded script server_scripts:mod_specific/_allthemods/atm_shard.js in 0.0 s
[18:45:07] [main/INFO]: Loaded script server_scripts:mod_specific/_allthemods/atm_star.js in 0.002 s
[18:45:07] [main/INFO]: Loaded script server_scripts:mod_specific/_allthemods/uu_matter_recipes.js in 0.001 s
[18:45:07] [main/INFO]: Loaded script server_scripts:mod_specific/_minecraft/minecraft.js in 0.001 s
[18:45:07] [main/INFO]: Loaded script server_scripts:mod_specific/_misc/misc.js in 0.0 s
[18:45:07] [main/INFO]: Loaded 67/67 KubeJS server scripts in 0.078 s
[18:45:07] [main/INFO]: Scripts loaded
[18:45:07] [main/INFO]: Registered custom recipe handler for type kubejs:shaped
[18:45:07] [main/INFO]: Registered custom recipe handler for type kubejs:shapeless
[18:45:07] [main/INFO]: Registered custom recipe handler for type minecraft:crafting_shaped
[18:45:07] [main/INFO]: Registered custom recipe handler for type minecraft:crafting_shapeless
[18:45:07] [main/INFO]: Registered custom recipe handler for type minecraft:stonecutting
[18:45:07] [main/INFO]: Registered custom recipe handler for type minecraft:smelting
[18:45:07] [main/INFO]: Registered custom recipe handler for type minecraft:blasting
[18:45:07] [main/INFO]: Registered custom recipe handler for type minecraft:smoking
[18:45:07] [main/INFO]: Registered custom recipe handler for type minecraft:campfire_cooking
[18:45:07] [main/INFO]: Registered custom recipe handler for type minecraft:smithing
[18:45:07] [main/INFO]: Registered custom recipe handler for type cucumber:shaped_no_mirror
[18:45:07] [main/INFO]: Registered custom recipe handler for type mysticalagriculture:tag
[18:45:07] [main/INFO]: Registered custom recipe handler for type botanypots:crop
[18:45:07] [main/INFO]: Registered custom recipe handler for type dankstorage:upgrade
[18:45:07] [main/INFO]: Registered custom recipe handler for type appliedenergistics2:grinder
[18:45:07] [main/INFO]: Registered custom recipe handler for type botania:runic_altar
[18:45:07] [main/INFO]: Registered custom recipe handler for type integrateddynamics:squeezer
[18:45:07] [main/INFO]: Registered custom recipe handler for type integrateddynamics:mechanical_squeezer
[18:45:07] [main/INFO]: Registered custom recipe handler for type ars_nouveau:enchanting_apparatus
[18:45:07] [main/INFO]: Registered custom recipe handler for type ars_nouveau:enchantment
[18:45:07] [main/INFO]: Registered custom recipe handler for type ars_nouveau:glyph_recipe
[18:45:07] [main/INFO]: Registered custom recipe handler for type thermal:furnace
[18:45:07] [main/INFO]: Registered custom recipe handler for type thermal:sawmill
[18:45:07] [main/INFO]: Registered custom recipe handler for type thermal:pulverizer
[18:45:07] [main/INFO]: Registered custom recipe handler for type thermal:smelter
[18:45:07] [main/INFO]: Registered custom recipe handler for type thermal:insolator
[18:45:07] [main/INFO]: Registered custom recipe handler for type thermal:centrifuge
[18:45:07] [main/INFO]: Registered custom recipe handler for type thermal:press
[18:45:07] [main/INFO]: Registered custom recipe handler for type thermal:crucible
[18:45:07] [main/INFO]: Registered custom recipe handler for type thermal:chiller
[18:45:07] [main/INFO]: Registered custom recipe handler for type thermal:refinery
[18:45:07] [main/INFO]: Registered custom recipe handler for type thermal:pyrolyzer
[18:45:07] [main/INFO]: Registered custom recipe handler for type thermal:brewer
[18:45:07] [main/INFO]: Registered custom recipe handler for type thermal:bottler
[18:45:07] [main/INFO]: Registered custom recipe handler for type thermal:pulverizer_catalyst
[18:45:07] [main/INFO]: Registered custom recipe handler for type thermal:smelter_catalyst
[18:45:07] [main/INFO]: Registered custom recipe handler for type thermal:insolator_catalyst
[18:45:07] [main/INFO]: Registered custom recipe handler for type thermal:stirling_fuel
[18:45:07] [main/INFO]: Registered custom recipe handler for type thermal:compression_fuel
[18:45:07] [main/INFO]: Registered custom recipe handler for type thermal:magmatic_fuel
[18:45:07] [main/INFO]: Registered custom recipe handler for type thermal:numismatic_fuel
[18:45:07] [main/INFO]: Registered custom recipe handler for type thermal:lapidary_fuel
[18:45:07] [main/INFO]: Registered custom recipe handler for type thermal:tree_extractor
[18:45:07] [main/INFO]: Registered custom recipe handler for type thermal:tree_extractor_boost
[18:45:07] [main/INFO]: Registered custom recipe handler for type thermal:fisher_boost
[18:45:07] [main/INFO]: Registered custom recipe handler for type thermal:rock_gen
[18:45:07] [main/INFO]: Registered custom recipe handler for type thermal:potion_diffuser_boost
[18:45:07] [main/INFO]: Registered custom recipe handler for type create:sequenced_assembly
[18:45:07] [main/INFO]: Registered custom recipe handler for type create:mechanical_crafting
[18:45:07] [main/INFO]: Registered custom recipe handler for type create:conversion
[18:45:07] [main/INFO]: Registered custom recipe handler for type create:crushing
[18:45:07] [main/INFO]: Registered custom recipe handler for type create:cutting
[18:45:07] [main/INFO]: Registered custom recipe handler for type create:milling
[18:45:07] [main/INFO]: Registered custom recipe handler for type create:basin
[18:45:07] [main/INFO]: Registered custom recipe handler for type create:mixing
[18:45:07] [main/INFO]: Registered custom recipe handler for type create:compacting
[18:45:07] [main/INFO]: Registered custom recipe handler for type create:pressing
[18:45:07] [main/INFO]: Registered custom recipe handler for type create:sandpaper_polishing
[18:45:07] [main/INFO]: Registered custom recipe handler for type create:splashing
[18:45:07] [main/INFO]: Registered custom recipe handler for type create:deploying
[18:45:07] [main/INFO]: Registered custom recipe handler for type create:filling
[18:45:07] [main/INFO]: Registered custom recipe handler for type create:emptying
[18:45:07] [main/INFO]: Registered custom recipe handler for type immersiveengineering:turn_and_copy
[18:45:07] [main/INFO]: Registered custom recipe handler for type immersiveengineering:alloy
[18:45:07] [main/INFO]: Registered custom recipe handler for type immersiveengineering:blast_furnace
[18:45:07] [main/INFO]: Registered custom recipe handler for type immersiveengineering:blast_furnace_fuel
[18:45:07] [main/INFO]: Registered custom recipe handler for type immersiveengineering:coke_oven
[18:45:07] [main/INFO]: Registered custom recipe handler for type immersiveengineering:cloche
[18:45:07] [main/INFO]: Registered custom recipe handler for type immersiveengineering:fertilizer
[18:45:07] [main/INFO]: Registered custom recipe handler for type immersiveengineering:metal_press
[18:45:07] [main/INFO]: Registered custom recipe handler for type immersiveengineering:arc_furnace
[18:45:07] [main/INFO]: Registered custom recipe handler for type immersiveengineering:crusher
[18:45:07] [main/INFO]: Registered custom recipe handler for type immersiveengineering:sawmill
[18:45:07] [main/INFO]: Registered custom recipe handler for type mekanism:crushing
[18:45:07] [main/INFO]: Registered custom recipe handler for type mekanism:enriching
[18:45:07] [main/INFO]: Registered custom recipe handler for type mekanism:smelting
[18:45:07] [main/INFO]: Registered custom recipe handler for type mekanism:chemical_infusing
[18:45:07] [main/INFO]: Registered custom recipe handler for type mekanism:combining
[18:45:07] [main/INFO]: Registered custom recipe handler for type mekanism:crystallizing
[18:45:07] [main/INFO]: Registered custom recipe handler for type mekanism:dissolution
[18:45:07] [main/INFO]: Registered custom recipe handler for type mekanism:compressing
[18:45:07] [main/INFO]: Registered custom recipe handler for type mekanism:purifying
[18:45:07] [main/INFO]: Registered custom recipe handler for type mekanism:injecting
[18:45:07] [main/INFO]: Registered custom recipe handler for type mekanism:energy_conversion
[18:45:07] [main/INFO]: Registered custom recipe handler for type mekanism:gas_conversion
[18:45:07] [main/INFO]: Registered custom recipe handler for type mekanism:oxidizing
[18:45:07] [main/INFO]: Registered custom recipe handler for type mekanism:metallurgic_infusing
[18:45:07] [main/INFO]: Registered custom recipe handler for type mekanism:reaction
[18:45:07] [main/INFO]: Registered custom recipe handler for type mekanism:sawing
[18:45:07] [main/INFO]: Registered custom recipe handler for type bloodmagic:altar
[18:45:07] [main/INFO]: Registered custom recipe handler for type bloodmagic:array
[18:45:07] [main/INFO]: Registered custom recipe handler for type bloodmagic:soulforge
[18:45:07] [main/INFO]: Registered custom recipe handler for type bloodmagic:arc
[18:45:07] [main/INFO]: Registered custom recipe handler for type bloodmagic:alchemytable
[18:45:07] [main/INFO]: Scanning recipes...
[18:45:07] [main/INFO]: Reloading ResourceManager: KubeJS Virtual Data Pack [low priority], Default, BetterDungeons-1.16.4-1.2.1.jar, ftb-essentials-1605.1.5-build.32.jar, supermartijn642configlib-1.0.9-mc1.16.jar, AdditionalEnchantedMiner-1.16.5-16.1.11.jar, simplemagnets-1.1.5-mc1.16.jar, IntegratedTerminals-1.16.5-1.2.11.jar, HammerLib-1.16.5-16.3.27.jar, mcw-windows-2.0.2-mc1.16.5.jar, windowlogging-mc1.16.5_v0.0.5.jar, modnametooltip_1.16.2-1.15.0.jar, IronJetpacks-1.16.5-4.2.3.jar, ForgeEndertech-1.16.5-7.2.2.0-build.0202.jar, CTM-MC1.16.1-1.1.2.6.jar, YungsApi-1.16.4-Forge-13.jar, Powah-1.16.5-2.3.16.jar, cabletiers-1.16.5-0.544.jar, rangedpumps-0.8.2.jar, jumbofurnace-1.16.4-2.2.0.1.jar, WitherSkeletonTweaks-1.16.5-5.4.1.jar, Shrink-1.16.5-1.1.6.jar, reliquary-1.16.5-1.3.5.1104.jar, universalgrid-1.16.5-0.125.jar, randompatches-2.4.4-forge.jar, Apotheosis-1.16.5-4.8.4.jar, WaterStrainer-1.16.3-10.0.0.jar, dynviewdist-2.0.jar, TMechworks-1.16.3+-2.2.5.jar, JustEnoughResources-1.16.5-0.12.1.133.jar, DeLogger-3.0.4-build.20+mc1.16.5.jar, shetiphiancore-1.16-3.8.6.jar, supplementaries-1.16.5-0.18.2.jar, refinedstorage-1.9.17.jar, novillagerdm-1.0.1.jar, AdvancementPlaques-1.16.5-1.4.1.jar, PackMenu-1.16.5-2.5.0.jar, alltheores-1.3.6-1.16.5-36.1.0.jar, industrial-foregoing-1.16.5-3.2.14.7-16.jar, cleancut-mc1.16-2.2-forge.jar, torchmaster-2.3.8.jar, repurposed_structures_forge-3.4.7+1.16.5.jar, fastfurnaceminusreplacement-1.1-1.16.3.jar, BiomesOPlenty-1.16.5-13.1.0.485-universal.jar, ironfurnaces-1.16.5-2.7.7.jar, mcw-trapdoors-1.0.4-mc1.16.5.jar, silent-gear-1.16.5-2.6.30.jar, supermartijn642corelib-1.0.16-mc1.16.5.jar, Botania-1.16.5-420.2.jar, SpawnerFix-1.16.2-1.0.0.2.jar, spark-forge.jar, portality-1.16.5-3.2.5.jar, curios-forge-1.16.5-4.0.5.3.jar, corail_woodcutter-1.16-2.0.1.jar, tanknull-2.3-1.16.4.jar, angelring-1.16.5-1.3.4.1.jar, tombstone-6.7.2-1.16.5.jar, ExtraStorage-1.16.5-1.6.1.jar, NaturesAura-34.3.jar, constructionwand-1.16.5-2.6.jar, mcw-roofs-2.1.0-mc1.16.5.jar, cfm-7.0.0pre22-1.16.3.jar, observerlib-1.16.5-1.5.3.jar, globalxp-1.16.5-v1.9.jar, cloth-config-4.13.49-forge.jar, AdChimneys-1.16.5-6.0.12.3-build.0207.jar, FastLeafDecay-v25.2.jar, CodeChickenLib-1.16.5-4.0.6.443-universal.jar, CBMultipart-1.16.5-3.0.4.123-universal.jar, Babel-1.0.5.jar, JEPB-1.0.0.jar, BetterMineshafts-Forge-1.16.4-2.0.4.jar, geckolib-forge-1.16.5-3.0.65.jar, SaveMyStronghold-1.16.4-1.0.jar, ClientTweaks_1.16.3-5.3.0.jar, nomowanderer_MC1.16.5_1.2.jar, woot-1.16.5-1.0.8.3.jar, bagofyurting-1.16.4-1.2.0.1.jar, jei-1.16.5-7.7.1.145.jar, jei-professions-1.0.0-1.16.4.jar, AttributeFix-1.16.5-10.1.3.jar, Mekanism-1.16.5-10.1.1.456.jar, caelus-forge-1.16.5-2.1.3.2.jar, AllTheCompressed-1.0.3-1.16.5-36.2.26.jar, invtweaks-1.16.4-1.0.1.jar, shutupexperimentalsettings-1.0.3.jar, NaturesCompass-1.16.5-1.9.1-forge.jar, catjammies-1.1.0.jar, LibX-1.16.3-1.0.76.jar, compactmachines-4.0.0-beta.2.jar, phosphophyllite-1.16.5-0.5.1.jar, engineerstools-1.16.5-1.1.7.jar, curioofundying-forge-1.16.5-5.2.0.0.jar, FarmingForBlockheads_1.16.5-7.3.1.jar, pneumaticcraft-repressurized-1.16.5-2.15.2-303.jar, pedestals-0.8s_hotfix_5.jar, extradisks-1.16.4-1.5.1.jar, ImmersivePetroleum-1.16.5-3.3.0-11.jar, ironchest-1.16.5-11.2.21.jar, MythicBotany-1.16.5-1.4.19.jar, IntegratedCrafting-1.16.5-1.0.20.jar, logprot-1.16-1.5.jar, theoneprobe-1.16-3.1.4.jar, MouseTweaks-2.14-mc1.16.2.jar, useful_railroads-1.16.5-1.4.6.38.jar, pamhc2crops-1.16.3-1.0.2.jar, creativeapiary-1.16.5-1.72.jar, Ding-1.16.5-1.3.0.jar, jeiintegration_1.16.5-7.0.1.15.jar, pipez-1.16.5-1.2.15.jar, flywheel-1.16-0.2.5.jar, Mantle-1.16.5-1.6.157.jar, IntegratedDynamics-1.16.5-1.10.6.jar, integratednbt-1.16.4-1.4.2.jar, pamhc2foodcore-1.16.3-1.0.2.jar, ftb-backups-2.1.2.2.jar, polymorph-forge-1.16.5-0.25.jar, AutoRegLib-1.6-49.jar, entityculling-forge-mc1.16.5-1.4.0.jar, structurize-0.13.252-ALPHA-universal.jar, norecipeadvancements-1.0.1.jar, creativecrafter-1.16.5-0.1521.jar, PickleTweaks-1.16.5-5.2.6.jar, lootr-1.16.5-0.1.11.36.jar, allthetweaks-1.4.5-1.16.5-36.1.13.jar, byg-1.3.5.jar, extremeSoundMuffler-3.17_1.16.5.jar, CosmeticArmorReworked-1.16.5-v4a.jar, xptome-1.16.5-v2.1.2.jar, DefaultOptions_1.16.5-12.2.1.jar, rsrequestify-1.16.5-2.1.6.jar, CyclopsCore-1.16.5-1.12.1.jar, astralsorcery-1.16-1.16.5-1.13.12.jar, NetherPortalFix_1.16.3-7.2.1.jar, aiotbotania-1.16.5-1.8.4.jar, advancedperipherals-1.16.5-0.7.7.1r.jar, tinyredstone-1.16.5-1.13.1.jar, eidolon-0.2.7.jar, managear-1.16.3-2.2.3.jar, JustEnoughCalculation-1.16.5-3.8.6.jar, incontrol-1.16-5.2.2.jar, connectivity-2.4-1.16.5.jar, rsgauges-1.16.5-1.2.13.jar, findme-1.16.3-2.2.1.0.jar, glassential-forge-1.16.5-1.1.7.jar, TerraForged-1.16.5-0.2.16-BETA-2.jar, configurableextramobdrops_1.16.5-1.8.jar, CookingForBlockheads_1.16.5-9.3.4.jar, Controlling-7.0.0.28.jar, Placebo-1.16.5-4.6.1.jar, dankstorage-3.19.jar, citadel-1.8.1-1.16.5.jar, iceandfire-2.1.9-1.16.5.jar, allthemodium-1.5.18-1.16.5-36.1.23.jar, mightyarchitect-mc1.16.3_v0.5.jar, potionsmaster-0.2.2-1.16.5-36.1.0.jar, moreminecarts-1.3.14.jar, culinaryconstruct-forge-1.16.5-4.0.0.7.jar, cartographer-0.0.2-1.16.5-36.0.52.jar, Bookshelf-Forge-1.16.5-10.4.31.jar, DarkUtilities-1.16.5-8.0.11.jar, BotanyPots-1.16.5-7.1.30.jar, BotanyTrees-1.16.5-3.0.6.jar, sophisticatedbackpacks-1.16.5-3.15.1.503.jar, u_team_core-1.16.5-3.2.1.196.jar, buildinggadgets-1.16.5-3.8.2.jar, FramedBlocks-2.13.0.jar, forge-1.16.5-36.2.26-universal.jar, cofh_core-1.16.5-1.4.2.9.jar, thermal_foundation-1.16.5-1.4.3.10.jar, thermal_innovation-1.16.5-1.4.1.3.jar, thermal_locomotion-1.16.5-1.4.1.2.jar, Psi 1.16-97.jar, thermal_cultivation-1.16.5-1.4.1.3.jar, appleskin-forge-mc1.16.x-2.3.0.jar, Aquaculture-1.16.5-2.1.21.jar, mcw-doors-1.0.5-mc1.16.5.jar, LightingWand-1.16.4-1.8.1.jar, jeed-1.16.5-1.6.jar, MekanismGenerators-1.16.5-10.1.1.456.jar, XNetGases-1.16.5-2.3.9.jar, MmmMmmMmmMmm-1.16.5-1.3.1.jar, absentbydesign-1.16.5-1.5.1.jar, twilightforest-1.16.5-4.0.870-universal.jar, mob_grinding_utils-1.16.5-0.4.32.jar, RSInfinityBooster-1.16.5-1.1+13.jar, EquipmentCompare-1.16.5-1.2.7.jar, chipped-1.16.5-1.2.1-forge.jar, chocolate-1.3.0-1.16.4.jar, mcw-bridges-2.0.1-mc1.16.5.jar, useful_backpacks-1.16.5-1.12.1.90.jar, ResourcefulBees-1.16.5-0.10.4.jar, HostileNeuralNetworks-1.16.5-1.0.6.jar, entangled-1.3.10-mc1.16.jar, endertanks-1.16-1.9.7.jar, CommonCapabilities-1.16.5-2.8.0.jar, crashutilities-3.13.jar, Compressium-1.16.5-1.2.3.jar, getittogetherdrops-1.16.5-v1.1.1.jar, MekanismAdditions-1.16.5-10.1.1.456.jar, valkyrielib-1.16.5-3.0.9.5.jar, envirocore-1.16.5-3.0.9.3.jar, envirotech-1.16.5-3.0.9.4.jar, Lollipop-1.16.5-3.2.9.jar, mcw-fences-1.0.2-mc1.16.5.jar, simplylight-1.16.5-1.4.0-build.24.jar, tgcropesmod-1.16.2-1.1.0.jar, atmadditions-1.16.5-1.0.2.jar, pamhc2foodextended-1.16.3-1.0.4.jar, SolarFluxReborn-1.16.5-16.3.9.jar, dpanvil-1.16.5-1.2.3.jar, Patchouli-1.16.4-53.2.jar, ars_nouveau-1.16.5-1.24.16.jar, collective-1.16.5-3.8.jar, betterbiomeblend-1.16.4-1.2.9-forge.jar, time-in-a-bottle-1.1.0.jar, thermal_expansion-1.16.5-1.4.2.4.jar, IntegratedTunnels-1.16.5-1.8.9.jar, DrawersTooltip-1.16.2-2.1.1.jar, MysticalCustomization-1.16.5-2.1.7.jar, lostcities-1.16-4.0.11-beta.jar, elevatorid-1.16.5-1.7.13.jar, GunpowderLib-1.16.5-1.2.2.jar, ftb-ultimine-forge-1605.3.1-build.45.jar, BetterStrongholds-1.16.4-1.2.1.jar, buildersaddition-1.16.5-20210807a.jar, Runelic-1.16.5-7.0.2.jar, starterkit_1.16.5-3.1.jar, MekanismTools-1.16.5-10.1.1.456.jar, architectury-1.29.51.jar, ftb-library-forge-1605.3.4-build.90.jar, ftb-teams-forge-1605.2.3-build.40.jar, ftb-ranks-forge-1605.1.5-build.16.jar, curiouselytra-forge-1.16.5-4.0.2.4.jar, cc-tweaked-1.16.5-1.100.2.jar, ProjectRed-1.16.5-4.11.0-core.jar, energymeter-1.16.5-1.6.1.jar, ProjectRed-1.16.5-4.11.0-exploration.jar, ProjectRed-1.16.5-4.11.0-integration.jar, ProjectRed-1.16.5-4.11.0-illumination.jar, ProjectRed-1.16.5-4.11.0-transmission.jar, light-overlay-5.8.1.jar, trashcans-1.0.12-mc1.16.jar, TrampleStopper-2.6.1-build.22+mc1.16.5.jar, smallships-1.16.5-1.10.3.jar, bwncr-1.16.5-3.10.16.jar, observable-0.2.1-forge.jar, Cyclic-1.16.5-1.5.13.jar, BetterAdvancements-1.16.5-0.1.1.115.jar, rhino-forge-1605.1.5-build.75.jar, biggerreactors-1.16.5-0.5.1.jar, Cucumber-1.16.5-4.1.12.jar, TrashSlot_1.16.3-12.2.1.jar, pamhc2trees-1.16.3-1.0.1.jar, flatbedrock-1.2.0-build.2+mc1.16.5.jar, craftingstation-4.2.jar, item-filters-forge-1605.2.5-build.9.jar, elementalcraft-1.16.5-2.7.14.jar, platforms-1.16-1.7.12.jar, metalbarrels-1.16.2-3.3b.jar, abnormals_core-1.16.5-3.3.1.jar, upgrade_aquatic-1.16.5-3.1.2.jar, ponderjs-1.16.5-1.0.3d.jar, ae2extras-1.3.1-1.16.5.jar, ensorcellation-1.16.5-1.4.1.2.jar, create-mc1.16.5_v0.3.2g.jar, ZYCraft-1.16.5-3.1.34.jar, Waystones_1.16.5-7.6.4.jar, Clumps-6.0.0.27.jar, enviromats-1.16.5-2.0.9.0.jar, comforts-forge-1.16.5-4.0.1.3.jar, appliedenergistics2-8.4.7.jar, lazierae2-1.16.5-1.1.4.jar, Artifacts-1.16.5-2.10.4.jar, framedcompactdrawers-1.16-2.2.1.jar, configured-1.5.1-1.16.5.jar, DimStorage-1.16.5-4.4.1.jar, DungeonCrawl-1.16.5-2.3.5.jar, demagnetize-forge-1.16.2-1.2.2.jar, TravelAnchors-2.4.jar, lazydfu-0.1.3.jar, mcjtylib-1.16-5.1.3.jar, rftoolsbase-1.16-2.1.2.jar, xnet-1.16-3.0.16.jar, rftoolsdim-1.16-7.0.20-beta.jar, rftoolspower-1.16-3.0.13.jar, rftoolsbuilder-1.16-3.1.5.jar, rftoolsstorage-1.16-2.0.17.jar, rftoolscontrol-1.16-4.0.14.jar, restrictions-1.16-3.0.6.jar, ExplorersCompass-1.16.5-1.1.2-forge.jar, mahoutsukai-1.16.5-v1.34.7.jar, ToastControl-1.16.5-4.4.0.jar, mininggadgets-1.7.5.jar, EnderStorage-1.16.5-2.8.0.168-universal.jar, AkashicTome-1.4-16.jar, ftb-chunks-forge-1605.3.2-build.115.jar, kubejs-forge-1605.3.19-build.289.jar, kubejs-thermal-1605.1.4-build.4.jar, ftb-quests-forge-1605.3.6-build.76.jar, kubejs-create-1605.1.4-build.12.jar, kubejs-mekanism-1605.1.2-build.2.jar, BloodMagic-1.16.4-3.1.7-27.jar, tomeofblood-1.16.5-1.2.3.jar, kubejs-blood-magic-1605.1.1-build.3.jar, scuba-gear-1.16.5-1.0.3.jar, BrandonsCore-1.16.5-3.0.11.238-universal.jar, Draconic-Evolution-1.16.5-3.0.19.432-universal.jar, immersiveposts-1.16.5-4.2.2.jar, ImmersiveEngineering-1.16.5-5.0.7-143.jar, kubejs-immersive-engineering-1605.1.2-build.28.jar, selene-1.16.5-1.9.0.jar, MysticalAgriculture-1.16.5-4.2.6.jar, MysticalAgradditions-1.16.5-4.2.4.jar, sounddeviceoptions-1.4.3.jar, CraftingTweaks_1.16.5-12.2.1.jar, TConstruct-1.16.5-3.3.3.332.jar, rftoolsutility-1.16-3.1.10.jar, EnchantmentDescriptions-1.16.5-7.0.18.jar, ToolBelt-1.16.5-1.16.0.jar, titanium-1.16.5-3.2.8.7-22.jar, mana-and-artifice-1.5.1.6.jar, silent-lib-1.16.3-4.9.6.jar, Exchangers-1.16.5-3.0.2.jar, ctiers-1.16.5-1.36.jar, archers_paradox-1.16.5-1.4.0.1.jar, omgourd-1.16.5-1.4.0.1.jar, enviroenergy-1.16.5-3.0.9.1.jar, Iceberg-1.16.5-1.0.38.jar, Quark-r2.4-321.jar, LegendaryTooltips-1.16.5-1.1.6.jar, creativewirelesstransmitter-1.16x-1.12.jar, FastWorkbench-1.16.5-4.6.1.jar, StorageDrawers-1.16.3-8.5.1.jar, topaddons-1.16.5-2.2.0-beta.jar, FluxNetworks-1.16.5-6.2.1.14.jar, enderchests-1.16-1.7.9.jar, minecolonies-1.16.5-1.0.352-BETA.jar, pylons-1.0.4.jar, ferritecore-2.1.0-forge.jar, engineersdecor-1.16.5-1.1.16.jar, Chisel-MC1.16.5-2.0.1-alpha.4.jar, SoL-Carrot-1.16.5-1.10.1.jar, modular-routers-1.16.5-7.5.2-83.jar, refinedstorageaddons-0.7.4.jar, expandability-2.0.1-forge.jar, botanicalmachinery-1.16.4-0.4.4.jar, valhelsia_core-16.0.13a.jar, forbidden_arcanus-16.2.2.jar, overloadedarmorbar-5.1.0.jar, Morph-o-Tool-1.4-27.jar, Translocators-1.16.5-2.6.0.82-universal.jar, flickerfix-1.0.1.jar, createaddition-1.16.5-20220129a.jar, balancedenchanting-1.16.2-1.1.jar, resourcefulbees:internals, Solar Flux Generated Resources, torohealth-1.16.4-forge-4.jar, KubeJS Resource Pack [data], KubeJS Virtual Data Pack [high priority]
[18:45:13] [main/INFO]: [blocks] Found 1753 tags, added 2563 objects, removed 46 objects
[18:45:13] [main/INFO]: [blocks] Found 1753 tags, added 0 objects, removed 0 objects
[18:45:13] [main/ERROR]: Couldn't load block tag farmersdelight:mushroom_colony_growable_on as it is missing following references: supplementaries:planter_rich (from supplementaries-1.16.5-0.18.2.jar)
[18:45:17] [main/INFO]: [items] Found 3764 tags, added 1973 objects, removed 23 objects
[18:45:17] [main/INFO]: [items] Found 3764 tags, added 0 objects, removed 0 objects
[18:45:17] [main/ERROR]: Couldn't load item tag forge:marble as it is missing following references: #enviromats:marble (from enviromats-1.16.5-2.0.9.0.jar)
[18:45:17] [main/ERROR]: Couldn't load item tag forge:granodiorite as it is missing following references: #enviromats:granodiorite (from enviromats-1.16.5-2.0.9.0.jar)
[18:45:17] [main/ERROR]: Couldn't load item tag forge:hardened_stone as it is missing following references: #enviromats:hardened_stone (from enviromats-1.16.5-2.0.9.0.jar)
[18:45:17] [main/ERROR]: Couldn't load item tag forge:basalt as it is missing following references: #enviromats:basalt (from enviromats-1.16.5-2.0.9.0.jar)
[18:45:17] [main/ERROR]: Couldn't load item tag forge:pumice as it is missing following references: #enviromats:pumice (from enviromats-1.16.5-2.0.9.0.jar)
[18:45:17] [main/ERROR]: Couldn't load item tag forge:travertine as it is missing following references: #enviromats:travertine (from enviromats-1.16.5-2.0.9.0.jar)
[18:45:17] [main/INFO]: [fluids] Found 165 tags, added 67 objects, removed 0 objects
[18:45:17] [main/INFO]: [fluids] Found 165 tags, added 0 objects, removed 0 objects
[18:45:17] [main/INFO]: [entity_types] Found 46 tags, added 202 objects, removed 0 objects
[18:45:17] [main/INFO]: [entity_types] Found 46 tags, added 0 objects, removed 0 objects
[18:45:17] [main/INFO]: [tunnel_types] Found 0 tags, added 0 objects, removed 0 objects
[18:45:17] [main/INFO]: [tunnel_types] Found 0 tags, added 0 objects, removed 0 objects
[18:45:17] [main/INFO]: [potions] Found 0 tags, added 0 objects, removed 0 objects
[18:45:17] [main/INFO]: [potions] Found 0 tags, added 0 objects, removed 0 objects
[18:45:17] [main/INFO]: [pigments] Found 0 tags, added 0 objects, removed 0 objects
[18:45:17] [main/INFO]: [pigments] Found 0 tags, added 0 objects, removed 0 objects
[18:45:17] [main/INFO]: [enchantments] Found 1 tags, added 0 objects, removed 0 objects
[18:45:17] [main/INFO]: [enchantments] Found 1 tags, added 0 objects, removed 0 objects
[18:45:17] [main/INFO]: [tile_entity_types] Found 5 tags, added 0 objects, removed 0 objects
[18:45:17] [main/INFO]: [tile_entity_types] Found 5 tags, added 0 objects, removed 0 objects
[18:45:17] [main/INFO]: [slurries] Found 2 tags, added 0 objects, removed 0 objects
[18:45:17] [main/INFO]: [slurries] Found 2 tags, added 0 objects, removed 0 objects
[18:45:17] [main/INFO]: [infuse_types] Found 8 tags, added 0 objects, removed 0 objects
[18:45:17] [main/INFO]: [infuse_types] Found 8 tags, added 0 objects, removed 0 objects
[18:45:17] [main/INFO]: [gases] Found 5 tags, added 0 objects, removed 0 objects
[18:45:17] [main/INFO]: [gases] Found 5 tags, added 0 objects, removed 0 objects
[18:45:17] [main/INFO]: Loot Modification Manager has loaded 0 sets of modifiers
[18:45:17] [main/WARN]: Failed to parse recipe 'thermal:compat/mysticalagriculture/insolator_mysticalag_zombie_pigman_seeds[thermal:insolator]'! Falling back to vanilla: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_zombie_pigman_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:45:17] [main/WARN]: Failed to parse recipe thermal:compat/mysticalagriculture/insolator_mysticalag_zombie_pigman_seeds[thermal:insolator]: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_zombie_pigman_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:45:17] [main/INFO]: Received new training data for mana-and-artifice:manaweave_patterns/circle
[18:45:18] [main/WARN]: Failed to parse recipe 'thermal:compat/appliedenergistics2/ae2_ender_pearl_dust_convert[minecraft:crafting_shapeless]'! Falling back to vanilla: com.google.gson.JsonSyntaxException: Unknown item tag 'thermal:ender_pearl_dust'
[18:45:18] [main/WARN]: Failed to parse recipe thermal:compat/appliedenergistics2/ae2_ender_pearl_dust_convert[minecraft:crafting_shapeless]: com.google.gson.JsonSyntaxException: Unknown item tag 'thermal:ender_pearl_dust'
[18:45:18] [main/INFO]: ignoring heat properties for block occultism:spirit_fire: mod not loaded
[18:45:18] [main/WARN]: Failed to parse recipe 'thermal:compat/mysticalagriculture/insolator_mysticalag_phantom_seeds[thermal:insolator]'! Falling back to vanilla: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_phantom_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:45:18] [main/WARN]: Failed to parse recipe thermal:compat/mysticalagriculture/insolator_mysticalag_phantom_seeds[thermal:insolator]: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_phantom_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:45:18] [main/INFO]: Received new training data for mana-and-artifice:manaweave_patterns/star
[18:45:18] [main/WARN]: Failed to parse recipe 'thermal:compat/mysticalagriculture/insolator_mysticalag_villager_seeds[thermal:insolator]'! Falling back to vanilla: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_villager_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:45:18] [main/WARN]: Failed to parse recipe thermal:compat/mysticalagriculture/insolator_mysticalag_villager_seeds[thermal:insolator]: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_villager_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:45:18] [main/WARN]: Failed to parse recipe 'mana-and-artifice:decoration/stonecutting/redstone_arcane_stone_reset_stonecutter[minecraft:stonecutting]'! Falling back to vanilla: com.google.gson.JsonSyntaxException: Unknown item tag 'mana-and-artifice:stonecutter_resettable_redstone_arcane_stones'
[18:45:18] [main/WARN]: Failed to parse recipe mana-and-artifice:decoration/stonecutting/redstone_arcane_stone_reset_stonecutter[minecraft:stonecutting]: com.google.gson.JsonSyntaxException: Unknown item tag 'mana-and-artifice:stonecutter_resettable_redstone_arcane_stones'
[18:45:18] [main/WARN]: Failed to parse recipe 'thermal:compat/mysticalagriculture/insolator_mysticalag_wolf_seeds[thermal:insolator]'! Falling back to vanilla: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_wolf_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:45:18] [main/WARN]: Failed to parse recipe thermal:compat/mysticalagriculture/insolator_mysticalag_wolf_seeds[thermal:insolator]: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_wolf_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:45:18] [main/INFO]: Received new training data for mana-and-artifice:manaweave_patterns/slash
[18:45:18] [main/WARN]: Failed to parse recipe 'thermal:compat/mysticalagriculture/insolator_mysticalag_polar_bear_seeds[thermal:insolator]'! Falling back to vanilla: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_polar_bear_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:45:18] [main/WARN]: Failed to parse recipe thermal:compat/mysticalagriculture/insolator_mysticalag_polar_bear_seeds[thermal:insolator]: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_polar_bear_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:45:18] [main/WARN]: Failed to parse recipe 'thermal:compat/mysticalagriculture/insolator_mysticalag_llama_seeds[thermal:insolator]'! Falling back to vanilla: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_llama_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:45:18] [main/WARN]: Failed to parse recipe thermal:compat/mysticalagriculture/insolator_mysticalag_llama_seeds[thermal:insolator]: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_llama_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:45:18] [main/WARN]: Failed to parse recipe 'thermal:compat/mysticalagriculture/insolator_mysticalag_stray_seeds[thermal:insolator]'! Falling back to vanilla: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_stray_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:45:18] [main/WARN]: Failed to parse recipe thermal:compat/mysticalagriculture/insolator_mysticalag_stray_seeds[thermal:insolator]: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_stray_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:45:18] [main/WARN]: Recipe mana-and-artifice:multiblock/eldrin_altar does not define a tier, defaulting to 1.
[18:45:18] [main/WARN]: Failed to parse recipe 'thermal:compat/mysticalagriculture/insolator_mysticalag_vex_seeds[thermal:insolator]'! Falling back to vanilla: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_vex_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:45:18] [main/WARN]: Failed to parse recipe thermal:compat/mysticalagriculture/insolator_mysticalag_vex_seeds[thermal:insolator]: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_vex_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:45:18] [main/WARN]: Failed to parse recipe 'thermal:fuels/compression/compression_creosote[thermal:compression_fuel]': {"fluid_tag":"forge:creosote","amount":1000} is not a valid ingredient!
[18:45:18] [main/INFO]: Received new training data for mana-and-artifice:manaweave_patterns/backslash
[18:45:18] [main/INFO]: Received new training data for mana-and-artifice:manaweave_patterns/split_triangle
[18:45:18] [main/INFO]: Received new training data for mana-and-artifice:manaweave_patterns/knot
[18:45:18] [main/WARN]: Failed to parse recipe 'mana-and-artifice:runeforging/stone_pedestal_with_sign[minecraft:crafting_shapeless]'! Falling back to vanilla: com.google.gson.JsonParseException: An ingredient entry is either a tag or an item, not both
[18:45:18] [main/WARN]: Failed to parse recipe mana-and-artifice:runeforging/stone_pedestal_with_sign[minecraft:crafting_shapeless]: com.google.gson.JsonParseException: An ingredient entry is either a tag or an item, not both
[18:45:18] [main/WARN]: Failed to parse recipe 'thermal:compat/mysticalagriculture/insolator_mysticalag_evoker_seeds[thermal:insolator]'! Falling back to vanilla: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_evoker_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:45:18] [main/WARN]: Failed to parse recipe thermal:compat/mysticalagriculture/insolator_mysticalag_evoker_seeds[thermal:insolator]: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_evoker_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:45:18] [main/WARN]: Failed to parse recipe 'thermal:compat/mysticalagriculture/insolator_mysticalag_magma_cube_seeds[thermal:insolator]'! Falling back to vanilla: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_magma_cube_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:45:18] [main/WARN]: Failed to parse recipe thermal:compat/mysticalagriculture/insolator_mysticalag_magma_cube_seeds[thermal:insolator]: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_magma_cube_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:45:18] [main/WARN]: Failed to parse recipe 'thermal:compat/mysticalagriculture/insolator_mysticalag_drowned_seeds[thermal:insolator]'! Falling back to vanilla: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_drowned_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:45:18] [main/WARN]: Failed to parse recipe thermal:compat/mysticalagriculture/insolator_mysticalag_drowned_seeds[thermal:insolator]: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_drowned_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:45:18] [main/WARN]: Failed to parse recipe 'thermal:compat/mysticalagriculture/insolator_mysticalag_dolphin_seeds[thermal:insolator]'! Falling back to vanilla: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_dolphin_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:45:18] [main/WARN]: Failed to parse recipe thermal:compat/mysticalagriculture/insolator_mysticalag_dolphin_seeds[thermal:insolator]: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_dolphin_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:45:18] [main/WARN]: Failed to parse recipe 'mana-and-artifice:decoration/stonecutting/redstone_arcane_sandstone_reset_stonecutter[minecraft:stonecutting]'! Falling back to vanilla: com.google.gson.JsonSyntaxException: Unknown item tag 'mana-and-artifice:stonecutter_resettable_redstone_arcane_sandstones'
[18:45:18] [main/WARN]: Failed to parse recipe mana-and-artifice:decoration/stonecutting/redstone_arcane_sandstone_reset_stonecutter[minecraft:stonecutting]: com.google.gson.JsonSyntaxException: Unknown item tag 'mana-and-artifice:stonecutter_resettable_redstone_arcane_sandstones'
[18:45:18] [main/WARN]: Failed to parse recipe 'thermal:compat/mysticalagriculture/insolator_mysticalag_husk_seeds[thermal:insolator]'! Falling back to vanilla: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_husk_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:45:18] [main/WARN]: Failed to parse recipe thermal:compat/mysticalagriculture/insolator_mysticalag_husk_seeds[thermal:insolator]: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_husk_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:45:18] [main/INFO]: Received new training data for mana-and-artifice:manaweave_patterns/inverted_split_triangle
[18:45:18] [main/WARN]: Failed to parse recipe 'thermal:compat/mysticalagriculture/insolator_mysticalag_panda_seeds[thermal:insolator]'! Falling back to vanilla: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_panda_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:45:18] [main/WARN]: Failed to parse recipe thermal:compat/mysticalagriculture/insolator_mysticalag_panda_seeds[thermal:insolator]: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_panda_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:45:18] [main/WARN]: Failed to parse recipe 'thermal:compat/mysticalagriculture/insolator_mysticalag_vindicator_seeds[thermal:insolator]'! Falling back to vanilla: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_vindicator_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:45:18] [main/WARN]: Failed to parse recipe thermal:compat/mysticalagriculture/insolator_mysticalag_vindicator_seeds[thermal:insolator]: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_vindicator_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:45:18] [main/WARN]: Failed to parse recipe 'thermal:compat/mysticalagriculture/insolator_mysticalag_shulker_seeds[thermal:insolator]'! Falling back to vanilla: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_shulker_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:45:18] [main/WARN]: Failed to parse recipe thermal:compat/mysticalagriculture/insolator_mysticalag_shulker_seeds[thermal:insolator]: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_shulker_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:45:18] [main/INFO]: ignoring heat properties for block decorative_blocks:soul_brazier: mod not loaded
[18:45:18] [main/INFO]: Received new training data for mana-and-artifice:manaweave_patterns/infinity
[18:45:18] [main/INFO]: Received new training data for mana-and-artifice:manaweave_patterns/hourglass
[18:45:18] [main/WARN]: Failed to parse recipe 'thermal:compat/mysticalagriculture/insolator_mysticalag_ravager_seeds[thermal:insolator]'! Falling back to vanilla: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_ravager_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:45:18] [main/WARN]: Failed to parse recipe thermal:compat/mysticalagriculture/insolator_mysticalag_ravager_seeds[thermal:insolator]: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_ravager_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:45:18] [main/INFO]: ignoring heat properties for block valhelsia_structures:brazier: mod not loaded
[18:45:18] [main/WARN]: Failed to parse recipe 'thermal:compat/mysticalagriculture/insolator_mysticalag_guardian_seeds[thermal:insolator]'! Falling back to vanilla: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_guardian_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:45:18] [main/WARN]: Failed to parse recipe thermal:compat/mysticalagriculture/insolator_mysticalag_guardian_seeds[thermal:insolator]: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_guardian_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:45:18] [main/INFO]: Received new training data for mana-and-artifice:manaweave_patterns/inverted_triangle
[18:45:18] [main/INFO]: ignoring heat properties for block betterendforge:emerald_ice: mod not loaded
[18:45:18] [main/WARN]: Failed to parse recipe 'thermal:compat/mysticalagriculture/insolator_mysticalag_mooshroom_seeds[thermal:insolator]'! Falling back to vanilla: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_mooshroom_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:45:18] [main/WARN]: Failed to parse recipe thermal:compat/mysticalagriculture/insolator_mysticalag_mooshroom_seeds[thermal:insolator]: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_mooshroom_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:45:18] [main/WARN]: Failed to parse recipe 'thermal:compat/mysticalagriculture/insolator_mysticalag_horse_seeds[thermal:insolator]'! Falling back to vanilla: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_horse_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:45:18] [main/WARN]: Failed to parse recipe thermal:compat/mysticalagriculture/insolator_mysticalag_horse_seeds[thermal:insolator]: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_horse_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:45:18] [main/WARN]: Failed to parse recipe 'thermal:compat/mysticalagriculture/insolator_mysticalag_silverfish_seeds[thermal:insolator]'! Falling back to vanilla: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_silverfish_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:45:18] [main/WARN]: Failed to parse recipe thermal:compat/mysticalagriculture/insolator_mysticalag_silverfish_seeds[thermal:insolator]: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_silverfish_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:45:18] [main/INFO]: Received new training data for mana-and-artifice:manaweave_patterns/square
[18:45:18] [main/WARN]: Failed to parse recipe 'thermal:compat/mysticalagriculture/insolator_mysticalag_fox_seeds[thermal:insolator]'! Falling back to vanilla: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_fox_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:45:18] [main/WARN]: Failed to parse recipe thermal:compat/mysticalagriculture/insolator_mysticalag_fox_seeds[thermal:insolator]: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_fox_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:45:18] [main/WARN]: Recipe mana-and-artifice:multiblock/wellspring_capture does not define a tier, defaulting to 1.
[18:45:18] [main/WARN]: Failed to parse recipe 'thermal:compat/mysticalagriculture/insolator_mysticalag_endermite_seeds[thermal:insolator]'! Falling back to vanilla: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_endermite_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:45:18] [main/WARN]: Failed to parse recipe thermal:compat/mysticalagriculture/insolator_mysticalag_endermite_seeds[thermal:insolator]: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_endermite_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:45:18] [main/INFO]: Received new training data for mana-and-artifice:manaweave_patterns/knot3
[18:45:18] [main/INFO]: Received new training data for mana-and-artifice:manaweave_patterns/knot4
[18:45:18] [main/INFO]: Received new training data for mana-and-artifice:manaweave_patterns/knot2
[18:45:18] [main/WARN]: Recipe mana-and-artifice:multiblock/test_multiblock does not define a tier, defaulting to 1.
[18:45:18] [main/WARN]: Failed to parse recipe 'thermal:compat/mysticalagriculture/insolator_mysticalag_witch_seeds[thermal:insolator]'! Falling back to vanilla: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_witch_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:45:18] [main/WARN]: Failed to parse recipe thermal:compat/mysticalagriculture/insolator_mysticalag_witch_seeds[thermal:insolator]: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_witch_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:45:18] [main/WARN]: Failed to parse recipe 'thermal:compat/mysticalagriculture/insolator_mysticalag_pillager_seeds[thermal:insolator]'! Falling back to vanilla: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_pillager_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:45:18] [main/WARN]: Failed to parse recipe thermal:compat/mysticalagriculture/insolator_mysticalag_pillager_seeds[thermal:insolator]: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_pillager_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:45:18] [main/INFO]: ignoring heat properties for block betterendforge:ancient_emerald_ice: mod not loaded
[18:45:18] [main/INFO]: ignoring heat properties for block betterendforge:dense_emerald_ice: mod not loaded
[18:45:18] [main/INFO]: ignoring heat properties for block decorative_blocks:brazier: mod not loaded
[18:45:18] [main/INFO]: ignoring heat properties for block natura:nether_heat_sand: mod not loaded
[18:45:18] [main/INFO]: Received new training data for mana-and-artifice:manaweave_patterns/diamond
[18:45:18] [main/WARN]: Failed to parse recipe 'thermal:compat/mysticalagriculture/insolator_mysticalag_parrot_seeds[thermal:insolator]'! Falling back to vanilla: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_parrot_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:45:18] [main/WARN]: Failed to parse recipe thermal:compat/mysticalagriculture/insolator_mysticalag_parrot_seeds[thermal:insolator]: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_parrot_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:45:18] [main/INFO]: Received new training data for mana-and-artifice:manaweave_patterns/triangle
[18:45:18] [main/WARN]: Failed to parse recipe 'thermal:compat/mysticalagriculture/insolator_mysticalag_cat_seeds[thermal:insolator]'! Falling back to vanilla: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_cat_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:45:18] [main/WARN]: Failed to parse recipe thermal:compat/mysticalagriculture/insolator_mysticalag_cat_seeds[thermal:insolator]: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_cat_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:45:18] [main/WARN]: Failed to parse recipe 'thermal:compat/mysticalagriculture/insolator_mysticalag_bat_seeds[thermal:insolator]'! Falling back to vanilla: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_bat_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:45:18] [main/WARN]: Failed to parse recipe thermal:compat/mysticalagriculture/insolator_mysticalag_bat_seeds[thermal:insolator]: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_bat_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:45:18] [main/INFO]: Found 37471 recipes and 0 failed recipes in 1.390 s
[18:45:30] [main/INFO]: Posted recipe events in 11.54 s
[18:45:30] [main/INFO]: Received new training data for mana-and-artifice:manaweave_patterns/circle
[18:45:30] [main/INFO]: Received new training data for mana-and-artifice:manaweave_patterns/star
[18:45:30] [main/INFO]: Received new training data for mana-and-artifice:manaweave_patterns/slash
[18:45:30] [main/WARN]: Recipe mana-and-artifice:multiblock/eldrin_altar does not define a tier, defaulting to 1.
[18:45:30] [main/INFO]: Received new training data for mana-and-artifice:manaweave_patterns/backslash
[18:45:30] [main/INFO]: Received new training data for mana-and-artifice:manaweave_patterns/split_triangle
[18:45:30] [main/INFO]: Received new training data for mana-and-artifice:manaweave_patterns/knot
[18:45:30] [main/INFO]: Received new training data for mana-and-artifice:manaweave_patterns/inverted_split_triangle
[18:45:30] [main/INFO]: Received new training data for mana-and-artifice:manaweave_patterns/infinity
[18:45:30] [main/INFO]: Received new training data for mana-and-artifice:manaweave_patterns/hourglass
[18:45:30] [main/INFO]: Received new training data for mana-and-artifice:manaweave_patterns/inverted_triangle
[18:45:30] [main/INFO]: Received new training data for mana-and-artifice:manaweave_patterns/square
[18:45:30] [main/WARN]: Recipe mana-and-artifice:multiblock/wellspring_capture does not define a tier, defaulting to 1.
[18:45:30] [main/INFO]: Received new training data for mana-and-artifice:manaweave_patterns/knot3
[18:45:30] [main/INFO]: Received new training data for mana-and-artifice:manaweave_patterns/knot4
[18:45:30] [main/INFO]: Received new training data for mana-and-artifice:manaweave_patterns/knot2
[18:45:30] [main/WARN]: Recipe mana-and-artifice:multiblock/test_multiblock does not define a tier, defaulting to 1.
[18:45:30] [main/INFO]: Received new training data for mana-and-artifice:manaweave_patterns/diamond
[18:45:30] [main/INFO]: Received new training data for mana-and-artifice:manaweave_patterns/triangle
[18:45:30] [main/INFO]: Modified & removed recipes in 336.5 ms
[18:45:30] [main/INFO]: Added recipes in 115.4 ms
[18:45:30] [main/INFO]: Added 1722 recipes, removed 1336 recipes, modified 7877 recipes, with 0 failed recipes and 0 fall-backed recipes
[18:45:31] [main/INFO]: Advancement Modification Manager has loaded 8 sets of modifiers
[18:45:31] [main/INFO]: Injecting loot table 'silentgear:inject/chests/bastion_bridge' into 'minecraft:chests/bastion_bridge'
[18:45:31] [main/INFO]: Injecting loot table 'silentgear:inject/chests/bastion_other' into 'minecraft:chests/bastion_other'
[18:45:32] [main/INFO]: Injecting loot table 'silentgear:inject/chests/bastion_treasure' into 'minecraft:chests/bastion_treasure'
[18:45:32] [main/INFO]: Injecting loot table 'silentgear:inject/entities/spider' into 'minecraft:entities/spider'
[18:45:33] [main/INFO]: Injecting loot table 'silentgear:inject/chests/ruined_portal' into 'minecraft:chests/ruined_portal'
[18:45:34] [main/INFO]: Injecting loot table 'silentgear:inject/entities/cave_spider' into 'minecraft:entities/cave_spider'
[18:45:34] [main/INFO]: Registered 18 additional loot tables.
[18:45:34] [main/INFO]: [functions] Found 0 tags, added 0 objects, removed 0 objects
[18:45:34] [main/INFO]: [functions] Found 0 tags, added 0 objects, removed 0 objects
[18:45:34] [main/ERROR]: Parsing error loading custom advancement twilightforest:alt/compat/tconstruct: Unknown item id 'tconstruct:book'
[18:45:34] [main/ERROR]: Parsing error loading custom advancement pedestals:main/craft_filter: Expected item to be an item, was unknown string 'pedestals:coin/filteritemstack'
[18:45:34] [main/INFO]: Loaded 12913 advancements
[18:45:34] [main/INFO]: Registered 53 additional recipes.
[18:45:34] [main/INFO]: Reloading HammerLib recipes...
[18:45:34] [main/INFO]: HammerLib injected 25 recipes into recipe map.
[18:45:34] [main/INFO]: Reloading 1 custom registries.
[18:45:34] [main/INFO]: 1 custom registries reloaded, added 0 total recipes.
[18:45:34] [main/INFO]: Registered 25 additional recipes.
[18:45:34] [main/INFO]: Loading comb recipes for 85 bees...
[18:45:34] [main/INFO]: Validating Honey Effects...
[18:45:34] [main/INFO]: Validating Honey Effects...
[18:45:34] [main/INFO]: Loaded 28 affix loot entries from resources.
[18:45:34] [main/INFO]: Registered 6 boss gear sets.
[18:45:34] [main/INFO]: Loaded 6 boss items from resources.
[18:45:34] [main/INFO]: Loaded 8 spawner items from resources.
[18:45:35] [main/INFO]: Loading Distillation Recipes.
[18:45:35] [main/INFO]: Loading Reservoirs.
[18:45:35] [main/INFO]: Loading Coker-Unit Recipes.
[18:45:35] [main/INFO]: Loading Sulfur Recovery Recipes.
[18:45:35] [main/INFO]: Reloading trait files
[18:45:35] [main/INFO]: Registered 74 traits
[18:45:35] [main/INFO]: Reloading part files
[18:45:35] [main/INFO]: Registered part serializer 'silentgear:compound_part'
[18:45:35] [main/INFO]: Registered part serializer 'silentgear:misc_upgrade'
[18:45:35] [main/INFO]: Registered 45 parts
[18:45:35] [main/INFO]: Reloading material files
[18:45:35] [main/INFO]: Registered material serializer 'silentgear:standard'
[18:45:35] [main/INFO]: Registered material serializer 'silentgear:compound'
[18:45:35] [main/INFO]: Registered material serializer 'silentgear:custom_compound'
[18:45:35] [main/INFO]: Registered material serializer 'silentgear:crafted'
[18:45:35] [main/INFO]: Skipped loading 7 material(s), as their conditions were not met. This is usually NOT an error!
[18:45:35] [main/INFO]: Skipped materials: silentgear:aluminum_steel, silentgear:bismuth, silentgear:bismuth_brass, silentgear:bismuth_steel, silentgear:redstone_alloy, silentgear:refined_iron, silentgear:titanium
[18:45:35] [main/INFO]: Beginning loading of data for data loader: tiny_block_overrides
[18:45:35] [main/INFO]: Data loader for tiny_block_overrides loaded 1 jsons
[18:45:36] [main/INFO]: ExoticDrops rolls:1 chance:15.0 weights:[4, 4, 2, 1, 1]
[18:45:37] [main/INFO]: Loaded 16 elementalcraft:shrine_upgrades
[18:45:37] [main/INFO]: Loaded 37 elementalcraft:tool_infusions
[18:45:37] [main/INFO]: Loaded 10 elementalcraft:runes
[18:45:37] [main/INFO]: Loaded 16 elementalcraft:spell_properties
[18:45:37] [main/INFO]: [il_tags/elementalcraft_runes] Found 3 tags, added 0 objects, removed 0 objects
[18:45:37] [main/INFO]: [il_tags/elementalcraft_runes] Found 3 tags, added 0 objects, removed 0 objects
[18:45:37] [main/INFO]: Loaded 1 DataPack Anvil TagCollection
[18:45:37] [main/INFO]: Built PerkTree with 417 perks!
[18:45:37] [main/INFO]: Loading data...
[18:45:39] [main/INFO]: Done.
[18:45:40] [main/INFO]: Couldn't fully analyze 1 compressed_iron_chestplate, missing knowledge for {1 leather_chestplate=1.0}
[18:45:40] [main/INFO]: Couldn't fully analyze 1 compressed_iron_boots, missing knowledge for {1 leather_boots=1.0}
[18:45:40] [main/INFO]: Couldn't fully analyze 1 mattock_nether, missing knowledge for {1 mattock=1.0}
[18:45:40] [main/INFO]: Couldn't fully analyze 1 alfsteel_aiot, missing knowledge for {1 alfsteel_aiot=1.0}
[18:45:40] [main/INFO]: Couldn't fully analyze 1 pneumatic_leggings, missing knowledge for {1 compressed_iron_leggings=1.0}
[18:45:40] [main/INFO]: Couldn't fully analyze 1 compressed_iron_helmet, missing knowledge for {1 leather_helmet=1.0}
[18:45:40] [main/INFO]: Couldn't fully analyze 1 creative_jetpack, missing knowledge for {1 unobtainium_jetpack=1.0}
[18:45:40] [main/INFO]: Couldn't fully analyze 1 compressed_iron_leggings, missing knowledge for {1 leather_leggings=1.0}
[18:45:40] [main/INFO]: Couldn't fully analyze 1 platinum_jetpack, missing knowledge for {1 electrum_jetpack=1.0}
[18:45:40] [main/INFO]: Finished recipe profiler for Arc Recycling, took 724 milliseconds
[18:45:40] [main/INFO]: Beginning load of custom recipes for colony workers
[18:45:40] [main/INFO]: Loaded 464 recipes for 14 crafters
[18:45:40] [main/INFO]: Beginning load of research for University.
[18:45:40] [main/INFO]: Loaded 184 recipes for 4 research branches
[18:45:40] [main/INFO]: Loaded 18 recipes
[18:45:40] [main/INFO]: Registered 11 blocks with enchanting stats.
[18:45:40] [main/INFO]: Loaded 13 normal and 13 rare Wandering Trader trade options.
[18:45:40] [main/INFO]: Loaded cucumber-tags.json in 1 ms
[18:45:40] [main/INFO]: 69 materials loaded
[18:45:40] [main/INFO]: 153 stats loaded for 70 materials
[18:45:41] [main/INFO]: Recipes for potions: eidolon:long_anchored, potionsmaster:uranium_sight, minecraft:water_breathing, apotheosis:long_resistance, upgrade_aquatic:vibing_long, cyclic:strong_haste, upgrade_aquatic:vibing, potionsmaster:iron_sight, mana-and-artifice:light_mana_potion, minecraft:strong_slowness, minecraft:long_invisibility, minecraft:long_slow_falling, apotheosis:long_haste, minecraft:strength, potionsmaster:copper_sight, cyclic:levitation, quark:long_resistance, minecraft:long_regeneration, potionsmaster:zinc_sight, quark:long_danger_sight, potionsmaster:nickel_sight, minecraft:fire_resistance, minecraft:harming, apotheosis:haste, upgrade_aquatic:restfulness_strong, cyclic:resistance, cyclic:wither, ars_nouveau:spell_damage, ars_nouveau:spell_damage_long, minecraft:strong_strength, apotheosis:wither, minecraft:long_strength, upgrade_aquatic:insomnia, minecraft:strong_regeneration, minecraft:strong_swiftness, apotheosis:sundering, potionsmaster:unobtainium_sight, apotheosis:knowledge, mana-and-artifice:superior_mana_potion, minecraft:long_poison, ars_nouveau:mana_regen_potion_long, quark:resistance, quark:long_resilience, potionsmaster:netherite_sight, upgrade_aquatic:vibing_strong, potionsmaster:tin_sight, quark:strong_resistance, upgrade_aquatic:repellence, apotheosis:strong_knowledge, minecraft:long_slowness, cyclic:swimspeed, minecraft:invisibility, minecraft:slow_falling, minecraft:long_weakness, minecraft:mundane, minecraft:strong_healing, mana-and-artifice:minor_mana_potion, minecraft:regeneration, upgrade_aquatic:restfulness, resourcefulbees:calming, potionsmaster:silver_sight, resourcefulbees:long_calming, eidolon:chilled, upgrade_aquatic:repellence_strong, potionsmaster:diamond_sight, minecraft:poison, minecraft:long_water_breathing, minecraft:night_vision, apotheosis:strong_sundering, apotheosis:long_fatigue, potionsmaster:osmium_sight, minecraft:luck, apotheosis:absorption, upgrade_aquatic:repellence_long, potionsmaster:lead_sight, minecraft:strong_turtle_master, cyclic:stun, minecraft:long_fire_resistance, apotheosis:long_sundering, eidolon:anchored, potionsmaster:aluminium_sight, minecraft:turtle_master, minecraft:water, potionsmaster:crimsoniron_sight, minecraft:long_night_vision, apotheosis:fatigue, minecraft:swiftness, apotheosis:long_wither, minecraft:long_turtle_master, apotheosis:strong_fatigue, minecraft:strong_leaping, apotheosis:strong_wither, apotheosis:strong_haste, ars_nouveau:spell_damage_strong, potionsmaster:bismuth_sight, minecraft:thick, minecraft:long_leaping, minecraft:healing, minecraft:strong_harming, potionsmaster:allthemodium_sight, potionsmaster:vibranium_sight, apotheosis:resistance, potionsmaster:lapis_sight, potionsmaster:platinum_sight, potionsmaster:emerald_sight, upgrade_aquatic:insomnia_strong, minecraft:slowness, cyclic:haste, minecraft:long_swiftness, minecraft:strong_poison, quark:resilience, minecraft:weakness, quark:danger_sight, minecraft:leaping, apotheosis:strong_absorption, ars_nouveau:mana_regen_potion_strong, potionsmaster:coal_sight, apotheosis:strong_resistance, mana-and-artifice:greater_mana_potion, apotheosis:long_absorption, ars_nouveau:mana_regen_potion, mana-and-artifice:mana_potion, minecraft:awkward, apotheosis:long_knowledge, potionsmaster:redstone_sight, potionsmaster:gold_sight, quark:strong_resilience, cyclic:blind, eidolon:long_chilled, cyclic:hunger, potionsmaster:quartz_sight
[18:45:44] [main/INFO]: Loading vanilla base decorator
[18:46:00] [main/INFO]: Adding DataPackFinder
[18:46:00] [main/INFO]: Registering /terra command
[18:46:00] [main/INFO]: onRegisterCommandsEvent
[18:46:00] [main/INFO]: Loading command nodes...
[18:46:00] [main/INFO]: Loaded 2901 command nodes
[18:46:00] [main/INFO]: Adding Reload Listener: 'resourcefulbees recipe manager'
[18:46:01] [main/INFO]: SourceFile:407: Loaded script server_scripts:mod_specific/envirotech/envirotech.js in 0.002 s
[18:46:01] [main/INFO]: SourceFile:407: Loaded script server_scripts:tags.js in 0.001 s
[18:46:01] [main/INFO]: SourceFile:407: Loaded script server_scripts:unify.js in 0.003 s
[18:46:01] [main/INFO]: SourceFile:407: Loaded script server_scripts:constants.js in 0.001 s
[18:46:01] [main/INFO]: SourceFile:407: Loaded script server_scripts:advanced_interactions/atm_shards.js in 0.001 s
[18:46:01] [main/INFO]: SourceFile:407: Loaded script server_scripts:advanced_interactions/multiblock.js in 0.001 s
[18:46:01] [main/INFO]: SourceFile:407: Loaded script server_scripts:advanced_interactions/turtles.js in 0.0 s
[18:46:01] [main/INFO]: SourceFile:407: Loaded script server_scripts:mod_specific/akashic_tome/akashic_tome.js in 0.001 s
[18:46:01] [main/INFO]: SourceFile:407: Loaded script server_scripts:mod_specific/angelring/angelring.js in 0.0 s
[18:46:01] [main/INFO]: SourceFile:407: Loaded script server_scripts:mod_specific/apotheosis/apotheosis.js in 0.0 s
[18:46:01] [main/INFO]: SourceFile:407: Loaded script server_scripts:mod_specific/applied_energistics2/applied_energistics2.js in 0.001 s
[18:46:01] [main/INFO]: SourceFile:407: Loaded script server_scripts:mod_specific/ars_nouveau/ars.js in 0.0 s
[18:46:01] [main/INFO]: SourceFile:407: Loaded script server_scripts:mod_specific/astralsorcery/astralsorcery.js in 0.0 s
[18:46:01] [main/INFO]: SourceFile:407: Loaded script server_scripts:mod_specific/bagofyurting/bagofyurting.js in 0.0 s
[18:46:01] [main/INFO]: SourceFile:407: Loaded script server_scripts:mod_specific/biggerreactors/biggerreactors.js in 0.0 s
[18:46:01] [main/INFO]: SourceFile:407: Loaded script server_scripts:mod_specific/biomesoplenty/biomesoplenty.js in 0.0 s
[18:46:01] [main/INFO]: SourceFile:407: Loaded script server_scripts:mod_specific/botania/botania.js in 0.001 s
[18:46:01] [main/INFO]: SourceFile:407: Loaded script server_scripts:mod_specific/botania/mjollnir.js in 0.0 s
[18:46:01] [main/INFO]: SourceFile:407: Loaded script server_scripts:mod_specific/botany_pots/botany_pots.js in 0.001 s
[18:46:01] [main/INFO]: SourceFile:407: Loaded script server_scripts:mod_specific/buildinggadgets/buildinggadgets.js in 0.0 s
[18:46:01] [main/INFO]: SourceFile:407: Loaded script server_scripts:mod_specific/byg/byg.js in 0.0 s
[18:46:01] [main/INFO]: SourceFile:407: Loaded script server_scripts:mod_specific/comforts/comforts.js in 0.001 s
[18:46:01] [main/INFO]: SourceFile:407: Loaded script server_scripts:mod_specific/compact_machines/compct_machines.js in 0.0 s
[18:46:01] [main/INFO]: SourceFile:407: Loaded script server_scripts:mod_specific/computercraft/computercraft.js in 0.0 s
[18:46:01] [main/INFO]: SourceFile:407: Loaded script server_scripts:mod_specific/create/create.js in 0.0 s
[18:46:01] [main/INFO]: SourceFile:407: Loaded script server_scripts:mod_specific/cyclic/cyclic.js in 0.0 s
[18:46:01] [main/INFO]: SourceFile:407: Loaded script server_scripts:mod_specific/entangled/entangled.js in 0.0 s
[18:46:01] [main/INFO]: SourceFile:407: Loaded script server_scripts:mod_specific/explorerscompass/explorerscompass.js in 0.0 s
[18:46:01] [main/INFO]: SourceFile:407: Loaded script server_scripts:mod_specific/forbidden_arcanus/forbidden_arcanus.js in 0.0 s
[18:46:01] [main/INFO]: SourceFile:407: Loaded script server_scripts:mod_specific/framedblocks/framedblocks.js in 0.0 s
[18:46:01] [main/INFO]: SourceFile:407: Loaded script server_scripts:mod_specific/iceandfire/iceandfire.js in 0.001 s
[18:46:01] [main/INFO]: SourceFile:407: Loaded script server_scripts:mod_specific/immersive_engineering/cloche.js in 0.0 s
[18:46:01] [main/INFO]: SourceFile:407: Loaded script server_scripts:mod_specific/immersive_engineering/immersive_engineering.js in 0.0 s
[18:46:01] [main/INFO]: SourceFile:407: Loaded script server_scripts:mod_specific/integrated_dynamics/integrated_dynamics.js in 0.001 s
[18:46:01] [main/INFO]: SourceFile:407: Loaded script server_scripts:mod_specific/iron_jetpacks/iron_jetpacks.js in 0.0 s
[18:46:01] [main/INFO]: SourceFile:407: Loaded script server_scripts:mod_specific/macaw/macaw.js in 0.0 s
[18:46:01] [main/INFO]: SourceFile:407: Loaded script server_scripts:mod_specific/mekanism/mekanism.js in 0.001 s
[18:46:01] [main/INFO]: SourceFile:407: Loaded script server_scripts:mod_specific/metalbarrels/metalbarrels.js in 0.0 s
[18:46:01] [main/INFO]: SourceFile:407: Loaded script server_scripts:mod_specific/mininggadgets/mininggadgets.js in 0.0 s
[18:46:01] [main/INFO]: SourceFile:407: Loaded script server_scripts:mod_specific/mysticalagriculture/mysticalagriculture.js in 0.001 s
[18:46:01] [main/INFO]: SourceFile:407: Loaded script server_scripts:mod_specific/pams_harvestcraft/pams.js in 0.0 s
[18:46:01] [main/INFO]: SourceFile:407: Loaded script server_scripts:mod_specific/pedestals/pedestals.js in 0.0 s
[18:46:01] [main/INFO]: SourceFile:407: Loaded script server_scripts:mod_specific/pneumaticcraft/pneumaticcraft.js in 0.0 s
[18:46:01] [main/INFO]: SourceFile:407: Loaded script server_scripts:mod_specific/powah/powah.js in 0.001 s
[18:46:01] [main/INFO]: SourceFile:407: Loaded script server_scripts:mod_specific/projectred/projectred.js in 0.0 s
[18:46:01] [main/INFO]: SourceFile:407: Loaded script server_scripts:mod_specific/quark/quark.js in 0.0 s
[18:46:01] [main/INFO]: SourceFile:407: Loaded script server_scripts:mod_specific/quarryplus/quarryplus.js in 0.001 s
[18:46:01] [main/INFO]: SourceFile:407: Loaded script server_scripts:mod_specific/refinedstorage/refinedstorage.js in 0.001 s
[18:46:01] [main/INFO]: SourceFile:407: Loaded script server_scripts:mod_specific/resourcefulbees/comb_recipes.js in 0.0 s
[18:46:01] [main/INFO]: SourceFile:407: Loaded script server_scripts:mod_specific/resourcefulbees/resourcefulbees.js in 0.0 s
[18:46:01] [main/INFO]: SourceFile:407: Loaded script server_scripts:mod_specific/rftools/dimension_builder.js in 0.0 s
[18:46:01] [main/INFO]: SourceFile:407: Loaded script server_scripts:mod_specific/rftools/rftools.js in 0.0 s
[18:46:01] [main/INFO]: SourceFile:407: Loaded script server_scripts:mod_specific/solarflux/solarflux.js in 0.0 s
[18:46:01] [main/INFO]: SourceFile:407: Loaded script server_scripts:mod_specific/storage_drawers/storage_drawers.js in 0.001 s
[18:46:01] [main/INFO]: SourceFile:407: Loaded script server_scripts:mod_specific/tconstruct/tconstruct.js in 0.0 s
[18:46:01] [main/INFO]: SourceFile:407: Loaded script server_scripts:mod_specific/thermal/thermal.js in 0.001 s
[18:46:01] [main/INFO]: SourceFile:407: Loaded script server_scripts:mod_specific/tombstone/tombstone.js in 0.0 s
[18:46:01] [main/INFO]: SourceFile:407: Loaded script server_scripts:mod_specific/universal_grid/universal_grid.js in 0.0 s
[18:46:01] [main/INFO]: SourceFile:407: Loaded script server_scripts:mod_specific/woot/woot.js in 0.0 s
[18:46:01] [main/INFO]: SourceFile:407: Loaded script server_scripts:mod_specific/xreliquary/xreliquary.js in 0.0 s
[18:46:01] [main/INFO]: SourceFile:407: Loaded script server_scripts:mod_specific/zycraft/zycraft.js in 0.0 s
[18:46:01] [main/INFO]: SourceFile:407: Loaded script server_scripts:mod_specific/_allthemods/allthemodium.js in 0.0 s
[18:46:01] [main/INFO]: SourceFile:407: Loaded script server_scripts:mod_specific/_allthemods/atm_shard.js in 0.0 s
[18:46:01] [main/INFO]: SourceFile:407: Loaded script server_scripts:mod_specific/_allthemods/atm_star.js in 0.001 s
[18:46:01] [main/INFO]: SourceFile:407: Loaded script server_scripts:mod_specific/_allthemods/uu_matter_recipes.js in 0.0 s
[18:46:01] [main/INFO]: SourceFile:407: Loaded script server_scripts:mod_specific/_minecraft/minecraft.js in 0.001 s
[18:46:01] [main/INFO]: SourceFile:407: Loaded script server_scripts:mod_specific/_misc/misc.js in 0.0 s
[18:46:01] [main/INFO]: SourceFile:407: Loaded 67/67 KubeJS server scripts in 0.036 s
[18:46:01] [main/INFO]: Scripts loaded
[18:46:01] [main/INFO]: Registered custom recipe handler for type kubejs:shaped
[18:46:01] [main/INFO]: Registered custom recipe handler for type kubejs:shapeless
[18:46:01] [main/INFO]: Registered custom recipe handler for type minecraft:crafting_shaped
[18:46:01] [main/INFO]: Registered custom recipe handler for type minecraft:crafting_shapeless
[18:46:01] [main/INFO]: Registered custom recipe handler for type minecraft:stonecutting
[18:46:01] [main/INFO]: Registered custom recipe handler for type minecraft:smelting
[18:46:01] [main/INFO]: Registered custom recipe handler for type minecraft:blasting
[18:46:01] [main/INFO]: Registered custom recipe handler for type minecraft:smoking
[18:46:01] [main/INFO]: Registered custom recipe handler for type minecraft:campfire_cooking
[18:46:01] [main/INFO]: Registered custom recipe handler for type minecraft:smithing
[18:46:01] [main/INFO]: Registered custom recipe handler for type cucumber:shaped_no_mirror
[18:46:01] [main/INFO]: Registered custom recipe handler for type mysticalagriculture:tag
[18:46:01] [main/INFO]: Registered custom recipe handler for type botanypots:crop
[18:46:01] [main/INFO]: Registered custom recipe handler for type dankstorage:upgrade
[18:46:01] [main/INFO]: Registered custom recipe handler for type appliedenergistics2:grinder
[18:46:01] [main/INFO]: Registered custom recipe handler for type botania:runic_altar
[18:46:01] [main/INFO]: Registered custom recipe handler for type integrateddynamics:squeezer
[18:46:01] [main/INFO]: Registered custom recipe handler for type integrateddynamics:mechanical_squeezer
[18:46:01] [main/INFO]: Registered custom recipe handler for type ars_nouveau:enchanting_apparatus
[18:46:01] [main/INFO]: Registered custom recipe handler for type ars_nouveau:enchantment
[18:46:01] [main/INFO]: Registered custom recipe handler for type ars_nouveau:glyph_recipe
[18:46:01] [main/INFO]: Registered custom recipe handler for type thermal:furnace
[18:46:01] [main/INFO]: Registered custom recipe handler for type thermal:sawmill
[18:46:01] [main/INFO]: Registered custom recipe handler for type thermal:pulverizer
[18:46:01] [main/INFO]: Registered custom recipe handler for type thermal:smelter
[18:46:01] [main/INFO]: Registered custom recipe handler for type thermal:insolator
[18:46:01] [main/INFO]: Registered custom recipe handler for type thermal:centrifuge
[18:46:01] [main/INFO]: Registered custom recipe handler for type thermal:press
[18:46:01] [main/INFO]: Registered custom recipe handler for type thermal:crucible
[18:46:01] [main/INFO]: Registered custom recipe handler for type thermal:chiller
[18:46:01] [main/INFO]: Registered custom recipe handler for type thermal:refinery
[18:46:01] [main/INFO]: Registered custom recipe handler for type thermal:pyrolyzer
[18:46:01] [main/INFO]: Registered custom recipe handler for type thermal:brewer
[18:46:01] [main/INFO]: Registered custom recipe handler for type thermal:bottler
[18:46:01] [main/INFO]: Registered custom recipe handler for type thermal:pulverizer_catalyst
[18:46:01] [main/INFO]: Registered custom recipe handler for type thermal:smelter_catalyst
[18:46:01] [main/INFO]: Registered custom recipe handler for type thermal:insolator_catalyst
[18:46:01] [main/INFO]: Registered custom recipe handler for type thermal:stirling_fuel
[18:46:01] [main/INFO]: Registered custom recipe handler for type thermal:compression_fuel
[18:46:01] [main/INFO]: Registered custom recipe handler for type thermal:magmatic_fuel
[18:46:01] [main/INFO]: Registered custom recipe handler for type thermal:numismatic_fuel
[18:46:01] [main/INFO]: Registered custom recipe handler for type thermal:lapidary_fuel
[18:46:01] [main/INFO]: Registered custom recipe handler for type thermal:tree_extractor
[18:46:01] [main/INFO]: Registered custom recipe handler for type thermal:tree_extractor_boost
[18:46:01] [main/INFO]: Registered custom recipe handler for type thermal:fisher_boost
[18:46:01] [main/INFO]: Registered custom recipe handler for type thermal:rock_gen
[18:46:01] [main/INFO]: Registered custom recipe handler for type thermal:potion_diffuser_boost
[18:46:01] [main/INFO]: Registered custom recipe handler for type create:sequenced_assembly
[18:46:01] [main/INFO]: Registered custom recipe handler for type create:mechanical_crafting
[18:46:01] [main/INFO]: Registered custom recipe handler for type create:conversion
[18:46:01] [main/INFO]: Registered custom recipe handler for type create:crushing
[18:46:01] [main/INFO]: Registered custom recipe handler for type create:cutting
[18:46:01] [main/INFO]: Registered custom recipe handler for type create:milling
[18:46:01] [main/INFO]: Registered custom recipe handler for type create:basin
[18:46:01] [main/INFO]: Registered custom recipe handler for type create:mixing
[18:46:01] [main/INFO]: Registered custom recipe handler for type create:compacting
[18:46:01] [main/INFO]: Registered custom recipe handler for type create:pressing
[18:46:01] [main/INFO]: Registered custom recipe handler for type create:sandpaper_polishing
[18:46:01] [main/INFO]: Registered custom recipe handler for type create:splashing
[18:46:01] [main/INFO]: Registered custom recipe handler for type create:deploying
[18:46:01] [main/INFO]: Registered custom recipe handler for type create:filling
[18:46:01] [main/INFO]: Registered custom recipe handler for type create:emptying
[18:46:01] [main/INFO]: Registered custom recipe handler for type immersiveengineering:turn_and_copy
[18:46:01] [main/INFO]: Registered custom recipe handler for type immersiveengineering:alloy
[18:46:01] [main/INFO]: Registered custom recipe handler for type immersiveengineering:blast_furnace
[18:46:01] [main/INFO]: Registered custom recipe handler for type immersiveengineering:blast_furnace_fuel
[18:46:01] [main/INFO]: Registered custom recipe handler for type immersiveengineering:coke_oven
[18:46:01] [main/INFO]: Registered custom recipe handler for type immersiveengineering:cloche
[18:46:01] [main/INFO]: Registered custom recipe handler for type immersiveengineering:fertilizer
[18:46:01] [main/INFO]: Registered custom recipe handler for type immersiveengineering:metal_press
[18:46:01] [main/INFO]: Registered custom recipe handler for type immersiveengineering:arc_furnace
[18:46:01] [main/INFO]: Registered custom recipe handler for type immersiveengineering:crusher
[18:46:01] [main/INFO]: Registered custom recipe handler for type immersiveengineering:sawmill
[18:46:01] [main/INFO]: Registered custom recipe handler for type mekanism:crushing
[18:46:01] [main/INFO]: Registered custom recipe handler for type mekanism:enriching
[18:46:01] [main/INFO]: Registered custom recipe handler for type mekanism:smelting
[18:46:01] [main/INFO]: Registered custom recipe handler for type mekanism:chemical_infusing
[18:46:01] [main/INFO]: Registered custom recipe handler for type mekanism:combining
[18:46:01] [main/INFO]: Registered custom recipe handler for type mekanism:crystallizing
[18:46:01] [main/INFO]: Registered custom recipe handler for type mekanism:dissolution
[18:46:01] [main/INFO]: Registered custom recipe handler for type mekanism:compressing
[18:46:01] [main/INFO]: Registered custom recipe handler for type mekanism:purifying
[18:46:01] [main/INFO]: Registered custom recipe handler for type mekanism:injecting
[18:46:01] [main/INFO]: Registered custom recipe handler for type mekanism:energy_conversion
[18:46:01] [main/INFO]: Registered custom recipe handler for type mekanism:gas_conversion
[18:46:01] [main/INFO]: Registered custom recipe handler for type mekanism:oxidizing
[18:46:01] [main/INFO]: Registered custom recipe handler for type mekanism:metallurgic_infusing
[18:46:01] [main/INFO]: Registered custom recipe handler for type mekanism:reaction
[18:46:01] [main/INFO]: Registered custom recipe handler for type mekanism:sawing
[18:46:01] [main/INFO]: Registered custom recipe handler for type bloodmagic:altar
[18:46:01] [main/INFO]: Registered custom recipe handler for type bloodmagic:array
[18:46:01] [main/INFO]: Registered custom recipe handler for type bloodmagic:soulforge
[18:46:01] [main/INFO]: Registered custom recipe handler for type bloodmagic:arc
[18:46:01] [main/INFO]: Registered custom recipe handler for type bloodmagic:alchemytable
[18:46:01] [main/INFO]: Scanning recipes...
[18:46:01] [main/INFO]: Reloading ResourceManager: KubeJS Virtual Data Pack [low priority], Default, BetterDungeons-1.16.4-1.2.1.jar, ftb-essentials-1605.1.5-build.32.jar, supermartijn642configlib-1.0.9-mc1.16.jar, AdditionalEnchantedMiner-1.16.5-16.1.11.jar, simplemagnets-1.1.5-mc1.16.jar, IntegratedTerminals-1.16.5-1.2.11.jar, HammerLib-1.16.5-16.3.27.jar, mcw-windows-2.0.2-mc1.16.5.jar, windowlogging-mc1.16.5_v0.0.5.jar, modnametooltip_1.16.2-1.15.0.jar, IronJetpacks-1.16.5-4.2.3.jar, ForgeEndertech-1.16.5-7.2.2.0-build.0202.jar, CTM-MC1.16.1-1.1.2.6.jar, YungsApi-1.16.4-Forge-13.jar, Powah-1.16.5-2.3.16.jar, cabletiers-1.16.5-0.544.jar, rangedpumps-0.8.2.jar, jumbofurnace-1.16.4-2.2.0.1.jar, WitherSkeletonTweaks-1.16.5-5.4.1.jar, Shrink-1.16.5-1.1.6.jar, reliquary-1.16.5-1.3.5.1104.jar, universalgrid-1.16.5-0.125.jar, randompatches-2.4.4-forge.jar, Apotheosis-1.16.5-4.8.4.jar, WaterStrainer-1.16.3-10.0.0.jar, dynviewdist-2.0.jar, TMechworks-1.16.3+-2.2.5.jar, JustEnoughResources-1.16.5-0.12.1.133.jar, DeLogger-3.0.4-build.20+mc1.16.5.jar, shetiphiancore-1.16-3.8.6.jar, supplementaries-1.16.5-0.18.2.jar, refinedstorage-1.9.17.jar, novillagerdm-1.0.1.jar, AdvancementPlaques-1.16.5-1.4.1.jar, PackMenu-1.16.5-2.5.0.jar, alltheores-1.3.6-1.16.5-36.1.0.jar, industrial-foregoing-1.16.5-3.2.14.7-16.jar, cleancut-mc1.16-2.2-forge.jar, torchmaster-2.3.8.jar, repurposed_structures_forge-3.4.7+1.16.5.jar, fastfurnaceminusreplacement-1.1-1.16.3.jar, BiomesOPlenty-1.16.5-13.1.0.485-universal.jar, ironfurnaces-1.16.5-2.7.7.jar, mcw-trapdoors-1.0.4-mc1.16.5.jar, silent-gear-1.16.5-2.6.30.jar, supermartijn642corelib-1.0.16-mc1.16.5.jar, Botania-1.16.5-420.2.jar, SpawnerFix-1.16.2-1.0.0.2.jar, spark-forge.jar, portality-1.16.5-3.2.5.jar, curios-forge-1.16.5-4.0.5.3.jar, corail_woodcutter-1.16-2.0.1.jar, tanknull-2.3-1.16.4.jar, angelring-1.16.5-1.3.4.1.jar, tombstone-6.7.2-1.16.5.jar, ExtraStorage-1.16.5-1.6.1.jar, NaturesAura-34.3.jar, constructionwand-1.16.5-2.6.jar, mcw-roofs-2.1.0-mc1.16.5.jar, cfm-7.0.0pre22-1.16.3.jar, observerlib-1.16.5-1.5.3.jar, globalxp-1.16.5-v1.9.jar, cloth-config-4.13.49-forge.jar, AdChimneys-1.16.5-6.0.12.3-build.0207.jar, FastLeafDecay-v25.2.jar, CodeChickenLib-1.16.5-4.0.6.443-universal.jar, CBMultipart-1.16.5-3.0.4.123-universal.jar, Babel-1.0.5.jar, JEPB-1.0.0.jar, BetterMineshafts-Forge-1.16.4-2.0.4.jar, geckolib-forge-1.16.5-3.0.65.jar, SaveMyStronghold-1.16.4-1.0.jar, ClientTweaks_1.16.3-5.3.0.jar, nomowanderer_MC1.16.5_1.2.jar, woot-1.16.5-1.0.8.3.jar, bagofyurting-1.16.4-1.2.0.1.jar, jei-1.16.5-7.7.1.145.jar, jei-professions-1.0.0-1.16.4.jar, AttributeFix-1.16.5-10.1.3.jar, Mekanism-1.16.5-10.1.1.456.jar, caelus-forge-1.16.5-2.1.3.2.jar, AllTheCompressed-1.0.3-1.16.5-36.2.26.jar, invtweaks-1.16.4-1.0.1.jar, shutupexperimentalsettings-1.0.3.jar, NaturesCompass-1.16.5-1.9.1-forge.jar, catjammies-1.1.0.jar, LibX-1.16.3-1.0.76.jar, compactmachines-4.0.0-beta.2.jar, phosphophyllite-1.16.5-0.5.1.jar, engineerstools-1.16.5-1.1.7.jar, curioofundying-forge-1.16.5-5.2.0.0.jar, FarmingForBlockheads_1.16.5-7.3.1.jar, pneumaticcraft-repressurized-1.16.5-2.15.2-303.jar, pedestals-0.8s_hotfix_5.jar, extradisks-1.16.4-1.5.1.jar, ImmersivePetroleum-1.16.5-3.3.0-11.jar, ironchest-1.16.5-11.2.21.jar, MythicBotany-1.16.5-1.4.19.jar, IntegratedCrafting-1.16.5-1.0.20.jar, logprot-1.16-1.5.jar, theoneprobe-1.16-3.1.4.jar, MouseTweaks-2.14-mc1.16.2.jar, useful_railroads-1.16.5-1.4.6.38.jar, pamhc2crops-1.16.3-1.0.2.jar, creativeapiary-1.16.5-1.72.jar, Ding-1.16.5-1.3.0.jar, jeiintegration_1.16.5-7.0.1.15.jar, pipez-1.16.5-1.2.15.jar, flywheel-1.16-0.2.5.jar, Mantle-1.16.5-1.6.157.jar, IntegratedDynamics-1.16.5-1.10.6.jar, integratednbt-1.16.4-1.4.2.jar, pamhc2foodcore-1.16.3-1.0.2.jar, ftb-backups-2.1.2.2.jar, polymorph-forge-1.16.5-0.25.jar, AutoRegLib-1.6-49.jar, entityculling-forge-mc1.16.5-1.4.0.jar, structurize-0.13.252-ALPHA-universal.jar, norecipeadvancements-1.0.1.jar, creativecrafter-1.16.5-0.1521.jar, PickleTweaks-1.16.5-5.2.6.jar, lootr-1.16.5-0.1.11.36.jar, allthetweaks-1.4.5-1.16.5-36.1.13.jar, byg-1.3.5.jar, extremeSoundMuffler-3.17_1.16.5.jar, CosmeticArmorReworked-1.16.5-v4a.jar, xptome-1.16.5-v2.1.2.jar, DefaultOptions_1.16.5-12.2.1.jar, rsrequestify-1.16.5-2.1.6.jar, CyclopsCore-1.16.5-1.12.1.jar, astralsorcery-1.16-1.16.5-1.13.12.jar, NetherPortalFix_1.16.3-7.2.1.jar, aiotbotania-1.16.5-1.8.4.jar, advancedperipherals-1.16.5-0.7.7.1r.jar, tinyredstone-1.16.5-1.13.1.jar, eidolon-0.2.7.jar, managear-1.16.3-2.2.3.jar, JustEnoughCalculation-1.16.5-3.8.6.jar, incontrol-1.16-5.2.2.jar, connectivity-2.4-1.16.5.jar, rsgauges-1.16.5-1.2.13.jar, findme-1.16.3-2.2.1.0.jar, glassential-forge-1.16.5-1.1.7.jar, TerraForged-1.16.5-0.2.16-BETA-2.jar, configurableextramobdrops_1.16.5-1.8.jar, CookingForBlockheads_1.16.5-9.3.4.jar, Controlling-7.0.0.28.jar, Placebo-1.16.5-4.6.1.jar, dankstorage-3.19.jar, citadel-1.8.1-1.16.5.jar, iceandfire-2.1.9-1.16.5.jar, allthemodium-1.5.18-1.16.5-36.1.23.jar, mightyarchitect-mc1.16.3_v0.5.jar, potionsmaster-0.2.2-1.16.5-36.1.0.jar, moreminecarts-1.3.14.jar, culinaryconstruct-forge-1.16.5-4.0.0.7.jar, cartographer-0.0.2-1.16.5-36.0.52.jar, Bookshelf-Forge-1.16.5-10.4.31.jar, DarkUtilities-1.16.5-8.0.11.jar, BotanyPots-1.16.5-7.1.30.jar, BotanyTrees-1.16.5-3.0.6.jar, sophisticatedbackpacks-1.16.5-3.15.1.503.jar, u_team_core-1.16.5-3.2.1.196.jar, buildinggadgets-1.16.5-3.8.2.jar, FramedBlocks-2.13.0.jar, forge-1.16.5-36.2.26-universal.jar, cofh_core-1.16.5-1.4.2.9.jar, thermal_foundation-1.16.5-1.4.3.10.jar, thermal_innovation-1.16.5-1.4.1.3.jar, thermal_locomotion-1.16.5-1.4.1.2.jar, Psi 1.16-97.jar, thermal_cultivation-1.16.5-1.4.1.3.jar, appleskin-forge-mc1.16.x-2.3.0.jar, Aquaculture-1.16.5-2.1.21.jar, mcw-doors-1.0.5-mc1.16.5.jar, LightingWand-1.16.4-1.8.1.jar, jeed-1.16.5-1.6.jar, MekanismGenerators-1.16.5-10.1.1.456.jar, XNetGases-1.16.5-2.3.9.jar, MmmMmmMmmMmm-1.16.5-1.3.1.jar, absentbydesign-1.16.5-1.5.1.jar, twilightforest-1.16.5-4.0.870-universal.jar, mob_grinding_utils-1.16.5-0.4.32.jar, RSInfinityBooster-1.16.5-1.1+13.jar, EquipmentCompare-1.16.5-1.2.7.jar, chipped-1.16.5-1.2.1-forge.jar, chocolate-1.3.0-1.16.4.jar, mcw-bridges-2.0.1-mc1.16.5.jar, useful_backpacks-1.16.5-1.12.1.90.jar, ResourcefulBees-1.16.5-0.10.4.jar, HostileNeuralNetworks-1.16.5-1.0.6.jar, entangled-1.3.10-mc1.16.jar, endertanks-1.16-1.9.7.jar, CommonCapabilities-1.16.5-2.8.0.jar, crashutilities-3.13.jar, Compressium-1.16.5-1.2.3.jar, getittogetherdrops-1.16.5-v1.1.1.jar, MekanismAdditions-1.16.5-10.1.1.456.jar, valkyrielib-1.16.5-3.0.9.5.jar, envirocore-1.16.5-3.0.9.3.jar, envirotech-1.16.5-3.0.9.4.jar, Lollipop-1.16.5-3.2.9.jar, mcw-fences-1.0.2-mc1.16.5.jar, simplylight-1.16.5-1.4.0-build.24.jar, tgcropesmod-1.16.2-1.1.0.jar, atmadditions-1.16.5-1.0.2.jar, pamhc2foodextended-1.16.3-1.0.4.jar, SolarFluxReborn-1.16.5-16.3.9.jar, dpanvil-1.16.5-1.2.3.jar, Patchouli-1.16.4-53.2.jar, ars_nouveau-1.16.5-1.24.16.jar, collective-1.16.5-3.8.jar, betterbiomeblend-1.16.4-1.2.9-forge.jar, time-in-a-bottle-1.1.0.jar, thermal_expansion-1.16.5-1.4.2.4.jar, IntegratedTunnels-1.16.5-1.8.9.jar, DrawersTooltip-1.16.2-2.1.1.jar, MysticalCustomization-1.16.5-2.1.7.jar, lostcities-1.16-4.0.11-beta.jar, elevatorid-1.16.5-1.7.13.jar, GunpowderLib-1.16.5-1.2.2.jar, ftb-ultimine-forge-1605.3.1-build.45.jar, BetterStrongholds-1.16.4-1.2.1.jar, buildersaddition-1.16.5-20210807a.jar, Runelic-1.16.5-7.0.2.jar, starterkit_1.16.5-3.1.jar, MekanismTools-1.16.5-10.1.1.456.jar, architectury-1.29.51.jar, ftb-library-forge-1605.3.4-build.90.jar, ftb-teams-forge-1605.2.3-build.40.jar, ftb-ranks-forge-1605.1.5-build.16.jar, curiouselytra-forge-1.16.5-4.0.2.4.jar, cc-tweaked-1.16.5-1.100.2.jar, ProjectRed-1.16.5-4.11.0-core.jar, energymeter-1.16.5-1.6.1.jar, ProjectRed-1.16.5-4.11.0-exploration.jar, ProjectRed-1.16.5-4.11.0-integration.jar, ProjectRed-1.16.5-4.11.0-illumination.jar, ProjectRed-1.16.5-4.11.0-transmission.jar, light-overlay-5.8.1.jar, trashcans-1.0.12-mc1.16.jar, TrampleStopper-2.6.1-build.22+mc1.16.5.jar, smallships-1.16.5-1.10.3.jar, bwncr-1.16.5-3.10.16.jar, observable-0.2.1-forge.jar, Cyclic-1.16.5-1.5.13.jar, BetterAdvancements-1.16.5-0.1.1.115.jar, rhino-forge-1605.1.5-build.75.jar, biggerreactors-1.16.5-0.5.1.jar, Cucumber-1.16.5-4.1.12.jar, TrashSlot_1.16.3-12.2.1.jar, pamhc2trees-1.16.3-1.0.1.jar, flatbedrock-1.2.0-build.2+mc1.16.5.jar, craftingstation-4.2.jar, item-filters-forge-1605.2.5-build.9.jar, elementalcraft-1.16.5-2.7.14.jar, platforms-1.16-1.7.12.jar, metalbarrels-1.16.2-3.3b.jar, abnormals_core-1.16.5-3.3.1.jar, upgrade_aquatic-1.16.5-3.1.2.jar, ponderjs-1.16.5-1.0.3d.jar, ae2extras-1.3.1-1.16.5.jar, ensorcellation-1.16.5-1.4.1.2.jar, create-mc1.16.5_v0.3.2g.jar, ZYCraft-1.16.5-3.1.34.jar, Waystones_1.16.5-7.6.4.jar, Clumps-6.0.0.27.jar, enviromats-1.16.5-2.0.9.0.jar, comforts-forge-1.16.5-4.0.1.3.jar, appliedenergistics2-8.4.7.jar, lazierae2-1.16.5-1.1.4.jar, Artifacts-1.16.5-2.10.4.jar, framedcompactdrawers-1.16-2.2.1.jar, configured-1.5.1-1.16.5.jar, DimStorage-1.16.5-4.4.1.jar, DungeonCrawl-1.16.5-2.3.5.jar, demagnetize-forge-1.16.2-1.2.2.jar, TravelAnchors-2.4.jar, lazydfu-0.1.3.jar, mcjtylib-1.16-5.1.3.jar, rftoolsbase-1.16-2.1.2.jar, xnet-1.16-3.0.16.jar, rftoolsdim-1.16-7.0.20-beta.jar, rftoolspower-1.16-3.0.13.jar, rftoolsbuilder-1.16-3.1.5.jar, rftoolsstorage-1.16-2.0.17.jar, rftoolscontrol-1.16-4.0.14.jar, restrictions-1.16-3.0.6.jar, ExplorersCompass-1.16.5-1.1.2-forge.jar, mahoutsukai-1.16.5-v1.34.7.jar, ToastControl-1.16.5-4.4.0.jar, mininggadgets-1.7.5.jar, EnderStorage-1.16.5-2.8.0.168-universal.jar, AkashicTome-1.4-16.jar, ftb-chunks-forge-1605.3.2-build.115.jar, kubejs-forge-1605.3.19-build.289.jar, kubejs-thermal-1605.1.4-build.4.jar, ftb-quests-forge-1605.3.6-build.76.jar, kubejs-create-1605.1.4-build.12.jar, kubejs-mekanism-1605.1.2-build.2.jar, BloodMagic-1.16.4-3.1.7-27.jar, tomeofblood-1.16.5-1.2.3.jar, kubejs-blood-magic-1605.1.1-build.3.jar, scuba-gear-1.16.5-1.0.3.jar, BrandonsCore-1.16.5-3.0.11.238-universal.jar, Draconic-Evolution-1.16.5-3.0.19.432-universal.jar, immersiveposts-1.16.5-4.2.2.jar, ImmersiveEngineering-1.16.5-5.0.7-143.jar, kubejs-immersive-engineering-1605.1.2-build.28.jar, selene-1.16.5-1.9.0.jar, MysticalAgriculture-1.16.5-4.2.6.jar, MysticalAgradditions-1.16.5-4.2.4.jar, sounddeviceoptions-1.4.3.jar, CraftingTweaks_1.16.5-12.2.1.jar, TConstruct-1.16.5-3.3.3.332.jar, rftoolsutility-1.16-3.1.10.jar, EnchantmentDescriptions-1.16.5-7.0.18.jar, ToolBelt-1.16.5-1.16.0.jar, titanium-1.16.5-3.2.8.7-22.jar, mana-and-artifice-1.5.1.6.jar, silent-lib-1.16.3-4.9.6.jar, Exchangers-1.16.5-3.0.2.jar, ctiers-1.16.5-1.36.jar, archers_paradox-1.16.5-1.4.0.1.jar, omgourd-1.16.5-1.4.0.1.jar, enviroenergy-1.16.5-3.0.9.1.jar, Iceberg-1.16.5-1.0.38.jar, Quark-r2.4-321.jar, LegendaryTooltips-1.16.5-1.1.6.jar, creativewirelesstransmitter-1.16x-1.12.jar, FastWorkbench-1.16.5-4.6.1.jar, StorageDrawers-1.16.3-8.5.1.jar, topaddons-1.16.5-2.2.0-beta.jar, FluxNetworks-1.16.5-6.2.1.14.jar, enderchests-1.16-1.7.9.jar, minecolonies-1.16.5-1.0.352-BETA.jar, pylons-1.0.4.jar, ferritecore-2.1.0-forge.jar, engineersdecor-1.16.5-1.1.16.jar, Chisel-MC1.16.5-2.0.1-alpha.4.jar, SoL-Carrot-1.16.5-1.10.1.jar, modular-routers-1.16.5-7.5.2-83.jar, refinedstorageaddons-0.7.4.jar, expandability-2.0.1-forge.jar, botanicalmachinery-1.16.4-0.4.4.jar, valhelsia_core-16.0.13a.jar, forbidden_arcanus-16.2.2.jar, overloadedarmorbar-5.1.0.jar, Morph-o-Tool-1.4-27.jar, Translocators-1.16.5-2.6.0.82-universal.jar, flickerfix-1.0.1.jar, createaddition-1.16.5-20220129a.jar, balancedenchanting-1.16.2-1.1.jar, resourcefulbees:internals, Solar Flux Generated Resources, torohealth-1.16.4-forge-4.jar, KubeJS Resource Pack [data], KubeJS Virtual Data Pack [high priority]
[18:46:06] [main/INFO]: [blocks] Found 1753 tags, added 2563 objects, removed 46 objects
[18:46:06] [main/INFO]: [blocks] Found 1753 tags, added 0 objects, removed 0 objects
[18:46:06] [main/ERROR]: Couldn't load block tag farmersdelight:mushroom_colony_growable_on as it is missing following references: supplementaries:planter_rich (from supplementaries-1.16.5-0.18.2.jar)
[18:46:10] [main/INFO]: [items] Found 3764 tags, added 1973 objects, removed 23 objects
[18:46:10] [main/INFO]: [items] Found 3764 tags, added 0 objects, removed 0 objects
[18:46:10] [main/ERROR]: Couldn't load item tag forge:marble as it is missing following references: #enviromats:marble (from enviromats-1.16.5-2.0.9.0.jar)
[18:46:10] [main/ERROR]: Couldn't load item tag forge:granodiorite as it is missing following references: #enviromats:granodiorite (from enviromats-1.16.5-2.0.9.0.jar)
[18:46:10] [main/ERROR]: Couldn't load item tag forge:hardened_stone as it is missing following references: #enviromats:hardened_stone (from enviromats-1.16.5-2.0.9.0.jar)
[18:46:10] [main/ERROR]: Couldn't load item tag forge:basalt as it is missing following references: #enviromats:basalt (from enviromats-1.16.5-2.0.9.0.jar)
[18:46:10] [main/ERROR]: Couldn't load item tag forge:pumice as it is missing following references: #enviromats:pumice (from enviromats-1.16.5-2.0.9.0.jar)
[18:46:10] [main/ERROR]: Couldn't load item tag forge:travertine as it is missing following references: #enviromats:travertine (from enviromats-1.16.5-2.0.9.0.jar)
[18:46:10] [main/INFO]: [fluids] Found 165 tags, added 67 objects, removed 0 objects
[18:46:10] [main/INFO]: [fluids] Found 165 tags, added 0 objects, removed 0 objects
[18:46:10] [main/INFO]: [entity_types] Found 46 tags, added 202 objects, removed 0 objects
[18:46:10] [main/INFO]: [entity_types] Found 46 tags, added 0 objects, removed 0 objects
[18:46:10] [main/INFO]: [tunnel_types] Found 0 tags, added 0 objects, removed 0 objects
[18:46:10] [main/INFO]: [tunnel_types] Found 0 tags, added 0 objects, removed 0 objects
[18:46:10] [main/INFO]: [potions] Found 0 tags, added 0 objects, removed 0 objects
[18:46:10] [main/INFO]: [potions] Found 0 tags, added 0 objects, removed 0 objects
[18:46:10] [main/INFO]: [pigments] Found 0 tags, added 0 objects, removed 0 objects
[18:46:10] [main/INFO]: [pigments] Found 0 tags, added 0 objects, removed 0 objects
[18:46:10] [main/INFO]: [enchantments] Found 1 tags, added 0 objects, removed 0 objects
[18:46:10] [main/INFO]: [enchantments] Found 1 tags, added 0 objects, removed 0 objects
[18:46:10] [main/INFO]: [tile_entity_types] Found 5 tags, added 0 objects, removed 0 objects
[18:46:10] [main/INFO]: [tile_entity_types] Found 5 tags, added 0 objects, removed 0 objects
[18:46:10] [main/INFO]: [slurries] Found 2 tags, added 0 objects, removed 0 objects
[18:46:10] [main/INFO]: [slurries] Found 2 tags, added 0 objects, removed 0 objects
[18:46:10] [main/INFO]: [infuse_types] Found 8 tags, added 0 objects, removed 0 objects
[18:46:10] [main/INFO]: [infuse_types] Found 8 tags, added 0 objects, removed 0 objects
[18:46:10] [main/INFO]: [gases] Found 5 tags, added 0 objects, removed 0 objects
[18:46:10] [main/INFO]: [gases] Found 5 tags, added 0 objects, removed 0 objects
[18:46:10] [main/INFO]: Loot Modification Manager has loaded 0 sets of modifiers
[18:46:10] [main/WARN]: Failed to parse recipe 'thermal:compat/mysticalagriculture/insolator_mysticalag_zombie_pigman_seeds[thermal:insolator]'! Falling back to vanilla: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_zombie_pigman_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:46:10] [main/WARN]: Failed to parse recipe thermal:compat/mysticalagriculture/insolator_mysticalag_zombie_pigman_seeds[thermal:insolator]: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_zombie_pigman_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:46:10] [main/INFO]: Received new training data for mana-and-artifice:manaweave_patterns/circle
[18:46:10] [main/WARN]: Failed to parse recipe 'thermal:compat/appliedenergistics2/ae2_ender_pearl_dust_convert[minecraft:crafting_shapeless]'! Falling back to vanilla: com.google.gson.JsonSyntaxException: Unknown item tag 'thermal:ender_pearl_dust'
[18:46:10] [main/WARN]: Failed to parse recipe thermal:compat/appliedenergistics2/ae2_ender_pearl_dust_convert[minecraft:crafting_shapeless]: com.google.gson.JsonSyntaxException: Unknown item tag 'thermal:ender_pearl_dust'
[18:46:10] [main/INFO]: ignoring heat properties for block occultism:spirit_fire: mod not loaded
[18:46:10] [main/WARN]: Failed to parse recipe 'thermal:compat/mysticalagriculture/insolator_mysticalag_phantom_seeds[thermal:insolator]'! Falling back to vanilla: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_phantom_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:46:10] [main/WARN]: Failed to parse recipe thermal:compat/mysticalagriculture/insolator_mysticalag_phantom_seeds[thermal:insolator]: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_phantom_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:46:10] [main/INFO]: Received new training data for mana-and-artifice:manaweave_patterns/star
[18:46:10] [main/WARN]: Failed to parse recipe 'thermal:compat/mysticalagriculture/insolator_mysticalag_villager_seeds[thermal:insolator]'! Falling back to vanilla: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_villager_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:46:10] [main/WARN]: Failed to parse recipe thermal:compat/mysticalagriculture/insolator_mysticalag_villager_seeds[thermal:insolator]: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_villager_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:46:10] [main/WARN]: Failed to parse recipe 'mana-and-artifice:decoration/stonecutting/redstone_arcane_stone_reset_stonecutter[minecraft:stonecutting]'! Falling back to vanilla: com.google.gson.JsonSyntaxException: Unknown item tag 'mana-and-artifice:stonecutter_resettable_redstone_arcane_stones'
[18:46:10] [main/WARN]: Failed to parse recipe mana-and-artifice:decoration/stonecutting/redstone_arcane_stone_reset_stonecutter[minecraft:stonecutting]: com.google.gson.JsonSyntaxException: Unknown item tag 'mana-and-artifice:stonecutter_resettable_redstone_arcane_stones'
[18:46:10] [main/WARN]: Failed to parse recipe 'thermal:compat/mysticalagriculture/insolator_mysticalag_wolf_seeds[thermal:insolator]'! Falling back to vanilla: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_wolf_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:46:10] [main/WARN]: Failed to parse recipe thermal:compat/mysticalagriculture/insolator_mysticalag_wolf_seeds[thermal:insolator]: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_wolf_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:46:10] [main/INFO]: Received new training data for mana-and-artifice:manaweave_patterns/slash
[18:46:10] [main/WARN]: Failed to parse recipe 'thermal:compat/mysticalagriculture/insolator_mysticalag_polar_bear_seeds[thermal:insolator]'! Falling back to vanilla: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_polar_bear_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:46:10] [main/WARN]: Failed to parse recipe thermal:compat/mysticalagriculture/insolator_mysticalag_polar_bear_seeds[thermal:insolator]: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_polar_bear_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:46:10] [main/WARN]: Failed to parse recipe 'thermal:compat/mysticalagriculture/insolator_mysticalag_llama_seeds[thermal:insolator]'! Falling back to vanilla: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_llama_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:46:10] [main/WARN]: Failed to parse recipe thermal:compat/mysticalagriculture/insolator_mysticalag_llama_seeds[thermal:insolator]: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_llama_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:46:10] [main/WARN]: Failed to parse recipe 'thermal:compat/mysticalagriculture/insolator_mysticalag_stray_seeds[thermal:insolator]'! Falling back to vanilla: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_stray_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:46:10] [main/WARN]: Failed to parse recipe thermal:compat/mysticalagriculture/insolator_mysticalag_stray_seeds[thermal:insolator]: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_stray_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:46:10] [main/WARN]: Recipe mana-and-artifice:multiblock/eldrin_altar does not define a tier, defaulting to 1.
[18:46:10] [main/WARN]: Failed to parse recipe 'thermal:compat/mysticalagriculture/insolator_mysticalag_vex_seeds[thermal:insolator]'! Falling back to vanilla: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_vex_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:46:10] [main/WARN]: Failed to parse recipe thermal:compat/mysticalagriculture/insolator_mysticalag_vex_seeds[thermal:insolator]: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_vex_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:46:10] [main/WARN]: Failed to parse recipe 'thermal:fuels/compression/compression_creosote[thermal:compression_fuel]': {"fluid_tag":"forge:creosote","amount":1000} is not a valid ingredient!
[18:46:10] [main/INFO]: Received new training data for mana-and-artifice:manaweave_patterns/backslash
[18:46:10] [main/INFO]: Received new training data for mana-and-artifice:manaweave_patterns/split_triangle
[18:46:10] [main/INFO]: Received new training data for mana-and-artifice:manaweave_patterns/knot
[18:46:10] [main/WARN]: Failed to parse recipe 'mana-and-artifice:runeforging/stone_pedestal_with_sign[minecraft:crafting_shapeless]'! Falling back to vanilla: com.google.gson.JsonParseException: An ingredient entry is either a tag or an item, not both
[18:46:10] [main/WARN]: Failed to parse recipe mana-and-artifice:runeforging/stone_pedestal_with_sign[minecraft:crafting_shapeless]: com.google.gson.JsonParseException: An ingredient entry is either a tag or an item, not both
[18:46:10] [main/WARN]: Failed to parse recipe 'thermal:compat/mysticalagriculture/insolator_mysticalag_evoker_seeds[thermal:insolator]'! Falling back to vanilla: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_evoker_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:46:10] [main/WARN]: Failed to parse recipe thermal:compat/mysticalagriculture/insolator_mysticalag_evoker_seeds[thermal:insolator]: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_evoker_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:46:10] [main/WARN]: Failed to parse recipe 'thermal:compat/mysticalagriculture/insolator_mysticalag_magma_cube_seeds[thermal:insolator]'! Falling back to vanilla: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_magma_cube_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:46:10] [main/WARN]: Failed to parse recipe thermal:compat/mysticalagriculture/insolator_mysticalag_magma_cube_seeds[thermal:insolator]: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_magma_cube_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:46:10] [main/WARN]: Failed to parse recipe 'thermal:compat/mysticalagriculture/insolator_mysticalag_drowned_seeds[thermal:insolator]'! Falling back to vanilla: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_drowned_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:46:10] [main/WARN]: Failed to parse recipe thermal:compat/mysticalagriculture/insolator_mysticalag_drowned_seeds[thermal:insolator]: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_drowned_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:46:10] [main/WARN]: Failed to parse recipe 'thermal:compat/mysticalagriculture/insolator_mysticalag_dolphin_seeds[thermal:insolator]'! Falling back to vanilla: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_dolphin_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:46:10] [main/WARN]: Failed to parse recipe thermal:compat/mysticalagriculture/insolator_mysticalag_dolphin_seeds[thermal:insolator]: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_dolphin_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:46:10] [main/WARN]: Failed to parse recipe 'mana-and-artifice:decoration/stonecutting/redstone_arcane_sandstone_reset_stonecutter[minecraft:stonecutting]'! Falling back to vanilla: com.google.gson.JsonSyntaxException: Unknown item tag 'mana-and-artifice:stonecutter_resettable_redstone_arcane_sandstones'
[18:46:10] [main/WARN]: Failed to parse recipe mana-and-artifice:decoration/stonecutting/redstone_arcane_sandstone_reset_stonecutter[minecraft:stonecutting]: com.google.gson.JsonSyntaxException: Unknown item tag 'mana-and-artifice:stonecutter_resettable_redstone_arcane_sandstones'
[18:46:10] [main/WARN]: Failed to parse recipe 'thermal:compat/mysticalagriculture/insolator_mysticalag_husk_seeds[thermal:insolator]'! Falling back to vanilla: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_husk_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:46:10] [main/WARN]: Failed to parse recipe thermal:compat/mysticalagriculture/insolator_mysticalag_husk_seeds[thermal:insolator]: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_husk_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:46:10] [main/INFO]: Received new training data for mana-and-artifice:manaweave_patterns/inverted_split_triangle
[18:46:10] [main/WARN]: Failed to parse recipe 'thermal:compat/mysticalagriculture/insolator_mysticalag_panda_seeds[thermal:insolator]'! Falling back to vanilla: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_panda_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:46:10] [main/WARN]: Failed to parse recipe thermal:compat/mysticalagriculture/insolator_mysticalag_panda_seeds[thermal:insolator]: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_panda_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:46:10] [main/WARN]: Failed to parse recipe 'thermal:compat/mysticalagriculture/insolator_mysticalag_vindicator_seeds[thermal:insolator]'! Falling back to vanilla: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_vindicator_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:46:10] [main/WARN]: Failed to parse recipe thermal:compat/mysticalagriculture/insolator_mysticalag_vindicator_seeds[thermal:insolator]: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_vindicator_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:46:10] [main/WARN]: Failed to parse recipe 'thermal:compat/mysticalagriculture/insolator_mysticalag_shulker_seeds[thermal:insolator]'! Falling back to vanilla: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_shulker_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:46:10] [main/WARN]: Failed to parse recipe thermal:compat/mysticalagriculture/insolator_mysticalag_shulker_seeds[thermal:insolator]: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_shulker_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:46:10] [main/INFO]: ignoring heat properties for block decorative_blocks:soul_brazier: mod not loaded
[18:46:10] [main/INFO]: Received new training data for mana-and-artifice:manaweave_patterns/infinity
[18:46:10] [main/INFO]: Received new training data for mana-and-artifice:manaweave_patterns/hourglass
[18:46:11] [main/WARN]: Failed to parse recipe 'thermal:compat/mysticalagriculture/insolator_mysticalag_ravager_seeds[thermal:insolator]'! Falling back to vanilla: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_ravager_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:46:11] [main/WARN]: Failed to parse recipe thermal:compat/mysticalagriculture/insolator_mysticalag_ravager_seeds[thermal:insolator]: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_ravager_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:46:11] [main/INFO]: ignoring heat properties for block valhelsia_structures:brazier: mod not loaded
[18:46:11] [main/WARN]: Failed to parse recipe 'thermal:compat/mysticalagriculture/insolator_mysticalag_guardian_seeds[thermal:insolator]'! Falling back to vanilla: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_guardian_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:46:11] [main/WARN]: Failed to parse recipe thermal:compat/mysticalagriculture/insolator_mysticalag_guardian_seeds[thermal:insolator]: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_guardian_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:46:11] [main/INFO]: Received new training data for mana-and-artifice:manaweave_patterns/inverted_triangle
[18:46:11] [main/INFO]: ignoring heat properties for block betterendforge:emerald_ice: mod not loaded
[18:46:11] [main/WARN]: Failed to parse recipe 'thermal:compat/mysticalagriculture/insolator_mysticalag_mooshroom_seeds[thermal:insolator]'! Falling back to vanilla: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_mooshroom_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:46:11] [main/WARN]: Failed to parse recipe thermal:compat/mysticalagriculture/insolator_mysticalag_mooshroom_seeds[thermal:insolator]: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_mooshroom_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:46:11] [main/WARN]: Failed to parse recipe 'thermal:compat/mysticalagriculture/insolator_mysticalag_horse_seeds[thermal:insolator]'! Falling back to vanilla: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_horse_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:46:11] [main/WARN]: Failed to parse recipe thermal:compat/mysticalagriculture/insolator_mysticalag_horse_seeds[thermal:insolator]: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_horse_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:46:11] [main/WARN]: Failed to parse recipe 'thermal:compat/mysticalagriculture/insolator_mysticalag_silverfish_seeds[thermal:insolator]'! Falling back to vanilla: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_silverfish_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:46:11] [main/WARN]: Failed to parse recipe thermal:compat/mysticalagriculture/insolator_mysticalag_silverfish_seeds[thermal:insolator]: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_silverfish_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:46:11] [main/INFO]: Received new training data for mana-and-artifice:manaweave_patterns/square
[18:46:11] [main/WARN]: Failed to parse recipe 'thermal:compat/mysticalagriculture/insolator_mysticalag_fox_seeds[thermal:insolator]'! Falling back to vanilla: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_fox_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:46:11] [main/WARN]: Failed to parse recipe thermal:compat/mysticalagriculture/insolator_mysticalag_fox_seeds[thermal:insolator]: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_fox_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:46:11] [main/WARN]: Recipe mana-and-artifice:multiblock/wellspring_capture does not define a tier, defaulting to 1.
[18:46:11] [main/WARN]: Failed to parse recipe 'thermal:compat/mysticalagriculture/insolator_mysticalag_endermite_seeds[thermal:insolator]'! Falling back to vanilla: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_endermite_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:46:11] [main/WARN]: Failed to parse recipe thermal:compat/mysticalagriculture/insolator_mysticalag_endermite_seeds[thermal:insolator]: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_endermite_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:46:11] [main/INFO]: Received new training data for mana-and-artifice:manaweave_patterns/knot3
[18:46:11] [main/INFO]: Received new training data for mana-and-artifice:manaweave_patterns/knot4
[18:46:11] [main/INFO]: Received new training data for mana-and-artifice:manaweave_patterns/knot2
[18:46:11] [main/WARN]: Recipe mana-and-artifice:multiblock/test_multiblock does not define a tier, defaulting to 1.
[18:46:11] [main/WARN]: Failed to parse recipe 'thermal:compat/mysticalagriculture/insolator_mysticalag_witch_seeds[thermal:insolator]'! Falling back to vanilla: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_witch_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:46:11] [main/WARN]: Failed to parse recipe thermal:compat/mysticalagriculture/insolator_mysticalag_witch_seeds[thermal:insolator]: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_witch_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:46:11] [main/WARN]: Failed to parse recipe 'thermal:compat/mysticalagriculture/insolator_mysticalag_pillager_seeds[thermal:insolator]'! Falling back to vanilla: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_pillager_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:46:11] [main/WARN]: Failed to parse recipe thermal:compat/mysticalagriculture/insolator_mysticalag_pillager_seeds[thermal:insolator]: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_pillager_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:46:11] [main/INFO]: ignoring heat properties for block betterendforge:ancient_emerald_ice: mod not loaded
[18:46:11] [main/INFO]: ignoring heat properties for block betterendforge:dense_emerald_ice: mod not loaded
[18:46:11] [main/INFO]: ignoring heat properties for block decorative_blocks:brazier: mod not loaded
[18:46:11] [main/INFO]: ignoring heat properties for block natura:nether_heat_sand: mod not loaded
[18:46:11] [main/INFO]: Received new training data for mana-and-artifice:manaweave_patterns/diamond
[18:46:11] [main/WARN]: Failed to parse recipe 'thermal:compat/mysticalagriculture/insolator_mysticalag_parrot_seeds[thermal:insolator]'! Falling back to vanilla: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_parrot_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:46:11] [main/WARN]: Failed to parse recipe thermal:compat/mysticalagriculture/insolator_mysticalag_parrot_seeds[thermal:insolator]: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_parrot_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:46:11] [main/INFO]: Received new training data for mana-and-artifice:manaweave_patterns/triangle
[18:46:11] [main/WARN]: Failed to parse recipe 'thermal:compat/mysticalagriculture/insolator_mysticalag_cat_seeds[thermal:insolator]'! Falling back to vanilla: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_cat_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:46:11] [main/WARN]: Failed to parse recipe thermal:compat/mysticalagriculture/insolator_mysticalag_cat_seeds[thermal:insolator]: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_cat_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:46:11] [main/WARN]: Failed to parse recipe 'thermal:compat/mysticalagriculture/insolator_mysticalag_bat_seeds[thermal:insolator]'! Falling back to vanilla: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_bat_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:46:11] [main/WARN]: Failed to parse recipe thermal:compat/mysticalagriculture/insolator_mysticalag_bat_seeds[thermal:insolator]: com.google.gson.JsonSyntaxException: Invalid Thermal Series recipe: thermal:compat/mysticalagriculture/insolator_mysticalag_bat_seeds
Refer to the recipe's ResourceLocation to find the mod responsible and let them know!
[18:46:11] [main/INFO]: Found 37471 recipes and 0 failed recipes in 475.7 ms
[18:46:24] [main/INFO]: Posted recipe events in 13.00 s
[18:46:24] [main/INFO]: Received new training data for mana-and-artifice:manaweave_patterns/circle
[18:46:24] [main/INFO]: Received new training data for mana-and-artifice:manaweave_patterns/star
[18:46:24] [main/INFO]: Received new training data for mana-and-artifice:manaweave_patterns/slash
[18:46:24] [main/WARN]: Recipe mana-and-artifice:multiblock/eldrin_altar does not define a tier, defaulting to 1.
[18:46:24] [main/INFO]: Received new training data for mana-and-artifice:manaweave_patterns/backslash
[18:46:24] [main/INFO]: Received new training data for mana-and-artifice:manaweave_patterns/split_triangle
[18:46:24] [main/INFO]: Received new training data for mana-and-artifice:manaweave_patterns/knot
[18:46:24] [main/INFO]: Received new training data for mana-and-artifice:manaweave_patterns/inverted_split_triangle
[18:46:24] [main/INFO]: Received new training data for mana-and-artifice:manaweave_patterns/infinity
[18:46:24] [main/INFO]: Received new training data for mana-and-artifice:manaweave_patterns/hourglass
[18:46:24] [main/INFO]: Received new training data for mana-and-artifice:manaweave_patterns/inverted_triangle
[18:46:24] [main/INFO]: Received new training data for mana-and-artifice:manaweave_patterns/square
[18:46:24] [main/WARN]: Recipe mana-and-artifice:multiblock/wellspring_capture does not define a tier, defaulting to 1.
[18:46:24] [main/INFO]: Received new training data for mana-and-artifice:manaweave_patterns/knot3
[18:46:24] [main/INFO]: Received new training data for mana-and-artifice:manaweave_patterns/knot4
[18:46:24] [main/INFO]: Received new training data for mana-and-artifice:manaweave_patterns/knot2
[18:46:24] [main/WARN]: Recipe mana-and-artifice:multiblock/test_multiblock does not define a tier, defaulting to 1.
[18:46:24] [main/INFO]: Received new training data for mana-and-artifice:manaweave_patterns/diamond
[18:46:24] [main/INFO]: Received new training data for mana-and-artifice:manaweave_patterns/triangle
[18:46:24] [main/INFO]: Modified & removed recipes in 304.7 ms
[18:46:24] [main/INFO]: Added recipes in 28.89 ms
[18:46:24] [main/INFO]: Added 1722 recipes, removed 1336 recipes, modified 7877 recipes, with 0 failed recipes and 0 fall-backed recipes
[18:46:24] [main/INFO]: Advancement Modification Manager has loaded 8 sets of modifiers
[18:46:24] [main/INFO]: Injecting loot table 'silentgear:inject/chests/bastion_bridge' into 'minecraft:chests/bastion_bridge'
[18:46:25] [main/INFO]: Injecting loot table 'silentgear:inject/chests/bastion_other' into 'minecraft:chests/bastion_other'
[18:46:25] [main/INFO]: Injecting loot table 'silentgear:inject/chests/bastion_treasure' into 'minecraft:chests/bastion_treasure'
[18:46:25] [main/INFO]: Injecting loot table 'silentgear:inject/entities/spider' into 'minecraft:entities/spider'
[18:46:27] [main/INFO]: Injecting loot table 'silentgear:inject/chests/ruined_portal' into 'minecraft:chests/ruined_portal'
[18:46:27] [main/INFO]: Injecting loot table 'silentgear:inject/entities/cave_spider' into 'minecraft:entities/cave_spider'
[18:46:27] [main/INFO]: Registered 18 additional loot tables.
[18:46:27] [main/INFO]: [functions] Found 0 tags, added 0 objects, removed 0 objects
[18:46:27] [main/INFO]: [functions] Found 0 tags, added 0 objects, removed 0 objects
[18:46:27] [main/ERROR]: Parsing error loading custom advancement twilightforest:alt/compat/tconstruct: Unknown item id 'tconstruct:book'
[18:46:27] [main/ERROR]: Parsing error loading custom advancement pedestals:main/craft_filter: Expected item to be an item, was unknown string 'pedestals:coin/filteritemstack'
[18:46:27] [main/INFO]: Loaded 12913 advancements
[18:46:27] [main/INFO]: Registered 53 additional recipes.
[18:46:27] [main/INFO]: Reloading HammerLib recipes...
[18:46:27] [main/INFO]: HammerLib injected 25 recipes into recipe map.
[18:46:27] [main/INFO]: Reloading 1 custom registries.
[18:46:27] [main/INFO]: 1 custom registries reloaded, added 0 total recipes.
[18:46:27] [main/INFO]: Registered 25 additional recipes.
[18:46:27] [main/INFO]: Loading comb recipes for 85 bees...
[18:46:27] [main/INFO]: Validating Honey Effects...
[18:46:27] [main/INFO]: Validating Honey Effects...
[18:46:27] [main/INFO]: Loaded 28 affix loot entries from resources.
[18:46:27] [main/INFO]: Registered 6 boss gear sets.
[18:46:27] [main/INFO]: Loaded 6 boss items from resources.
[18:46:27] [main/INFO]: Loaded 8 spawner items from resources.
[18:46:28] [main/INFO]: Loading Distillation Recipes.
[18:46:28] [main/INFO]: Loading Reservoirs.
[18:46:28] [main/INFO]: Loading Coker-Unit Recipes.
[18:46:28] [main/INFO]: Loading Sulfur Recovery Recipes.
[18:46:28] [main/INFO]: Reloading trait files
[18:46:28] [main/INFO]: Registered 74 traits
[18:46:28] [main/INFO]: Reloading part files
[18:46:28] [main/INFO]: Registered 45 parts
[18:46:28] [main/INFO]: Reloading material files
[18:46:28] [main/INFO]: Skipped loading 7 material(s), as their conditions were not met. This is usually NOT an error!
[18:46:28] [main/INFO]: Skipped materials: silentgear:aluminum_steel, silentgear:bismuth, silentgear:bismuth_brass, silentgear:bismuth_steel, silentgear:redstone_alloy, silentgear:refined_iron, silentgear:titanium
[18:46:28] [main/INFO]: Beginning loading of data for data loader: tiny_block_overrides
[18:46:28] [main/INFO]: Data loader for tiny_block_overrides loaded 1 jsons
[18:46:29] [main/INFO]: ExoticDrops rolls:1 chance:15.0 weights:[4, 4, 2, 1, 1]
[18:46:30] [main/INFO]: Loaded 16 elementalcraft:shrine_upgrades
[18:46:30] [main/INFO]: Loaded 37 elementalcraft:tool_infusions
[18:46:30] [main/INFO]: Loaded 10 elementalcraft:runes
[18:46:30] [main/INFO]: Loaded 16 elementalcraft:spell_properties
[18:46:30] [main/INFO]: [il_tags/elementalcraft_runes] Found 3 tags, added 0 objects, removed 0 objects
[18:46:30] [main/INFO]: [il_tags/elementalcraft_runes] Found 3 tags, added 0 objects, removed 0 objects
[18:46:30] [main/INFO]: Loaded 1 DataPack Anvil TagCollection
[18:46:30] [main/INFO]: Built PerkTree with 417 perks!
[18:46:30] [main/INFO]: Loading data...
[18:46:32] [main/INFO]: Done.
[18:46:32] [main/INFO]: Couldn't fully analyze 1 compressed_iron_boots, missing knowledge for {1 leather_boots=1.0}
[18:46:32] [main/INFO]: Couldn't fully analyze 1 mattock_nether, missing knowledge for {1 mattock=1.0}
[18:46:32] [main/INFO]: Couldn't fully analyze 1 compressed_iron_chestplate, missing knowledge for {1 leather_chestplate=1.0}
[18:46:32] [main/INFO]: Couldn't fully analyze 1 alfsteel_aiot, missing knowledge for {1 alfsteel_aiot=1.0}
[18:46:32] [main/INFO]: Couldn't fully analyze 1 platinum_jetpack, missing knowledge for {1 electrum_jetpack=1.0}
[18:46:32] [main/INFO]: Couldn't fully analyze 1 creative_jetpack, missing knowledge for {1 unobtainium_jetpack=1.0}
[18:46:32] [main/INFO]: Couldn't fully analyze 1 compressed_iron_leggings, missing knowledge for {1 leather_leggings=1.0}
[18:46:32] [main/INFO]: Couldn't fully analyze 1 compressed_iron_helmet, missing knowledge for {1 leather_helmet=1.0}
[18:46:32] [main/INFO]: Couldn't fully analyze 1 pneumatic_leggings, missing knowledge for {1 compressed_iron_leggings=1.0}
[18:46:32] [main/INFO]: Finished recipe profiler for Arc Recycling, took 640 milliseconds
[18:46:32] [main/INFO]: Beginning load of custom recipes for colony workers
[18:46:32] [main/INFO]: Loaded 464 recipes for 14 crafters
[18:46:32] [main/INFO]: Beginning load of research for University.
[18:46:32] [main/INFO]: Loaded 184 recipes for 4 research branches
[18:46:32] [main/INFO]: Loaded 18 recipes
[18:46:32] [main/INFO]: Registered 11 blocks with enchanting stats.
[18:46:32] [main/INFO]: Loaded 13 normal and 13 rare Wandering Trader trade options.
[18:46:32] [main/INFO]: Loaded cucumber-tags.json in 0 ms
[18:46:32] [main/INFO]: 69 materials loaded
[18:46:33] [main/INFO]: 153 stats loaded for 70 materials
[18:46:33] [main/INFO]: Recipes for potions: eidolon:long_anchored, potionsmaster:uranium_sight, minecraft:water_breathing, apotheosis:long_resistance, upgrade_aquatic:vibing_long, cyclic:strong_haste, upgrade_aquatic:vibing, potionsmaster:iron_sight, mana-and-artifice:light_mana_potion, minecraft:strong_slowness, minecraft:long_invisibility, minecraft:long_slow_falling, apotheosis:long_haste, minecraft:strength, potionsmaster:copper_sight, cyclic:levitation, quark:long_resistance, minecraft:long_regeneration, potionsmaster:zinc_sight, quark:long_danger_sight, potionsmaster:nickel_sight, minecraft:fire_resistance, minecraft:harming, apotheosis:haste, upgrade_aquatic:restfulness_strong, cyclic:resistance, cyclic:wither, ars_nouveau:spell_damage, ars_nouveau:spell_damage_long, minecraft:strong_strength, apotheosis:wither, minecraft:long_strength, upgrade_aquatic:insomnia, minecraft:strong_regeneration, minecraft:strong_swiftness, apotheosis:sundering, potionsmaster:unobtainium_sight, apotheosis:knowledge, mana-and-artifice:superior_mana_potion, minecraft:long_poison, ars_nouveau:mana_regen_potion_long, quark:resistance, quark:long_resilience, potionsmaster:netherite_sight, upgrade_aquatic:vibing_strong, potionsmaster:tin_sight, quark:strong_resistance, upgrade_aquatic:repellence, apotheosis:strong_knowledge, minecraft:long_slowness, cyclic:swimspeed, minecraft:invisibility, minecraft:slow_falling, minecraft:long_weakness, minecraft:mundane, minecraft:strong_healing, mana-and-artifice:minor_mana_potion, minecraft:regeneration, upgrade_aquatic:restfulness, resourcefulbees:calming, potionsmaster:silver_sight, resourcefulbees:long_calming, eidolon:chilled, upgrade_aquatic:repellence_strong, potionsmaster:diamond_sight, minecraft:poison, minecraft:long_water_breathing, minecraft:night_vision, apotheosis:strong_sundering, apotheosis:long_fatigue, potionsmaster:osmium_sight, minecraft:luck, apotheosis:absorption, upgrade_aquatic:repellence_long, potionsmaster:lead_sight, minecraft:strong_turtle_master, cyclic:stun, minecraft:long_fire_resistance, apotheosis:long_sundering, eidolon:anchored, potionsmaster:aluminium_sight, minecraft:turtle_master, minecraft:water, potionsmaster:crimsoniron_sight, minecraft:long_night_vision, apotheosis:fatigue, minecraft:swiftness, apotheosis:long_wither, minecraft:long_turtle_master, apotheosis:strong_fatigue, minecraft:strong_leaping, apotheosis:strong_wither, apotheosis:strong_haste, ars_nouveau:spell_damage_strong, potionsmaster:bismuth_sight, minecraft:thick, minecraft:long_leaping, minecraft:healing, minecraft:strong_harming, potionsmaster:allthemodium_sight, potionsmaster:vibranium_sight, apotheosis:resistance, potionsmaster:lapis_sight, potionsmaster:platinum_sight, potionsmaster:emerald_sight, upgrade_aquatic:insomnia_strong, minecraft:slowness, cyclic:haste, minecraft:long_swiftness, minecraft:strong_poison, quark:resilience, minecraft:weakness, quark:danger_sight, minecraft:leaping, apotheosis:strong_absorption, ars_nouveau:mana_regen_potion_strong, potionsmaster:coal_sight, apotheosis:strong_resistance, mana-and-artifice:greater_mana_potion, apotheosis:long_absorption, ars_nouveau:mana_regen_potion, mana-and-artifice:mana_potion, minecraft:awkward, apotheosis:long_knowledge, potionsmaster:redstone_sight, potionsmaster:gold_sight, quark:strong_resilience, cyclic:blind, eidolon:long_chilled, cyclic:hunger, potionsmaster:quartz_sight
[18:46:35] [main/INFO]: Loading vanilla base decorator
[18:46:51] [main/INFO]: Client cache cleared!
[18:47:05] [main/INFO]: Tags Loaded
[18:47:05] [main/INFO]: Tags Reloaded
[18:47:05] [main/INFO]: Validating Mutations...
[18:47:05] [main/INFO]: Loading reactor moderators
[18:47:05] [main/INFO]: Loaded 52 moderator data entries
[18:47:05] [main/INFO]: Loaded 78 moderator entries
[18:47:05] [main/INFO]: Loading turbine coils
[18:47:05] [main/INFO]: Loaded 15 coil data entries
[18:47:05] [main/INFO]: Loaded 30 coil entries
[18:47:05] [main/INFO]: Loading fluid transitions
[18:47:06] [main/INFO]: Loaded 6 transitions data entries
[18:47:06] [main/INFO]: Loaded 6 liquid transition entries
[18:47:06] [main/INFO]: Loaded 8 gas transition entries
[18:47:06] [main/INFO]: Tags Reloaded
[18:47:06] [Server thread/INFO]: Starting integrated minecraft server version 1.16.5
[18:47:06] [Server thread/INFO]: Generating keypair
[18:47:06] [Server thread/INFO]: Loading config file engineerstools-server.toml
[18:47:06] [Server thread/INFO]: REDIA tool config: torch-placing, hoeing, tree-felling, safe-attack, durability:3000, initial-durability:100
[18:47:06] [Server thread/INFO]: REDIA tool efficiency curve: [0,1,1,2,2,3,3,3,3,4]
[18:47:06] [Server thread/INFO]: REDIA tool fortune curve: [0,0,0,0,1,1,1,1,2,3]
[18:47:06] [Server thread/INFO]: Stimpack config: uses:2, trigger:3.0 hearts, inst-heal:3.0 hearts.
[18:47:06] [Server thread/INFO]: Diving Capsule config: uses:10(dmg 10), trigger:3 bubbles, push:7 bubbles.
[18:47:06] [Server thread/INFO]: Musli Bar: hunger:6, saturation:1.2
[18:47:06] [Server thread/INFO]: Musli Press: storage:768hunger/512seeds, bar:8hunger/1seeds
[18:47:06] [Server thread/INFO]: Added immersivepetroleum:gasoline as Portable Generator Fuel. (256RF/t 5mB/t)
[18:47:06] [Server thread/INFO]: Added immersivepetroleum:gasoline as Motorboat Fuel. (1 mB/t)
[18:47:06] [Server thread/ERROR]: Encountered an unexpected exception
net.minecraftforge.fml.config.ConfigFileTypeHandler$ConfigLoadingException: Failed loading config file toolbelt-server.toml of type SERVER for modid toolbelt
	at net.minecraftforge.fml.config.ConfigFileTypeHandler.lambda$reader$1(ConfigFileTypeHandler.java:61) ~[?:?]
	at net.minecraftforge.fml.config.ConfigFileTypeHandler$$Lambda$32836/1873938551.apply(Unknown Source) ~[?:?]
	at net.minecraftforge.fml.config.ConfigTracker.openConfig(ConfigTracker.java:104) ~[?:?]
	at net.minecraftforge.fml.config.ConfigTracker.lambda$loadConfigs$1(ConfigTracker.java:83) ~[?:?]
	at net.minecraftforge.fml.config.ConfigTracker$$Lambda$32835/1315555379.accept(Unknown Source) ~[?:?]
	at java.lang.Iterable.forEach(Iterable.java:75) ~[?:1.8.0_51]
	at java.util.Collections$SynchronizedCollection.forEach(Collections.java:2062) ~[?:1.8.0_51]
	at net.minecraftforge.fml.config.ConfigTracker.loadConfigs(ConfigTracker.java:83) ~[?:?]
	at net.minecraftforge.fml.server.ServerLifecycleHooks.handleServerAboutToStart(ServerLifecycleHooks.java:94) ~[?:?]
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method) ~[?:1.8.0_51]
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62) ~[?:1.8.0_51]
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43) ~[?:1.8.0_51]
	at java.lang.reflect.Method.invoke(Method.java:497) ~[?:1.8.0_51]
	at net.optifine.reflect.Reflector.callBoolean(Reflector.java:809) ~[?:?]
	at net.minecraft.server.integrated.IntegratedServer.func_71197_b(IntegratedServer.java:83) ~[?:?]
	at net.minecraft.server.MinecraftServer.func_240802_v_(MinecraftServer.java:621) [?:?]
	at net.minecraft.server.MinecraftServer.func_240783_a_(MinecraftServer.java:232) [?:?]
	at net.minecraft.server.MinecraftServer$$Lambda$47914/1888176107.run(Unknown Source) [?:?]
	at java.lang.Thread.run(Thread.java:745) [?:1.8.0_51]
Caused by: com.electronwill.nightconfig.core.io.ParsingException: Not enough data available
	at com.electronwill.nightconfig.core.io.ParsingException.notEnoughData(ParsingException.java:22) ~[core-3.6.3.jar:?]
	at com.electronwill.nightconfig.core.io.ReaderInput.directReadChar(ReaderInput.java:36) ~[core-3.6.3.jar:?]
	at com.electronwill.nightconfig.core.io.AbstractInput.readChar(AbstractInput.java:49) ~[core-3.6.3.jar:?]
	at com.electronwill.nightconfig.core.io.AbstractInput.readCharsUntil(AbstractInput.java:123) ~[core-3.6.3.jar:?]
	at com.electronwill.nightconfig.toml.TableParser.parseKey(TableParser.java:166) ~[toml-3.6.3.jar:?]
	at com.electronwill.nightconfig.toml.TableParser.parseDottedKey(TableParser.java:145) ~[toml-3.6.3.jar:?]
	at com.electronwill.nightconfig.toml.TableParser.parseNormal(TableParser.java:55) ~[toml-3.6.3.jar:?]
	at com.electronwill.nightconfig.toml.TomlParser.parse(TomlParser.java:44) ~[toml-3.6.3.jar:?]
	at com.electronwill.nightconfig.toml.TomlParser.parse(TomlParser.java:37) ~[toml-3.6.3.jar:?]
	at com.electronwill.nightconfig.core.io.ConfigParser.parse(ConfigParser.java:113) ~[core-3.6.3.jar:?]
	at com.electronwill.nightconfig.core.io.ConfigParser.parse(ConfigParser.java:219) ~[core-3.6.3.jar:?]
	at com.electronwill.nightconfig.core.io.ConfigParser.parse(ConfigParser.java:202) ~[core-3.6.3.jar:?]
	at com.electronwill.nightconfig.core.file.WriteSyncFileConfig.load(WriteSyncFileConfig.java:73) ~[core-3.6.3.jar:?]
	at com.electronwill.nightconfig.core.file.AutosaveCommentedFileConfig.load(AutosaveCommentedFileConfig.java:85) ~[core-3.6.3.jar:?]
	at net.minecraftforge.fml.config.ConfigFileTypeHandler.lambda$reader$1(ConfigFileTypeHandler.java:57) ~[?:?]
	... 18 more
[18:47:06] [Server thread/FATAL]: Preparing crash report with UUID ad4b4a50-e7e0-4184-93cd-6a90ef8eb3d5
[18:47:06] [Server thread/ERROR]: This crash report has been saved to: C:\Users\Jeremy\curseforge\minecraft\Instances\All the Mods 6 - ATM6 - 1.16.5\crash-reports\crash-2022-04-09_18.47.06-server.txt
[18:47:06] [Server thread/INFO]: Stopping server
[18:47:06] [Server thread/INFO]: Saving players
[18:47:06] [Server thread/INFO]: Saving worlds
[18:47:06] [Server thread/ERROR]: Exception stopping the server
java.lang.NullPointerException: null
	at net.minecraft.server.MinecraftServer.func_213211_a(MinecraftServer.java:538) ~[?:?]
	at net.minecraft.server.integrated.IntegratedServer.func_213211_a(IntegratedServer.java:450) ~[?:?]
	at net.minecraft.server.MinecraftServer.func_71260_j(MinecraftServer.java:568) ~[?:?]
	at net.minecraft.server.integrated.IntegratedServer.func_71260_j(IntegratedServer.java:246) ~[?:?]
	at net.minecraft.server.MinecraftServer.func_240802_v_(MinecraftServer.java:679) [?:?]
	at net.minecraft.server.MinecraftServer.func_240783_a_(MinecraftServer.java:232) [?:?]
	at net.minecraft.server.MinecraftServer$$Lambda$47914/1888176107.run(Unknown Source) [?:?]
	at java.lang.Thread.run(Thread.java:745) [?:1.8.0_51]
[18:47:21] [Server thread/ERROR]: Exception caught during firing event: No server set.
	Index: 22
	Listeners:
		0: HIGH
		1: ASM: class me.shedaniel.architectury.event.forge.EventHandlerImplCommon event(Lnet/minecraftforge/fml/event/server/FMLServerStoppedEvent;)V
		2: NORMAL
		3: net.minecraftforge.eventbus.EventBus$$Lambda$2867/1577420620@e120a95
		4: ASM: class dev.ftb.mods.ftbessentials.FTBEEventHandler serverStopped(Lnet/minecraftforge/fml/event/server/FMLServerStoppedEvent;)V
		5: net.minecraftforge.eventbus.EventBus$$Lambda$2867/1577420620@8731df4
		6: net.minecraftforge.eventbus.EventBus$$Lambda$2867/1577420620@3bb552bf
		7: net.minecraftforge.eventbus.EventBus$$Lambda$2867/1577420620@70940ad1
		8: ASM: invtweaks.InvTweaksMod@3f489ea8 onServerStopped(Lnet/minecraftforge/fml/event/server/FMLServerStoppedEvent;)V
		9: ASM: net.roguelogix.phosphophyllite.Phosphophyllite@4f2cb33d onServerStopped(Lnet/minecraftforge/fml/event/server/FMLServerStoppedEvent;)V
		10: net.minecraftforge.eventbus.EventBus$$Lambda$2867/1577420620@6e4cf0f4
		11: net.minecraftforge.eventbus.EventBus$$Lambda$2867/1577420620@7ec0dc74
		12: net.minecraftforge.eventbus.EventBus$$Lambda$2867/1577420620@6ff159b9
		13: ASM: class com.terraforged.mod.server.ServerEvents serverStop(Lnet/minecraftforge/fml/event/server/FMLServerStoppedEvent;)V
		14: net.minecraftforge.eventbus.EventBus$$Lambda$2867/1577420620@3f631414
		15: net.minecraftforge.eventbus.EventBus$$Lambda$2867/1577420620@36a1885c
		16: ASM: class dan200.computercraft.shared.CommonHooks onServerStopped(Lnet/minecraftforge/fml/event/server/FMLServerStoppedEvent;)V
		17: net.minecraftforge.eventbus.EventBus$$Lambda$2867/1577420620@4efad180
		18: net.minecraftforge.eventbus.EventBus$$Lambda$2867/1577420620@2b237577
		19: net.minecraftforge.eventbus.EventBus$$Lambda$2867/1577420620@cc717b3
		20: net.minecraftforge.eventbus.EventBus$$Lambda$2867/1577420620@361e8d1f
		21: ASM: class sonar.fluxnetworks.register.CommonEventHandler onServerStopped(Lnet/minecraftforge/fml/event/server/FMLServerStoppedEvent;)V
		22: net.minecraftforge.eventbus.EventBus$$Lambda$2867/1577420620@2ef03c8d
java.lang.IllegalStateException: No server set.
	at appeng.core.worlddata.WorldData.instance(WorldData.java:92)
	at appeng.core.AppEng.serverStopped(AppEng.java:218)
	at appeng.core.AppEng$$Lambda$22756/251928304.accept(Unknown Source)
	at net.minecraftforge.eventbus.EventBus.doCastFilter(EventBus.java:247)
	at net.minecraftforge.eventbus.EventBus.lambda$addListener$11(EventBus.java:239)
	at net.minecraftforge.eventbus.EventBus$$Lambda$2867/1577420620.invoke(Unknown Source)
	at net.minecraftforge.eventbus.EventBus$$Lambda$3181/3802995.invoke(Unknown Source)
	at net.minecraftforge.eventbus.EventBus.post(EventBus.java:302)
	at net.minecraftforge.eventbus.EventBus.post(EventBus.java:283)
	at net.minecraftforge.fml.server.ServerLifecycleHooks.handleServerStopped(ServerLifecycleHooks.java:124)
	at net.minecraft.server.MinecraftServer.func_240802_v_(MinecraftServer.java:683)
	at net.minecraft.server.MinecraftServer.func_240783_a_(MinecraftServer.java:232)
	at net.minecraft.server.MinecraftServer$$Lambda$47914/1888176107.run(Unknown Source)
	at java.lang.Thread.run(Thread.java:745)

[18:47:21] [Server thread/ERROR]: java.lang.IllegalStateException: No server set.
