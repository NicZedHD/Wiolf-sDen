# Wiolf-sDen
Errorcode from the server

Letzte Änderung in der Logdatei: Wed, 29 Apr 2015 21:24:47 +0200

	at net.minecraft.world.chunk.Chunk.func_76631_c(Chunk.java:921) [apx.class:?]
	at net.minecraftforge.common.chunkio.ChunkIOProvider.callStage2(ChunkIOProvider.java:46) [ChunkIOProvider.class:?]
	at net.minecraftforge.common.chunkio.ChunkIOProvider.callStage2(ChunkIOProvider.java:12) [ChunkIOProvider.class:?]
	at net.minecraftforge.common.util.AsynchronousExecutor.skipQueue(AsynchronousExecutor.java:344) [AsynchronousExecutor.class:?]
	at net.minecraftforge.common.util.AsynchronousExecutor.getSkipQueue(AsynchronousExecutor.java:302) [AsynchronousExecutor.class:?]
	at net.minecraftforge.common.chunkio.ChunkIOExecutor.syncChunkLoad(ChunkIOExecutor.java:12) [ChunkIOExecutor.class:?]
	at net.minecraft.world.gen.ChunkProviderServer.loadChunk(ChunkProviderServer.java:126) [ms.class:?]
	at net.minecraft.world.gen.ChunkProviderServer.func_73158_c(ChunkProviderServer.java:101) [ms.class:?]
	at net.minecraft.world.gen.ChunkProviderServer.func_73154_d(ChunkProviderServer.java:199) [ms.class:?]
	at net.minecraft.world.World.func_72964_e(World.java:419) [ahb.class:?]
	at net.minecraft.world.World.func_147439_a(World.java:345) [ahb.class:?]
	at buildcraft.factory.TilePump.queueForPumping(TilePump.java:292) [TilePump.class:?]
	at buildcraft.factory.TilePump.rebuildQueue(TilePump.java:271) [TilePump.class:?]
	at buildcraft.factory.TilePump.getNextIndexToPump(TilePump.java:204) [TilePump.class:?]
	at buildcraft.factory.TilePump.func_145845_h(TilePump.java:107) [TilePump.class:?]
	at net.minecraft.world.World.func_72939_s(World.java:1939) [ahb.class:?]
	at net.minecraft.world.WorldServer.func_72939_s(WorldServer.java:489) [mt.class:?]
	at net.minecraft.server.MinecraftServer.func_71190_q(MinecraftServer.java:636) [MinecraftServer.class:?]
	at net.minecraft.server.dedicated.DedicatedServer.func_71190_q(DedicatedServer.java:334) [lt.class:?]
	at net.minecraft.server.MinecraftServer.func_71217_p(MinecraftServer.java:547) [MinecraftServer.class:?]
	at net.minecraft.server.MinecraftServer.run(MinecraftServer.java:427) [MinecraftServer.class:?]
	at net.minecraft.server.MinecraftServer$2.run(MinecraftServer.java:685) [li.class:?]
Caused by: java.lang.IllegalStateException: Entity is already tracked!
	at net.minecraft.entity.EntityTracker.func_72785_a(EntityTracker.java:196) ~[mn.class:?]
	... 28 more
[21:24:42] [Server thread/ERROR]: Encountered an unexpected exception
java.lang.NoClassDefFoundError: net/minecraft/world/World$3
	at net.minecraft.world.World.func_72914_a(World.java:3810) ~[ahb.class:?]
	at net.minecraft.server.MinecraftServer.func_71190_q(MinecraftServer.java:641) ~[MinecraftServer.class:?]
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
[21:24:45] [Server thread/INFO]: Stopping server
[21:24:45] [Server thread/INFO]: Saving players
[21:24:47] [Server thread/ERROR]: Exception stopping the server
java.lang.OutOfMemoryError: PermGen space
