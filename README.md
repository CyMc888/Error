# Error
29.10 22:57:13 [Server] INFO org.bukkit.command.CommandException: Unhandled exception executing command 'furnitureengine' in plugin FurnitureEngine v1.3.1
29.10 22:57:13 [Server] INFO at org.bukkit.command.PluginCommand.execute(PluginCommand.java:47) ~[patched_1.17.1.jar:git-Paper-"a55617d"]
29.10 22:57:13 [Server] INFO at org.bukkit.command.SimpleCommandMap.dispatch(SimpleCommandMap.java:159) ~[patched_1.17.1.jar:git-Paper-"a55617d"]
29.10 22:57:13 [Server] INFO at org.bukkit.craftbukkit.v1_17_R1.CraftServer.dispatchCommand(CraftServer.java:869) ~[patched_1.17.1.jar:git-Paper-"a55617d"]
29.10 22:57:13 [Server] INFO at net.minecraft.server.network.ServerGamePacketListenerImpl.handleCommand(ServerGamePacketListenerImpl.java:2257) ~[app:?]
29.10 22:57:13 [Server] INFO at net.minecraft.server.network.ServerGamePacketListenerImpl.handleChat(ServerGamePacketListenerImpl.java:2068) ~[app:?]
29.10 22:57:13 [Server] INFO at net.minecraft.server.network.ServerGamePacketListenerImpl.handleChat(ServerGamePacketListenerImpl.java:2049) ~[app:?]
29.10 22:57:13 [Server] INFO at net.minecraft.network.protocol.game.ServerboundChatPacket.handle(ServerboundChatPacket.java:46) ~[app:?]
29.10 22:57:13 [Server] INFO at net.minecraft.network.protocol.game.ServerboundChatPacket.handle(ServerboundChatPacket.java:6) ~[app:?]
29.10 22:57:13 [Server] INFO at net.minecraft.network.protocol.PacketUtils.lambda$ensureRunningOnSameThread$1(PacketUtils.java:56) ~[app:?]
29.10 22:57:13 [Server] INFO at net.minecraft.server.TickTask.run(TickTask.java:18) ~[patched_1.17.1.jar:git-Paper-"a55617d"]
29.10 22:57:13 [Server] INFO at net.minecraft.util.thread.BlockableEventLoop.doRunTask(BlockableEventLoop.java:149) ~[app:?]
29.10 22:57:13 [Server] INFO at net.minecraft.util.thread.ReentrantBlockableEventLoop.doRunTask(ReentrantBlockableEventLoop.java:23) ~[app:?]
29.10 22:57:13 [Server] INFO at net.minecraft.server.MinecraftServer.doRunTask(MinecraftServer.java:1418) ~[patched_1.17.1.jar:git-Paper-"a55617d"]
29.10 22:57:13 [Server] INFO at net.minecraft.server.MinecraftServer.shouldRun(MinecraftServer.java:192) ~[patched_1.17.1.jar:git-Paper-"a55617d"]
29.10 22:57:13 [Server] INFO at net.minecraft.util.thread.BlockableEventLoop.pollTask(BlockableEventLoop.java:122) ~[app:?]
29.10 22:57:13 [Server] INFO at net.minecraft.server.MinecraftServer.pollTaskInternal(MinecraftServer.java:1396) ~[patched_1.17.1.jar:git-Paper-"a55617d"]
29.10 22:57:14 [Server] INFO at net.minecraft.server.MinecraftServer.pollTask(MinecraftServer.java:1389) ~[patched_1.17.1.jar:git-Paper-"a55617d"]
29.10 22:57:14 [Server] INFO at net.minecraft.util.thread.BlockableEventLoop.managedBlock(BlockableEventLoop.java:132) ~[app:?]
29.10 22:57:14 [Server] INFO at net.minecraft.server.MinecraftServer.waitUntilNextTick(MinecraftServer.java:1367) ~[patched_1.17.1.jar:git-Paper-"a55617d"]
29.10 22:57:14 [Server] INFO at net.minecraft.server.MinecraftServer.runServer(MinecraftServer.java:1278) ~[patched_1.17.1.jar:git-Paper-"a55617d"]
29.10 22:57:14 [Server] INFO at net.minecraft.server.MinecraftServer.lambda$spin$0(MinecraftServer.java:319) ~[patched_1.17.1.jar:git-Paper-"a55617d"]
29.10 22:57:14 [Server] INFO at java.lang.Thread.run(Thread.java:831) ~[?:?]
29.10 22:57:14 [Server] INFO Caused by: java.lang.NullPointerException: Cannot invoke "org.bukkit.configuration.ConfigurationSection.getKeys(boolean)" because the return value of "org.bukkit.configuration.file.FileConfiguration.getConfigurationSection(String)" is null
29.10 22:57:14 [Server] INFO at me.mira.furnitureengine.commands.CoreCommand.onCommand(CoreCommand.java:32) ~[FurnitureEngine.jar:?]
29.10 22:57:14 [Server] INFO at org.bukkit.command.PluginCommand.execute(PluginCommand.java:45) ~[patched_1.17.1.jar:git-Paper-"a55617d"]
