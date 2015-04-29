[21:36:53] [Server thread/WARN]: Can't keep up! Did the system time change, or is the server overloaded? Running 4356ms behind, skipping 87 tick(s)
[21:37:14] [Server thread/WARN]: Can't keep up! Did the system time change, or is the server overloaded? Running 2355ms behind, skipping 47 tick(s)
[21:37:36] [Server thread/WARN]: Can't keep up! Did the system time change, or is the server overloaded? Running 2905ms behind, skipping 58 tick(s)
[21:37:51] [Server thread/WARN]: Can't keep up! Did the system time change, or is the server overloaded? Running 2054ms behind, skipping 41 tick(s)
[21:38:02] [Server thread/ERROR]: Encountered an unexpected exception
java.lang.NoClassDefFoundError: net/minecraft/world/World$3
	at net.minecraft.world.World.func_72914_a(World.java:3810) ~[ahb.class:?]
	at net.minecraft.server.MinecraftServer.func_71190_q(MinecraftServer.java:630) ~[MinecraftServer.class:?]
	at net.minecraft.server.dedicated.DedicatedServer.func_71190_q(DedicatedServer.java:334) ~[lt.class:?]
	at net.minecraft.server.MinecraftServer.func_71217_p(MinecraftServer.java:547) ~[MinecraftServer.class:?]
	at net.minecraft.server.MinecraftServer.run(MinecraftServer.java:427) [MinecraftServer.class:?]
	at net.minecraft.server.MinecraftServer$2.run(MinecraftServer.java:685) [li.class:?]
Caused by: java.lang.ClassNotFoundException: net.minecraft.world.World$3
	at net.minecraft.launchwrapper.LaunchClassLoader.findClass(LaunchClassLoader.java:191) ~[launchwrapper-1.11.jar:?]
	at java.lang.ClassLoader.loadClass(Unknown Source) ~[?:1.7.0_71]
	at java.lang.ClassLoader.loadClass(Unknown Source) ~[?:1.7.0_71]
	... 6 more
Caused by: java.lang.OutOfMemoryError: PermGen space
	at java.lang.ClassLoader.defineClass1(Native Method) ~[?:1.7.0_71]
	at java.lang.ClassLoader.defineClass(Unknown Source) ~[?:1.7.0_71]
	at java.security.SecureClassLoader.defineClass(Unknown Source) ~[?:1.7.0_71]
	at net.minecraft.launchwrapper.LaunchClassLoader.findClass(LaunchClassLoader.java:182) ~[launchwrapper-1.11.jar:?]
	at java.lang.ClassLoader.loadClass(Unknown Source) ~[?:1.7.0_71]
	at java.lang.ClassLoader.loadClass(Unknown Source) ~[?:1.7.0_71]
	... 6 more
[21:38:06] [Server thread/INFO]: Stopping server
[21:38:07] [Server thread/ERROR]: Exception stopping the server
java.lang.NoClassDefFoundError: io/netty/channel/DefaultChannelHandlerContext$14
	at io.netty.channel.DefaultChannelHandlerContext.close(DefaultChannelHandlerContext.java:547) ~[DefaultChannelHandlerContext.class:?]
	at io.netty.channel.DefaultChannelHandlerContext.close(DefaultChannelHandlerContext.java:423) ~[DefaultChannelHandlerContext.class:?]
	at io.netty.channel.DefaultChannelPipeline.close(DefaultChannelPipeline.java:826) ~[DefaultChannelPipeline.class:?]
	at io.netty.channel.AbstractChannel.close(AbstractChannel.java:177) ~[AbstractChannel.class:?]
	at net.minecraft.network.NetworkSystem.func_151268_b(NetworkSystem.java:132) ~[nc.class:?]
	at net.minecraft.server.MinecraftServer.func_71260_j(MinecraftServer.java:337) ~[MinecraftServer.class:?]
	at net.minecraft.server.MinecraftServer.run(MinecraftServer.java:480) [MinecraftServer.class:?]
	at net.minecraft.server.MinecraftServer$2.run(MinecraftServer.java:685) [li.class:?]
Caused by: java.lang.ClassNotFoundException: io.netty.channel.DefaultChannelHandlerContext$14
	at net.minecraft.launchwrapper.LaunchClassLoader.findClass(LaunchClassLoader.java:191) ~[launchwrapper-1.11.jar:?]
	at java.lang.ClassLoader.loadClass(Unknown Source) ~[?:1.7.0_71]
	at java.lang.ClassLoader.loadClass(Unknown Source) ~[?:1.7.0_71]
	... 8 more
Caused by: java.lang.OutOfMemoryError: PermGen space
