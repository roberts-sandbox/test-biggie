This is a list of all functions available for use in BlockLauncher Addon Mods.  

* List

|Function|On the wiki|Parameters|Returns|Mangled version|
|Stopwatch::~Stopwatch|No|()|IDK|_ZN9StopwatchD2Ev|
|Stopwatch::~Stopwatch|No|()|IDK|_ZN9StopwatchD1Ev|
|Tile::onFertilized|No|(TileSource*, int, int, int)|IDK|_ZN4Tile12onFertilizedEP10TileSourceiii|
|Tile::isObstructingChests|No|(TileSource*, int, int, int)|IDK|_ZN4Tile19isObstructingChestsEP10TileSourceiii|
|Tile::solid|No|(undefined|IDK|_ZN4Tile5solidE|
|Tile::getTesselatedUVs|No|()|IDK|_ZN4Tile16getTesselatedUVsEv|
|Tile::tick|No|(TileSource*, int, int, int, Random*)|IDK|_ZN4Tile4tickEP10TileSourceiiiP6Random|
|Tile::animateTick|No|(TileSource*, int, int, int, Random*)|IDK|_ZN4Tile11animateTickEP10TileSourceiiiP6Random|
|Tile::onPlace|No|(TileSource*, int, int, int)|IDK|_ZN4Tile7onPlaceEP10TileSourceiii|
|Tile::onRemove|No|(TileSource*, int, int, int)|IDK|_ZN4Tile8onRemoveEP10TileSourceiii|
|Tile::getSecondPart|No|(TileSource*, int, int, int, TilePos&)|IDK|_ZN4Tile13getSecondPartEP10TileSourceiiiR7TilePos|
|Tile::onGraphicsModeChanged|No|(bool, bool)|IDK|_ZN4Tile21onGraphicsModeChangedEbb|
|Tile::wasExploded|No|(TileSource*, int, int, int)|IDK|_ZN4Tile11wasExplodedEP10TileSourceiii|
|Tile::stepOn|No|(Entity*, int, int, int)|IDK|_ZN4Tile6stepOnEP6Entityiii|
|Tile::fallOn|No|(TileSource*, int, int, int, Entity*, float)|IDK|_ZN4Tile6fallOnEP10TileSourceiiiP6Entityf|
|Tile::getPlacementDataValue|No|(Mob*, int, int, int, signed char, float, float, float, int)|IDK|_ZN4Tile21getPlacementDataValueEP3Mobiiiafffi|
|Tile::prepareRender|No|(TileSource*, int, int, int)|IDK|_ZN4Tile13prepareRenderEP10TileSourceiii|
|Tile::attack|No|(Player*, int, int, int)|IDK|_ZN4Tile6attackEP6Playeriii|
|Tile::handleEntityInside|No|(TileSource*, int, int, int, Entity*, Vec3&)|IDK|_ZN4Tile18handleEntityInsideEP10TileSourceiiiP6EntityR4Vec3|
|Tile::getColor|No|(int)|IDK|_ZN4Tile8getColorEi|
|Tile::entityInside|No|(TileSource*, int, int, int, Entity*)|IDK|_ZN4Tile12entityInsideEP10TileSourceiiiP6Entity|
|Tile::triggerEvent|No|(TileSource*, int, int, int, int, int)|IDK|_ZN4Tile12triggerEventEP10TileSourceiiiii|
|NetEventCallback::onConnect|No|(RakNet::RakNetGUID const&)|IDK|_ZN16NetEventCallback9onConnectERKN6RakNet10RakNetGUIDE|
|NetEventCallback::onUnableToConnect|No|()|IDK|_ZN16NetEventCallback17onUnableToConnectEv|
|NetEventCallback::handle|No|(RakNet::RakNetGUID const&, LoginStatusPacket*)|IDK|_ZN16NetEventCallback6handleERKN6RakNet10RakNetGUIDEP17LoginStatusPacket|
|NetEventCallback::handle|No|(RakNet::RakNetGUID const&, SetTimePacket*)|IDK|_ZN16NetEventCallback6handleERKN6RakNet10RakNetGUIDEP13SetTimePacket|
|NetEventCallback::handle|No|(RakNet::RakNetGUID const&, StartGamePacket*)|IDK|_ZN16NetEventCallback6handleERKN6RakNet10RakNetGUIDEP15StartGamePacket|
|NetEventCallback::handle|No|(RakNet::RakNetGUID const&, AddItemEntityPacket*)|IDK|_ZN16NetEventCallback6handleERKN6RakNet10RakNetGUIDEP19AddItemEntityPacket|
|NetEventCallback::handle|No|(RakNet::RakNetGUID const&, AddPaintingPacket*)|IDK|_ZN16NetEventCallback6handleERKN6RakNet10RakNetGUIDEP17AddPaintingPacket|
|NetEventCallback::handle|No|(RakNet::RakNetGUID const&, TakeItemEntityPacket*)|IDK|_ZN16NetEventCallback6handleERKN6RakNet10RakNetGUIDEP20TakeItemEntityPacket|
|NetEventCallback::handle|No|(RakNet::RakNetGUID const&, AddEntityPacket*)|IDK|_ZN16NetEventCallback6handleERKN6RakNet10RakNetGUIDEP15AddEntityPacket|
|NetEventCallback::handle|No|(RakNet::RakNetGUID const&, AddMobPacket*)|IDK|_ZN16NetEventCallback6handleERKN6RakNet10RakNetGUIDEP12AddMobPacket|
|NetEventCallback::handle|No|(RakNet::RakNetGUID const&, AddPlayerPacket*)|IDK|_ZN16NetEventCallback6handleERKN6RakNet10RakNetGUIDEP15AddPlayerPacket|
|NetEventCallback::handle|No|(RakNet::RakNetGUID const&, RemovePlayerPacket*)|IDK|_ZN16NetEventCallback6handleERKN6RakNet10RakNetGUIDEP18RemovePlayerPacket|
|NetEventCallback::handle|No|(RakNet::RakNetGUID const&, RemoveEntityPacket*)|IDK|_ZN16NetEventCallback6handleERKN6RakNet10RakNetGUIDEP18RemoveEntityPacket|
|NetEventCallback::handle|No|(RakNet::RakNetGUID const&, MoveEntityPacket*)|IDK|_ZN16NetEventCallback6handleERKN6RakNet10RakNetGUIDEP16MoveEntityPacket|
|NetEventCallback::handle|No|(RakNet::RakNetGUID const&, RotateHeadPacket*)|IDK|_ZN16NetEventCallback6handleERKN6RakNet10RakNetGUIDEP16RotateHeadPacket|
|NetEventCallback::handle|No|(RakNet::RakNetGUID const&, PlaceBlockPacket*)|IDK|_ZN16NetEventCallback6handleERKN6RakNet10RakNetGUIDEP16PlaceBlockPacket|
|NetEventCallback::handle|No|(RakNet::RakNetGUID const&, UpdateBlockPacket*)|IDK|_ZN16NetEventCallback6handleERKN6RakNet10RakNetGUIDEP17UpdateBlockPacket|
|NetEventCallback::handle|No|(RakNet::RakNetGUID const&, ExplodePacket*)|IDK|_ZN16NetEventCallback6handleERKN6RakNet10RakNetGUIDEP13ExplodePacket|
|NetEventCallback::handle|No|(RakNet::RakNetGUID const&, LevelEventPacket*)|IDK|_ZN16NetEventCallback6handleERKN6RakNet10RakNetGUIDEP16LevelEventPacket|
|NetEventCallback::handle|No|(RakNet::RakNetGUID const&, TileEventPacket*)|IDK|_ZN16NetEventCallback6handleERKN6RakNet10RakNetGUIDEP15TileEventPacket|
|NetEventCallback::handle|No|(RakNet::RakNetGUID const&, ChunkDataPacket*)|IDK|_ZN16NetEventCallback6handleERKN6RakNet10RakNetGUIDEP15ChunkDataPacket|
|NetEventCallback::handle|No|(RakNet::RakNetGUID const&, SetEntityDataPacket*)|IDK|_ZN16NetEventCallback6handleERKN6RakNet10RakNetGUIDEP19SetEntityDataPacket|
|NetEventCallback::handle|No|(RakNet::RakNetGUID const&, SetEntityMotionPacket*)|IDK|_ZN16NetEventCallback6handleERKN6RakNet10RakNetGUIDEP21SetEntityMotionPacket|
|NetEventCallback::handle|No|(RakNet::RakNetGUID const&, SetSpawnPositionPacket*)|IDK|_ZN16NetEventCallback6handleERKN6RakNet10RakNetGUIDEP22SetSpawnPositionPacket|
|NetEventCallback::handle|No|(RakNet::RakNetGUID const&, HurtArmorPacket*)|IDK|_ZN16NetEventCallback6handleERKN6RakNet10RakNetGUIDEP15HurtArmorPacket|
|NetEventCallback::handle|No|(RakNet::RakNetGUID const&, SendInventoryPacket*)|IDK|_ZN16NetEventCallback6handleERKN6RakNet10RakNetGUIDEP19SendInventoryPacket|
|NetEventCallback::handle|No|(RakNet::RakNetGUID const&, ContainerOpenPacket*)|IDK|_ZN16NetEventCallback6handleERKN6RakNet10RakNetGUIDEP19ContainerOpenPacket|
|NetEventCallback::handle|No|(RakNet::RakNetGUID const&, ContainerAckPacket*)|IDK|_ZN16NetEventCallback6handleERKN6RakNet10RakNetGUIDEP18ContainerAckPacket|
|NetEventCallback::handle|No|(RakNet::RakNetGUID const&, ContainerSetDataPacket*)|IDK|_ZN16NetEventCallback6handleERKN6RakNet10RakNetGUIDEP22ContainerSetDataPacket|
|NetEventCallback::handle|No|(RakNet::RakNetGUID const&, ChatPacket*)|IDK|_ZN16NetEventCallback6handleERKN6RakNet10RakNetGUIDEP10ChatPacket|
|NetEventCallback::handle|No|(RakNet::RakNetGUID const&, AdventureSettingsPacket*)|IDK|_ZN16NetEventCallback6handleERKN6RakNet10RakNetGUIDEP23AdventureSettingsPacket|
|NetEventCallback::handle|No|(RakNet::RakNetGUID const&, FullChunkDataPacket*)|IDK|_ZN16NetEventCallback6handleERKN6RakNet10RakNetGUIDEP19FullChunkDataPacket|
|NetEventCallback::handle|No|(RakNet::RakNetGUID const&, UnloadChunkPacket*)|IDK|_ZN16NetEventCallback6handleERKN6RakNet10RakNetGUIDEP17UnloadChunkPacket|
|NetEventCallback::onServerFull|No|()|IDK|_ZN16NetEventCallback12onServerFullEv|
|Packet::~Packet|No|()|IDK|_ZN6PacketD2Ev|
|Packet::~Packet|No|()|IDK|_ZN6PacketD1Ev|
|Item::isLiquidClipItem|No|(int) const|IDK|_ZNK4Item16isLiquidClipItemEi|
|Item::getAnimationFrameFor|No|(Mob*) const|IDK|_ZNK4Item20getAnimationFrameForEP3Mob|
|IDataOutput::~IDataOutput|No|()|IDK|_ZN11IDataOutputD2Ev|
|IDataOutput::~IDataOutput|No|()|IDK|_ZN11IDataOutputD1Ev|
|IDataInput::~IDataInput|No|()|IDK|_ZN10IDataInputD2Ev|
|IDataInput::~IDataInput|No|()|IDK|_ZN10IDataInputD1Ev|
|BytesDataOutput::writeFloat|No|(float)|IDK|_ZN15BytesDataOutput10writeFloatEf|
|BytesDataOutput::writeDouble|No|(double)|IDK|_ZN15BytesDataOutput11writeDoubleEd|
|BytesDataOutput::writeByte|No|(char)|IDK|_ZN15BytesDataOutput9writeByteEc|
|BytesDataOutput::writeShort|No|(short)|IDK|_ZN15BytesDataOutput10writeShortEs|
|BytesDataOutput::writeInt|No|(int)|IDK|_ZN15BytesDataOutput8writeIntEi|
|BytesDataOutput::writeLongLong|No|(long long)|IDK|_ZN15BytesDataOutput13writeLongLongEx|
|BytesDataInput::readFloat|No|()|IDK|_ZN14BytesDataInput9readFloatEv|
|BytesDataInput::readDouble|No|()|IDK|_ZN14BytesDataInput10readDoubleEv|
|BytesDataInput::readByte|No|()|IDK|_ZN14BytesDataInput8readByteEv|
|BytesDataInput::readShort|No|()|IDK|_ZN14BytesDataInput9readShortEv|
|BytesDataInput::readInt|No|()|IDK|_ZN14BytesDataInput7readIntEv|
|BytesDataInput::readLongLong|No|()|IDK|_ZN14BytesDataInput12readLongLongEv|
|DataItem::~DataItem|No|()|IDK|_ZN8DataItemD2Ev|
|DataItem::~DataItem|No|()|IDK|_ZN8DataItemD1Ev|
|DataItem::isDataEqual|No|(DataItem const&) const|IDK|_ZNK8DataItem11isDataEqualERKS_|
|Entity::getShadowRadius|No|()|IDK|_ZN6Entity15getShadowRadiusEv|
|Entity::isSurfaceMob|No|() const|IDK|_ZNK6Entity12isSurfaceMobEv|
|Entity::handleEntityEvent|No|(char)|IDK|_ZN6Entity17handleEntityEventEc|
|Entity::getEntityTypeId|No|() const|IDK|_ZNK6Entity15getEntityTypeIdEv|
|Entity::queryEntityRenderer|No|()|IDK|_ZN6Entity19queryEntityRendererEv|
|Entity::onSynchedDataUpdate|No|(int)|IDK|_ZN6Entity19onSynchedDataUpdateEi|
|Tag::deleteChildren|No|()|IDK|_ZN3Tag14deleteChildrenEv|
|ByteTag::write|No|(IDataOutput*)|IDK|_ZN7ByteTag5writeEP11IDataOutput|
|ByteTag::load|No|(IDataInput*)|IDK|_ZN7ByteTag4loadEP10IDataInput|
|ByteTag::getId|No|() const|IDK|_ZNK7ByteTag5getIdEv|
|IntTag::write|No|(IDataOutput*)|IDK|_ZN6IntTag5writeEP11IDataOutput|
|IntTag::load|No|(IDataInput*)|IDK|_ZN6IntTag4loadEP10IDataInput|
|IntTag::getId|No|() const|IDK|_ZNK6IntTag5getIdEv|
|ListTag::write|No|(IDataOutput*)|IDK|_ZN7ListTag5writeEP11IDataOutput|
|ListTag::getId|No|() const|IDK|_ZNK7ListTag5getIdEv|
|ListTag::deleteChildren|No|()|IDK|_ZN7ListTag14deleteChildrenEv|
|StringTag::write|No|(IDataOutput*)|IDK|_ZN9StringTag5writeEP11IDataOutput|
|StringTag::getId|No|() const|IDK|_ZNK9StringTag5getIdEv|
|CompoundTag::getId|No|() const|IDK|_ZNK11CompoundTag5getIdEv|
|TileSourceListener::~TileSourceListener|No|()|IDK|_ZN18TileSourceListenerD2Ev|
|TileSourceListener::~TileSourceListener|No|()|IDK|_ZN18TileSourceListenerD1Ev|
|TileSourceListener::onSourceCreated|No|(TileSource*)|IDK|_ZN18TileSourceListener15onSourceCreatedEP10TileSource|
|TileSourceListener::onSourceDestroyed|No|(TileSource*)|IDK|_ZN18TileSourceListener17onSourceDestroyedEP10TileSource|
|TileSourceListener::onTilesDirty|No|(TileSource*, int, int, int, int, int, int)|IDK|_ZN18TileSourceListener12onTilesDirtyEP10TileSourceiiiiii|
|TileSourceListener::onAreaChanged|No|(TileSource&, TilePos const&, TilePos const&)|IDK|_ZN18TileSourceListener13onAreaChangedER10TileSourceRK7TilePosS4_|
|TileSourceListener::onTileChanged|No|(TileSource*, TilePos const&, FullTile, FullTile, int)|IDK|_ZN18TileSourceListener13onTileChangedEP10TileSourceRK7TilePos8FullTileS5_i|
|TileSourceListener::onBrightnessChanged|No|(TileSource&, TilePos const&)|IDK|_ZN18TileSourceListener19onBrightnessChangedER10TileSourceRK7TilePos|
|TileSourceListener::onTileEntityChanged|No|(TileSource&, TileEntity&)|IDK|_ZN18TileSourceListener19onTileEntityChangedER10TileSourceR10TileEntity|
|TileSourceListener::onTileEntityRemoved|No|(TileSource&, std::unique_ptr<TileEntity, std::default_delete<TileEntity> >&)|IDK|_ZN18TileSourceListener19onTileEntityRemovedER10TileSourceRSt10unique_ptrI10TileEntitySt14default_deleteIS3_EE|
|TileSourceListener::onTileEvent|No|(TileSource*, int, int, int, int, int)|IDK|_ZN18TileSourceListener11onTileEventEP10TileSourceiiiii|
|AppPlatformListener::onLowMemory|No|()|IDK|_ZN19AppPlatformListener11onLowMemoryEv|
|AppPlatformListener::onAppSuspended|No|()|IDK|_ZN19AppPlatformListener14onAppSuspendedEv|
|AppPlatformListener::onAppResumed|No|()|IDK|_ZN19AppPlatformListener12onAppResumedEv|
|AppPlatformListener::onAppFocusLost|No|()|IDK|_ZN19AppPlatformListener14onAppFocusLostEv|
|AppPlatformListener::onAppFocusGained|No|()|IDK|_ZN19AppPlatformListener16onAppFocusGainedEv|
|_TickPtr::~_TickPtr|No|()|IDK|_ZN8_TickPtrD2Ev|
|_TickPtr::~_TickPtr|No|()|IDK|_ZN8_TickPtrD1Ev|
|StemTile::mayPlaceOn|No|(int)|IDK|_ZN8StemTile10mayPlaceOnEi|
|Tile::farmland|No|(undefined|IDK|_ZN4Tile8farmlandE|
|StemTile::getColor|No|(int)|IDK|_ZN8StemTile8getColorEi|
|StemTile::getTexture|No|(signed char, int)|IDK|_ZN8StemTile10getTextureEai|
|StemTile::getResource|No|(int, Random*)|IDK|_ZN8StemTile11getResourceEiP6Random|
|StemTile::getResourceCount|No|(Random*)|IDK|_ZN8StemTile16getResourceCountEP6Random|
|Mob::getMaxHealth|No|()|IDK|_ZN3Mob12getMaxHealthEv|
|Mob::finalizeMobSpawn|No|()|IDK|_ZN3Mob16finalizeMobSpawnEv|
|Mob::isBaby|No|()|IDK|_ZN3Mob6isBabyEv|
|Mob::isTamable|No|() const|IDK|_ZNK3Mob9isTamableEv|
|Mob::getCarriedItem|No|()|IDK|_ZN3Mob14getCarriedItemEv|
|Mob::getUseItemDuration|No|()|IDK|_ZN3Mob18getUseItemDurationEv|
|Mob::ate|No|()|IDK|_ZN3Mob3ateEv|
|Mob::isAlliedTo|No|(Mob*)|IDK|_ZN3Mob10isAlliedToEPS_|
|EatTileGoal::setLevel|No|(Level*)|IDK|_ZN11EatTileGoal8setLevelEP5Level|
|EatTileGoal::stop|No|()|IDK|_ZN11EatTileGoal4stopEv|
|EatTileGoal::canContinueToUse|No|()|IDK|_ZN11EatTileGoal16canContinueToUseEv|
|EatTileGoal::getEatAnimationTick|No|()|IDK|_ZN11EatTileGoal19getEatAnimationTickEv|
|ChunkCache::acquireDiscarded|No|(std::unique_ptr<LevelChunk, std::default_delete<LevelChunk> >&)|IDK|_ZN10ChunkCache16acquireDiscardedERSt10unique_ptrI10LevelChunkSt14default_deleteIS1_EE|
|ChunkCache::onAppSuspended|No|()|IDK|_ZN10ChunkCache14onAppSuspendedEv|
|ChunkCache::onLowMemory|No|()|IDK|_ZN10ChunkCache11onLowMemoryEv|
|IMoveInput::~IMoveInput|No|()|IDK|_ZN10IMoveInputD2Ev|
|IMoveInput::~IMoveInput|No|()|IDK|_ZN10IMoveInputD1Ev|
|IMoveInput::tick|No|(Player*)|IDK|_ZN10IMoveInput4tickEP6Player|
|IMoveInput::render|No|(float)|IDK|_ZN10IMoveInput6renderEf|
|IMoveInput::setKey|No|(int, bool)|IDK|_ZN10IMoveInput6setKeyEib|
|IMoveInput::releaseAllKeys|No|()|IDK|_ZN10IMoveInput14releaseAllKeysEv|
|IMoveInput::onConfigChanged|No|(Config const&)|IDK|_ZN10IMoveInput15onConfigChangedERK6Config|
|ITouchScreenModel::~ITouchScreenModel|No|()|IDK|_ZN17ITouchScreenModelD2Ev|
|ITouchScreenModel::~ITouchScreenModel|No|()|IDK|_ZN17ITouchScreenModelD1Ev|
|ITouchScreenModel::getPointerId|No|(MouseAction const&)|IDK|_ZN17ITouchScreenModel12getPointerIdERK11MouseAction|
|ITouchScreenModel::getPointerId|No|(int, int, int)|IDK|_ZN17ITouchScreenModel12getPointerIdEiii|
|IArea::~IArea|No|()|IDK|_ZN5IAreaD2Ev|
|vtable for IArea|No|(undefined|IDK|_ZTV5IArea|
|IArea::~IArea|No|()|IDK|_ZN5IAreaD1Ev|
|TouchAreaModel::getPointerId|No|(MouseAction const&)|IDK|_ZN14TouchAreaModel12getPointerIdERK11MouseAction|
|TouchAreaModel::getPointerId|No|(int, int, int)|IDK|_ZN14TouchAreaModel12getPointerIdEiii|
|RectangleArea::isInside|No|(float, float)|IDK|_ZN13RectangleArea8isInsideEff|
|RectangleArea::centerX|No|()|IDK|_ZN13RectangleArea7centerXEv|
|RectangleArea::centerY|No|()|IDK|_ZN13RectangleArea7centerYEv|
|BaseContainerMenu::setData|No|(int, int)|IDK|_ZN17BaseContainerMenu7setDataEii|
|BaseContainerMenu::isResultSlot|No|(int)|IDK|_ZN17BaseContainerMenu12isResultSlotEi|
|InteractPacket::handle|No|(RakNet::RakNetGUID const&, NetEventCallback*)|IDK|_ZN14InteractPacket6handleERKN6RakNet10RakNetGUIDEP16NetEventCallback|
|TouchscreenInput::setKey|No|(int, bool)|IDK|_ZN16TouchscreenInput6setKeyEib|
|TouchscreenInput::releaseAllKeys|No|()|IDK|_ZN16TouchscreenInput14releaseAllKeysEv|
|StringByteInput::numBytesLeft|No|() const|IDK|_ZNK15StringByteInput12numBytesLeftEv|
|StringByteOutput::numWrittenBytes|No|() const|IDK|_ZNK16StringByteOutput15numWrittenBytesEv|
|Biome::refreshBiome|No|(long)|IDK|_ZN5Biome12refreshBiomeEl|
|DBChunkStorage::hintDiscardBatchBegin|No|()|IDK|_ZN14DBChunkStorage21hintDiscardBatchBeginEv|
|Model::render|No|()|IDK|_ZN5Model6renderEv|
|Model::renderHorrible|No|(float, float, float, float, float, float)|IDK|_ZN5Model14renderHorribleEffffff|
|AgableMob::getShadowRadius|No|()|IDK|_ZN9AgableMob15getShadowRadiusEv|
|Animal::shouldDespawn|No|() const|IDK|_ZNK6Animal13shouldDespawnEv|
|TargetGoal::stop|No|()|IDK|_ZN10TargetGoal4stopEv|
|TargetGoal::~TargetGoal|No|()|IDK|_ZN10TargetGoalD2Ev|
|vtable for Goal|No|(undefined|IDK|_ZTV4Goal|
|TargetGoal::~TargetGoal|No|()|IDK|_ZN10TargetGoalD1Ev|
|WolfModel::setupAnim|No|(float, float, float, float, float, float)|IDK|_ZN9WolfModel9setupAnimEffffff|
|Mth::PI|No|(undefined|IDK|_ZN3Mth2PIE|
|EntityRenderer::renderName|No|(Entity*, float)|IDK|_ZN14EntityRenderer10renderNameEP6Entityf|
|NetherReactorTile::getTexture|No|(signed char, int)|IDK|_ZN17NetherReactorTile10getTextureEai|
|Monster::isSurfaceMob|No|() const|IDK|_ZNK7Monster12isSurfaceMobEv|
|MonsterEggTile::getTexture|No|(signed char, int)|IDK|_ZN14MonsterEggTile10getTextureEai|
|Tile::stoneBrickSmooth|No|(undefined|IDK|_ZN4Tile16stoneBrickSmoothE|
|Tile::stoneBrick|No|(undefined|IDK|_ZN4Tile10stoneBrickE|
|Tile::rock|No|(undefined|IDK|_ZN4Tile4rockE|
|MonsterEggTile::getResourceCount|No|(Random*)|IDK|_ZN14MonsterEggTile16getResourceCountEP6Random|
|MonsterEggTile::getResource|No|(int, Random*)|IDK|_ZN14MonsterEggTile11getResourceEiP6Random|
|HangingEntity::isHangingEntity|No|()|IDK|_ZN13HangingEntity15isHangingEntityEv|
|HangingEntity::isPickable|No|()|IDK|_ZN13HangingEntity10isPickableEv|
|RakDataOutput::numWrittenBytes|No|() const|IDK|_ZNK13RakDataOutput15numWrittenBytesEv|
|RakDataInput::numBytesLeft|No|() const|IDK|_ZNK12RakDataInput12numBytesLeftEv|
|SetEntityDataPacket::handle|No|(RakNet::RakNetGUID const&, NetEventCallback*)|IDK|_ZN19SetEntityDataPacket6handleERKN6RakNet10RakNetGUIDEP16NetEventCallback|
|Stopwatch::print|No|(std::string const&)|IDK|_ZN9Stopwatch5printERKSs|
|CactusTile::getTileAABB|No|(TileSource*, int, int, int, AABB&)|IDK|_ZN10CactusTile11getTileAABBEP10TileSourceiiiR4AABB|
|CactusTile::getTexture|No|(signed char)|IDK|_ZN10CactusTile10getTextureEa|
|CactusTile::onGraphicsModeChanged|No|(bool, bool)|IDK|_ZN10CactusTile21onGraphicsModeChangedEbb|
|CactusTile::entityInside|No|(TileSource*, int, int, int, Entity*)|IDK|_ZN10CactusTile12entityInsideEP10TileSourceiiiP6Entity|
|StoneTile::getResource|No|(int, Random*)|IDK|_ZN9StoneTile11getResourceEiP6Random|
|StoneTile::getSpawnResourcesAuxValue|No|(int)|IDK|_ZN9StoneTile25getSpawnResourcesAuxValueEi|
|LeafTile::getResource|No|(int, Random*)|IDK|_ZN8LeafTile11getResourceEiP6Random|
|Tile::sapling|No|(undefined|IDK|_ZN4Tile7saplingE|
|LeafTile::getSpawnResourcesAuxValue|No|(int)|IDK|_ZN8LeafTile25getSpawnResourcesAuxValueEi|
|OldLogTile::getResource|No|(int, Random*)|IDK|_ZN10OldLogTile11getResourceEiP6Random|
|Tile::log|No|(undefined|IDK|_ZN4Tile3logE|
|NewLogTile::getResource|No|(int, Random*)|IDK|_ZN10NewLogTile11getResourceEiP6Random|
|Tile::log2|No|(undefined|IDK|_ZN4Tile4log2E|
|MegaTreeFeature::~MegaTreeFeature|No|()|IDK|_ZN15MegaTreeFeatureD2Ev|
|vtable for Feature|No|(undefined|IDK|_ZTV7Feature|
|MegaTreeFeature::~MegaTreeFeature|No|()|IDK|_ZN15MegaTreeFeatureD1Ev|
|GuiElement::tick|No|(Minecraft*)|IDK|_ZN10GuiElement4tickEP9Minecraft|
|GuiElement::topRender|No|(Minecraft*, int, int)|IDK|_ZN10GuiElement9topRenderEP9Minecraftii|
|GuiElement::setupPositions|No|()|IDK|_ZN10GuiElement14setupPositionsEv|
|GuiElement::mouseClicked|No|(Minecraft*, int, int, int)|IDK|_ZN10GuiElement12mouseClickedEP9Minecraftiii|
|GuiElement::mouseReleased|No|(Minecraft*, int, int, int)|IDK|_ZN10GuiElement13mouseReleasedEP9Minecraftiii|
|GuiElement::focusuedMouseClicked|No|(Minecraft*, int, int, int)|IDK|_ZN10GuiElement20focusuedMouseClickedEP9Minecraftiii|
|GuiElement::focusuedMouseReleased|No|(Minecraft*, int, int, int)|IDK|_ZN10GuiElement21focusuedMouseReleasedEP9Minecraftiii|
|GuiElement::keyPressed|No|(Minecraft*, int)|IDK|_ZN10GuiElement10keyPressedEP9Minecrafti|
|GuiElement::keyboardNewChar|No|(Minecraft*, std::string, bool)|IDK|_ZN10GuiElement15keyboardNewCharEP9MinecraftSsb|
|GuiElement::backPressed|No|(Minecraft*, bool)|IDK|_ZN10GuiElement11backPressedEP9Minecraftb|
|GuiElement::suppressOtherGUI|No|()|IDK|_ZN10GuiElement16suppressOtherGUIEv|
|GuiElement::setTextboxText|No|(std::string const&)|IDK|_ZN10GuiElement14setTextboxTextERKSs|
|Screen::removed|No|()|IDK|_ZN6Screen7removedEv|
|Screen::confirmResult|No|(bool, int)|IDK|_ZN6Screen13confirmResultEbi|
|Screen::feedMCOEvent|No|(MCOEvent)|IDK|_ZN6Screen12feedMCOEventE8MCOEvent|
|Screen::onTextBoxUpdated|No|(int)|IDK|_ZN6Screen16onTextBoxUpdatedEi|
|Screen::onMojangConnectorStatus|No|(MojangConnectionStatus)|IDK|_ZN6Screen23onMojangConnectorStatusE22MojangConnectionStatus|
|Screen::onInternetUpdate|No|()|IDK|_ZN6Screen16onInternetUpdateEv|
|Screen::guiElementClicked|No|(GuiElement*)|IDK|_ZN6Screen17guiElementClickedEP10GuiElement|
|ImageButton::renderBg|No|(Minecraft*, int, int)|IDK|_ZN11ImageButton8renderBgEP9Minecraftii|
|ImageButton::isSecondImage|No|(bool)|IDK|_ZN11ImageButton13isSecondImageEb|
|Touch::IInventoryPaneCallback::~IInventoryPaneCallback|No|()|IDK|_ZN5Touch22IInventoryPaneCallbackD2Ev|
|vtable for Touch::IInventoryPaneCallback|No|(undefined|IDK|_ZTVN5Touch22IInventoryPaneCallbackE|
|Touch::IInventoryPaneCallback::~IInventoryPaneCallback|No|()|IDK|_ZN5Touch22IInventoryPaneCallbackD1Ev|
|ContainerSetContentPacket::handle|No|(RakNet::RakNetGUID const&, NetEventCallback*)|IDK|_ZN25ContainerSetContentPacket6handleERKN6RakNet10RakNetGUIDEP16NetEventCallback|
|Touch::IngameBlockSelectionScreen::setupPositions|No|()|IDK|_ZN5Touch26IngameBlockSelectionScreen14setupPositionsEv|
|Gui::GuiScale|No|(undefined|IDK|_ZN3Gui8GuiScaleE|
|Touch::IngameBlockSelectionScreen::isAllowed|No|(int)|IDK|_ZN5Touch26IngameBlockSelectionScreen9isAllowedEi|
|non-virtual thunk to Touch::IngameBlockSelectionScreen::isAllowed|No|(int)|IDK|_ZThn132_N5Touch26IngameBlockSelectionScreen9isAllowedEi|
|Touch::IngameBlockSelectionScreen::hasClippingArea|No|(IntRectangle&)|IDK|_ZN5Touch26IngameBlockSelectionScreen15hasClippingAreaER12IntRectangle|
|MoveEntityPacket::handle|No|(RakNet::RakNetGUID const&, NetEventCallback*)|IDK|_ZN16MoveEntityPacket6handleERKN6RakNet10RakNetGUIDEP16NetEventCallback|
|SetEntityLinkPacket::handle|No|(RakNet::RakNetGUID const&, NetEventCallback*)|IDK|_ZN19SetEntityLinkPacket6handleERKN6RakNet10RakNetGUIDEP16NetEventCallback|
|SetEntityMotionPacket::handle|No|(RakNet::RakNetGUID const&, NetEventCallback*)|IDK|_ZN21SetEntityMotionPacket6handleERKN6RakNet10RakNetGUIDEP16NetEventCallback|
|Minecart::isPushable|No|()|IDK|_ZN8Minecart10isPushableEv|
|Minecart::getRideHeight|No|()|IDK|_ZN8Minecart13getRideHeightEv|
|Minecart::isPickable|No|()|IDK|_ZN8Minecart10isPickableEv|
|Minecart::activateMinecart|No|(int, int, int, bool)|IDK|_ZN8Minecart16activateMinecartEiiib|
|Minecart::getShadowHeightOffs|No|()|IDK|_ZN8Minecart19getShadowHeightOffsEv|
|Minecart::lerpTo|No|(float, float, float, float, float, int)|IDK|_ZN8Minecart6lerpToEfffffi|
|Minecart::lerpMotion|No|(float, float, float)|IDK|_ZN8Minecart10lerpMotionEfff|
|Minecart::getEntityTypeId|No|() const|IDK|_ZNK8Minecart15getEntityTypeIdEv|
|Minecart::getShadowRadius|No|()|IDK|_ZN8Minecart15getShadowRadiusEv|
|GuiElementContainer::tick|No|(Minecraft*)|IDK|_ZN19GuiElementContainer4tickEP9Minecraft|
|AvoidMobTypeGoal::canContinueToUse|No|()|IDK|_ZN16AvoidMobTypeGoal16canContinueToUseEv|
|AvoidMobTypeGoal::start|No|()|IDK|_ZN16AvoidMobTypeGoal5startEv|
|Villager::getBaseSpeed|No|()|IDK|_ZN8Villager12getBaseSpeedEv|
|Villager::shouldDespawn|No|() const|IDK|_ZNK8Villager13shouldDespawnEv|
|Villager::getAmbientSound|No|()|IDK|_ZN8Villager15getAmbientSoundEv|
|Villager::getEntityTypeId|No|() const|IDK|_ZNK8Villager15getEntityTypeIdEv|
|WorldLimitChunkSource::releaseChunk|No|(LevelChunk&)|IDK|_ZN21WorldLimitChunkSource12releaseChunkER10LevelChunk|
|FurnaceMenu::setSlot|No|(int, ItemInstance*)|IDK|_ZN11FurnaceMenu7setSlotEiP12ItemInstance|
|FurnaceMenu::tileEntityDestroyedIsInvalid|No|(int)|IDK|_ZN11FurnaceMenu28tileEntityDestroyedIsInvalidEi|
|Particle::addAdditionalSaveData|No|(CompoundTag*)|IDK|_ZN8Particle21addAdditionalSaveDataEP11CompoundTag|
|Particle::readAdditionalSaveData|No|(CompoundTag*)|IDK|_ZN8Particle22readAdditionalSaveDataEP11CompoundTag|
|CritParticle2::normalTick|No|()|IDK|_ZN13CritParticle210normalTickEv|
|FlameParticle::getBrightness|No|(float)|IDK|_ZN13FlameParticle13getBrightnessEf|
|FlameParticle::normalTick|No|()|IDK|_ZN13FlameParticle10normalTickEv|
|LavaParticle::getBrightness|No|(float)|IDK|_ZN12LavaParticle13getBrightnessEf|
|SmokeParticle::normalTick|No|()|IDK|_ZN13SmokeParticle10normalTickEv|
|BreakingItemParticle::init|No|(float, float, float, float, float, float, int)|IDK|_ZN20BreakingItemParticle4initEffffffi|
|Item::items|No|(undefined|IDK|_ZN4Item5itemsE|
|Tile::snow|No|(undefined|IDK|_ZN4Tile4snowE|
|MobFlameParticle::getBrightness|No|(float)|IDK|_ZN16MobFlameParticle13getBrightnessEf|
|CropTile::getResource|No|(int, Random*)|IDK|_ZN8CropTile11getResourceEiP6Random|
|CropTile::getResourceCount|No|(Random*)|IDK|_ZN8CropTile16getResourceCountEP6Random|
|CropTile::mayPlaceOn|No|(int)|IDK|_ZN8CropTile10mayPlaceOnEi|
|CropTile::getBaseSeed|No|()|IDK|_ZN8CropTile11getBaseSeedEv|
|Item::seeds_wheat|No|(undefined|IDK|_ZN4Item11seeds_wheatE|
|CropTile::getBasePlantId|No|()|IDK|_ZN8CropTile14getBasePlantIdEv|
|Item::wheat|No|(undefined|IDK|_ZN4Item5wheatE|
|GuiElement::pointInside|No|(int, int)|IDK|_ZN10GuiElement11pointInsideEii|
|GuiElement::onSelectedChanged|No|()|IDK|_ZN10GuiElement17onSelectedChangedEv|
|Pig::getBaseSpeed|No|()|IDK|_ZN3Pig12getBaseSpeedEv|
|Pig::getEntityTypeId|No|() const|IDK|_ZNK3Pig15getEntityTypeIdEv|
|Pig::getAmbientSound|No|()|IDK|_ZN3Pig15getAmbientSoundEv|
|Pig::getDeathLoot|No|()|IDK|_ZN3Pig12getDeathLootEv|
|Item::porkChop_raw|No|(undefined|IDK|_ZN4Item12porkChop_rawE|
|Item::porkChop_cooked|No|(undefined|IDK|_ZN4Item15porkChop_cookedE|
|Pig::getMaxHealth|No|()|IDK|_ZN3Pig12getMaxHealthEv|
|Pig::useNewAi|No|()|IDK|_ZN3Pig8useNewAiEv|
|LiquidTile::mayPick|No|(int, bool)|IDK|_ZN10LiquidTile7mayPickEib|
|LiquidTile::getTickDelay|No|()|IDK|_ZN10LiquidTile12getTickDelayEv|
|Material::water|No|(undefined|IDK|_ZN8Material5waterE|
|Material::lava|No|(undefined|IDK|_ZN8Material4lavaE|
|LiquidTile::isPathfindable|No|(TileSource*, int, int, int)|IDK|_ZN10LiquidTile14isPathfindableEP10TileSourceiii|
|LiquidTile::getMobToSpawn|No|(TileSource&, TilePos const&) const|IDK|_ZNK10LiquidTile13getMobToSpawnER10TileSourceRK7TilePos|
|LiquidTile::getResourceCount|No|(Random*)|IDK|_ZN10LiquidTile16getResourceCountEP6Random|
|LiquidTile::getResource|No|(int, Random*)|IDK|_ZN10LiquidTile11getResourceEiP6Random|
|LiquidTile::getTexture|No|(signed char)|IDK|_ZN10LiquidTile10getTextureEa|
|FlowerTile::getSpawnResourcesAuxValue|No|(int)|IDK|_ZN10FlowerTile25getSpawnResourcesAuxValueEi|
|ClothTile::getSpawnResourcesAuxValue|No|(int)|IDK|_ZN9ClothTile25getSpawnResourcesAuxValueEi|
|MeleeAttackGoal::setLevel|No|(Level*)|IDK|_ZN15MeleeAttackGoal8setLevelEP5Level|
|NearestAttackableTargetGoal::start|No|()|IDK|_ZN27NearestAttackableTargetGoal5startEv|
|Spider::getShadowRadius|No|()|IDK|_ZN6Spider15getShadowRadiusEv|
|Spider::getBaseSpeed|No|()|IDK|_ZN6Spider12getBaseSpeedEv|
|Spider::useNewAi|No|()|IDK|_ZN6Spider8useNewAiEv|
|NearestAttackableTargetGoal::~NearestAttackableTargetGoal|No|()|IDK|_ZN27NearestAttackableTargetGoalD2Ev|
|NearestAttackableTargetGoal::~NearestAttackableTargetGoal|No|()|IDK|_ZN27NearestAttackableTargetGoalD1Ev|
|LeafTile::onGraphicsModeChanged|No|(bool, bool)|IDK|_ZN8LeafTile21onGraphicsModeChangedEbb|
|PathfinderMob::setAttackTarget|No|(Entity*)|IDK|_ZN13PathfinderMob15setAttackTargetEP6Entity|
|PathfinderMob::shouldHoldGround|No|()|IDK|_ZN13PathfinderMob16shouldHoldGroundEv|
|PathfinderMob::checkHurtTarget|No|(Entity*, float)|IDK|_ZN13PathfinderMob15checkHurtTargetEP6Entityf|
|PathfinderMob::checkCantSeeTarget|No|(Entity*, float)|IDK|_ZN13PathfinderMob18checkCantSeeTargetEP6Entityf|
|PathfinderMob::getWalkTargetValue|No|(TilePos const&)|IDK|_ZN13PathfinderMob18getWalkTargetValueERK7TilePos|
|PathfinderMob::findAttackTarget|No|()|IDK|_ZN13PathfinderMob16findAttackTargetEv|
|FallingTile::getShadowRadius|No|()|IDK|_ZN11FallingTile15getShadowRadiusEv|
|FallingTile::isPickable|No|()|IDK|_ZN11FallingTile10isPickableEv|
|FallingTile::getShadowHeightOffs|No|()|IDK|_ZN11FallingTile19getShadowHeightOffsEv|
|FallingTile::getEntityTypeId|No|() const|IDK|_ZNK11FallingTile15getEntityTypeIdEv|
|Spider::getMaxHealth|No|()|IDK|_ZN6Spider12getMaxHealthEv|
|Spider::makeStuckInWeb|No|()|IDK|_ZN6Spider14makeStuckInWebEv|
|Spider::getEntityTypeId|No|() const|IDK|_ZNK6Spider15getEntityTypeIdEv|
|Spider::getAmbientSound|No|()|IDK|_ZN6Spider15getAmbientSoundEv|
|Spider::getDeathLoot|No|()|IDK|_ZN6Spider12getDeathLootEv|
|Item::string|No|(undefined|IDK|_ZN4Item6stringE|
|LevelListener::~LevelListener|No|()|IDK|_ZN13LevelListenerD2Ev|
|LevelListener::~LevelListener|No|()|IDK|_ZN13LevelListenerD1Ev|
|LevelListener::onSkyColorChanged|No|()|IDK|_ZN13LevelListener17onSkyColorChangedEv|
|LevelListener::allChanged|No|()|IDK|_ZN13LevelListener10allChangedEv|
|LevelListener::addParticle|No|(ParticleType, float, float, float, float, float, float, int)|IDK|_ZN13LevelListener11addParticleE12ParticleTypeffffffi|
|LevelListener::playSound|No|(std::string const&, float, float, float, float, float)|IDK|_ZN13LevelListener9playSoundERKSsfffff|
|LevelListener::playMusic|No|(std::string const&, float, float, float, float)|IDK|_ZN13LevelListener9playMusicERKSsffff|
|LevelListener::playStreamingMusic|No|(std::string const&, int, int, int)|IDK|_ZN13LevelListener18playStreamingMusicERKSsiii|
|LevelListener::onEntityAdded|No|(Entity&)|IDK|_ZN13LevelListener13onEntityAddedER6Entity|
|LevelListener::onEntityRemoved|No|(Entity&)|IDK|_ZN13LevelListener15onEntityRemovedER6Entity|
|LevelListener::onNewChunkFor|No|(Player&, LevelChunk&)|IDK|_ZN13LevelListener13onNewChunkForER6PlayerR10LevelChunk|
|LevelListener::levelEvent|No|(Mob*, int, int, int, int, int)|IDK|_ZN13LevelListener10levelEventEP3Mobiiiii|
|AddEntityPacket::handle|No|(RakNet::RakNetGUID const&, NetEventCallback*)|IDK|_ZN15AddEntityPacket6handleERKN6RakNet10RakNetGUIDEP16NetEventCallback|
|AddItemEntityPacket::handle|No|(RakNet::RakNetGUID const&, NetEventCallback*)|IDK|_ZN19AddItemEntityPacket6handleERKN6RakNet10RakNetGUIDEP16NetEventCallback|
|AddMobPacket::handle|No|(RakNet::RakNetGUID const&, NetEventCallback*)|IDK|_ZN12AddMobPacket6handleERKN6RakNet10RakNetGUIDEP16NetEventCallback|
|AddPaintingPacket::handle|No|(RakNet::RakNetGUID const&, NetEventCallback*)|IDK|_ZN17AddPaintingPacket6handleERKN6RakNet10RakNetGUIDEP16NetEventCallback|
|AddPlayerPacket::handle|No|(RakNet::RakNetGUID const&, NetEventCallback*)|IDK|_ZN15AddPlayerPacket6handleERKN6RakNet10RakNetGUIDEP16NetEventCallback|
|ChatPacket::handle|No|(RakNet::RakNetGUID const&, NetEventCallback*)|IDK|_ZN10ChatPacket6handleERKN6RakNet10RakNetGUIDEP16NetEventCallback|
|LevelEventPacket::handle|No|(RakNet::RakNetGUID const&, NetEventCallback*)|IDK|_ZN16LevelEventPacket6handleERKN6RakNet10RakNetGUIDEP16NetEventCallback|
|LoginStatusPacket::handle|No|(RakNet::RakNetGUID const&, NetEventCallback*)|IDK|_ZN17LoginStatusPacket6handleERKN6RakNet10RakNetGUIDEP16NetEventCallback|
|MessagePacket::handle|No|(RakNet::RakNetGUID const&, NetEventCallback*)|IDK|_ZN13MessagePacket6handleERKN6RakNet10RakNetGUIDEP16NetEventCallback|
|PlayerArmorEquipmentPacket::handle|No|(RakNet::RakNetGUID const&, NetEventCallback*)|IDK|_ZN26PlayerArmorEquipmentPacket6handleERKN6RakNet10RakNetGUIDEP16NetEventCallback|
|RemoveEntityPacket::handle|No|(RakNet::RakNetGUID const&, NetEventCallback*)|IDK|_ZN18RemoveEntityPacket6handleERKN6RakNet10RakNetGUIDEP16NetEventCallback|
|RemovePlayerPacket::handle|No|(RakNet::RakNetGUID const&, NetEventCallback*)|IDK|_ZN18RemovePlayerPacket6handleERKN6RakNet10RakNetGUIDEP16NetEventCallback|
|RotateHeadPacket::handle|No|(RakNet::RakNetGUID const&, NetEventCallback*)|IDK|_ZN16RotateHeadPacket6handleERKN6RakNet10RakNetGUIDEP16NetEventCallback|
|SetSpawnPositionPacket::handle|No|(RakNet::RakNetGUID const&, NetEventCallback*)|IDK|_ZN22SetSpawnPositionPacket6handleERKN6RakNet10RakNetGUIDEP16NetEventCallback|
|SetTimePacket::handle|No|(RakNet::RakNetGUID const&, NetEventCallback*)|IDK|_ZN13SetTimePacket6handleERKN6RakNet10RakNetGUIDEP16NetEventCallback|
|StartGamePacket::handle|No|(RakNet::RakNetGUID const&, NetEventCallback*)|IDK|_ZN15StartGamePacket6handleERKN6RakNet10RakNetGUIDEP16NetEventCallback|
|TileEventPacket::handle|No|(RakNet::RakNetGUID const&, NetEventCallback*)|IDK|_ZN15TileEventPacket6handleERKN6RakNet10RakNetGUIDEP16NetEventCallback|
|UpdateBlockPacket::handle|No|(RakNet::RakNetGUID const&, NetEventCallback*)|IDK|_ZN17UpdateBlockPacket6handleERKN6RakNet10RakNetGUIDEP16NetEventCallback|
|ServerSideNetworkHandler::onPlayerVerified|No|(RestCallTagData const&)|IDK|_ZN24ServerSideNetworkHandler16onPlayerVerifiedERK15RestCallTagData|
|ServerSideNetworkHandler::sendAndClearBatchedPackets|No|()|IDK|_ZN24ServerSideNetworkHandler26sendAndClearBatchedPacketsEv|
|MainChunkSource::getStoredChunks|No|() const|IDK|_ZNK15MainChunkSource15getStoredChunksEv|
|ImageButton::setupDefault|No|()|IDK|_ZN11ImageButton12setupDefaultEv|
|ImageButton::setYOffset|No|(int)|IDK|_ZN11ImageButton10setYOffsetEi|
|OptionButton::isSecondImage|No|(bool)|IDK|_ZN12OptionButton13isSecondImageEb|
|FleeSunGoal::setLevel|No|(Level*)|IDK|_ZN11FleeSunGoal8setLevelEP5Level|
|ClothTileItem::getIcon|No|(int, int, bool) const|IDK|_ZNK13ClothTileItem7getIconEiib|
|ClothTileItem::getLevelDataForAuxValue|No|(int) const|IDK|_ZNK13ClothTileItem23getLevelDataForAuxValueEi|
|LeafTileItem::getLevelDataForAuxValue|No|(int) const|IDK|_ZNK12LeafTileItem23getLevelDataForAuxValueEi|
|LeafTileItem::getIcon|No|(int, int, bool) const|IDK|_ZNK12LeafTileItem7getIconEiib|
|StoneSlabTileItem::getIcon|No|(int, int, bool) const|IDK|_ZNK17StoneSlabTileItem7getIconEiib|
|Tile::stoneSlabHalf|No|(undefined|IDK|_ZN4Tile13stoneSlabHalfE|
|StoneSlabTileItem::getLevelDataForAuxValue|No|(int) const|IDK|_ZNK17StoneSlabTileItem23getLevelDataForAuxValueEi|
|SaplingTileItem::getLevelDataForAuxValue|No|(int) const|IDK|_ZNK15SaplingTileItem23getLevelDataForAuxValueEi|
|SaplingTileItem::getIcon|No|(int, int, bool) const|IDK|_ZNK15SaplingTileItem7getIconEiib|
|BookshelfTile::getTexture|No|(signed char)|IDK|_ZN13BookshelfTile10getTextureEa|
|BookshelfTile::getResourceCount|No|(Random*)|IDK|_ZN13BookshelfTile16getResourceCountEP6Random|
|BookshelfTile::getResource|No|(int, Random*)|IDK|_ZN13BookshelfTile11getResourceEiP6Random|
|Item::book|No|(undefined|IDK|_ZN4Item4bookE|
|CakeTile::mayPlace|No|(TileSource*, int, int, int, signed char)|IDK|_ZN8CakeTile8mayPlaceEP10TileSourceiiia|
|CakeTile::getTexture|No|(signed char, int)|IDK|_ZN8CakeTile10getTextureEai|
|CakeTile::getResourceCount|No|(Random*)|IDK|_ZN8CakeTile16getResourceCountEP6Random|
|ClayTile::getResource|No|(int, Random*)|IDK|_ZN8ClayTile11getResourceEiP6Random|
|Item::clay|No|(undefined|IDK|_ZN4Item4clayE|
|ClayTile::getResourceCount|No|(Random*)|IDK|_ZN8ClayTile16getResourceCountEP6Random|
|DirtTile::getTexture|No|(signed char, int)|IDK|_ZN8DirtTile10getTextureEai|
|GlassTile::getResourceCount|No|(Random*)|IDK|_ZN9GlassTile16getResourceCountEP6Random|
|IceTile::getResourceCount|No|(Random*)|IDK|_ZN7IceTile16getResourceCountEP6Random|
|MultiTextureTile::getSpawnResourcesAuxValue|No|(int)|IDK|_ZN16MultiTextureTile25getSpawnResourcesAuxValueEi|
|ObsidianTile::getResourceCount|No|(Random*)|IDK|_ZN12ObsidianTile16getResourceCountEP6Random|
|ObsidianTile::getResource|No|(int, Random*)|IDK|_ZN12ObsidianTile11getResourceEiP6Random|
|Tile::obsidian|No|(undefined|IDK|_ZN4Tile8obsidianE|
|OreTile::getResource|No|(int, Random*)|IDK|_ZN7OreTile11getResourceEiP6Random|
|Tile::coalOre|No|(undefined|IDK|_ZN4Tile7coalOreE|
|Tile::diamondOre|No|(undefined|IDK|_ZN4Tile10diamondOreE|
|Tile::lapisOre|No|(undefined|IDK|_ZN4Tile8lapisOreE|
|Tile::emeraldOre|No|(undefined|IDK|_ZN4Tile10emeraldOreE|
|Item::emerald|No|(undefined|IDK|_ZN4Item7emeraldE|
|Item::coal|No|(undefined|IDK|_ZN4Item4coalE|
|Item::diamond|No|(undefined|IDK|_ZN4Item7diamondE|
|Item::dye_powder|No|(undefined|IDK|_ZN4Item10dye_powderE|
|OreTile::getSpawnResourcesAuxValue|No|(int)|IDK|_ZN7OreTile25getSpawnResourcesAuxValueEi|
|MetalTile::getTexture|No|(signed char)|IDK|_ZN9MetalTile10getTextureEa|
|QuartzBlockTile::getSpawnResourcesAuxValue|No|(int)|IDK|_ZN15QuartzBlockTile25getSpawnResourcesAuxValueEi|
|RedStoneOreTile::getTickDelay|No|()|IDK|_ZN15RedStoneOreTile12getTickDelayEv|
|RedStoneOreTile::getResource|No|(int, Random*)|IDK|_ZN15RedStoneOreTile11getResourceEiP6Random|
|Item::redStone|No|(undefined|IDK|_ZN4Item8redStoneE|
|ReedTile::canSurvive|No|(TileSource*, int, int, int)|IDK|_ZN8ReedTile10canSurviveEP10TileSourceiii|
|ReedTile::getResource|No|(int, Random*)|IDK|_ZN8ReedTile11getResourceEiP6Random|
|Item::reeds|No|(undefined|IDK|_ZN4Item5reedsE|
|ReedTile::onGraphicsModeChanged|No|(bool, bool)|IDK|_ZN8ReedTile21onGraphicsModeChangedEbb|
|SnowTile::getResource|No|(int, Random*)|IDK|_ZN8SnowTile11getResourceEiP6Random|
|Item::snowBall|No|(undefined|IDK|_ZN4Item8snowBallE|
|SnowTile::getResourceCount|No|(Random*)|IDK|_ZN8SnowTile16getResourceCountEP6Random|
|StonecutterTile::getTexture|No|(signed char)|IDK|_ZN15StonecutterTile10getTextureEa|
|StonecutterTile::use|No|(Player*, int, int, int)|IDK|_ZN15StonecutterTile3useEP6Playeriii|
|TopSnowTile::getResource|No|(int, Random*)|IDK|_ZN11TopSnowTile11getResourceEiP6Random|
|TopSnowTile::getResourceCount|No|(Random*)|IDK|_ZN11TopSnowTile16getResourceCountEP6Random|
|WebTile::entityInside|No|(TileSource*, int, int, int, Entity*)|IDK|_ZN7WebTile12entityInsideEP10TileSourceiiiP6Entity|
|WebTile::getResource|No|(int, Random*)|IDK|_ZN7WebTile11getResourceEiP6Random|
|WorkbenchTile::getTexture|No|(signed char)|IDK|_ZN13WorkbenchTile10getTextureEa|
|WorkbenchTile::use|No|(Player*, int, int, int)|IDK|_ZN13WorkbenchTile3useEP6Playeriii|
|Recipe::SIZE_3X3|No|(undefined|IDK|_ZN6Recipe8SIZE_3X3E|
|HayBlockTile::getDirTexture|No|(signed char, int)|IDK|_ZN12HayBlockTile13getDirTextureEai|
|SandTile::getTexture|No|(signed char, int)|IDK|_ZN8SandTile10getTextureEai|
|SandTile::getSpawnResourcesAuxValue|No|(int)|IDK|_ZN8SandTile25getSpawnResourcesAuxValueEi|
|ColoredTile::getSpawnResourcesAuxValue|No|(int)|IDK|_ZN11ColoredTile25getSpawnResourcesAuxValueEi|
|MobSpawnerTile::getResourceCount|No|(Random*)|IDK|_ZN14MobSpawnerTile16getResourceCountEP6Random|
|WaterLilyTileItem::isLiquidClipItem|No|(int) const|IDK|_ZNK17WaterLilyTileItem16isLiquidClipItemEi|
|Tile::setLightEmission|No|(float)|IDK|_ZN4Tile16setLightEmissionEf|
|Tile::lightEmission|No|(undefined|IDK|_ZN4Tile13lightEmissionE|
|Tile::init|No|()|IDK|_ZN4Tile4initEv|
|Tile::tiles|No|(undefined|IDK|_ZN4Tile5tilesE|
|Tile::translucency|No|(undefined|IDK|_ZN4Tile12translucencyE|
|Tile::spawnBurnResources|No|(TileSource*, float, float, float)|IDK|_ZN4Tile18spawnBurnResourcesEP10TileSourcefff|
|Tile::destroy|No|(TileSource*, int, int, int, int)|IDK|_ZN4Tile7destroyEP10TileSourceiiii|
|Tile::playerWillDestroy|No|(Player*, int, int, int, int)|IDK|_ZN4Tile17playerWillDestroyEP6Playeriiii|
|Tile::getTexture|No|(signed char, int)|IDK|_ZN4Tile10getTextureEai|
|Tile::getTexture|No|(signed char)|IDK|_ZN4Tile10getTextureEa|
|Tile::mayPick|No|(int, bool)|IDK|_ZN4Tile7mayPickEib|
|Tile::mayPick|No|()|IDK|_ZN4Tile7mayPickEv|
|Tile::getTickDelay|No|()|IDK|_ZN4Tile12getTickDelayEv|
|Tile::getResourceCount|No|(Random*)|IDK|_ZN4Tile16getResourceCountEP6Random|
|Tile::getResource|No|(int, Random*)|IDK|_ZN4Tile11getResourceEiP6Random|
|ThinFenceTile::getResource|No|(int, Random*)|IDK|_ZN13ThinFenceTile11getResourceEiP6Random|
|Tile::getExplosionResistance|No|(Entity*)|IDK|_ZN4Tile22getExplosionResistanceEP6Entity|
|Tile::use|No|(Player*, int, int, int)|IDK|_ZN4Tile3useEP6Playeriii|
|Tile::getColor|No|(TileSource*, int, int, int)|IDK|_ZN4Tile8getColorEP10TileSourceiii|
|Tile::getSignal|No|(TileSource*, int, int, int)|IDK|_ZN4Tile9getSignalEP10TileSourceiii|
|Tile::getSignal|No|(TileSource*, int, int, int, int)|IDK|_ZN4Tile9getSignalEP10TileSourceiiii|
|Tile::isSignalSource|No|()|IDK|_ZN4Tile14isSignalSourceEv|
|Tile::getDirectSignal|No|(TileSource*, int, int, int, int)|IDK|_ZN4Tile15getDirectSignalEP10TileSourceiiii|
|Tile::playerDestroy|No|(Player*, int, int, int, int)|IDK|_ZN4Tile13playerDestroyEP6Playeriiii|
|Tile::canSurvive|No|(TileSource*, int, int, int)|IDK|_ZN4Tile10canSurviveEP10TileSourceiii|
|Tile::getDescriptionId|No|(ItemInstance const*) const|IDK|_ZNK4Tile16getDescriptionIdEPK12ItemInstance|
|Tile::setSoundType|No|(Tile::SoundType const&)|IDK|_ZN4Tile12setSoundTypeERKNS_9SoundTypeE|
|Tile::setLightBlock|No|(int)|IDK|_ZN4Tile13setLightBlockEi|
|Tile::lightBlock|No|(undefined|IDK|_ZN4Tile10lightBlockE|
|Tile::setExplodeable|No|(float)|IDK|_ZN4Tile14setExplodeableEf|
|Tile::setDestroyTime|No|(float)|IDK|_ZN4Tile14setDestroyTimeEf|
|Tile::setTicking|No|(bool)|IDK|_ZN4Tile10setTickingEb|
|Tile::shouldTick|No|(undefined|IDK|_ZN4Tile10shouldTickE|
|Tile::getSpawnResourcesAuxValue|No|(int)|IDK|_ZN4Tile25getSpawnResourcesAuxValueEi|
|Tile::getTileAABB|No|(TileSource*, int, int, int, AABB&)|IDK|_ZN4Tile11getTileAABBEP10TileSourceiiiR4AABB|
|Tile::mayPlace|No|(TileSource*, int, int, int, signed char)|IDK|_ZN4Tile8mayPlaceEP10TileSourceiiia|
|Tile::neighborChanged|No|(TileSource*, int, int, int, int, int, int)|IDK|_ZN4Tile15neighborChangedEP10TileSourceiiiiii|
|Tile::getTextureNum|No|(int)|IDK|_ZN4Tile13getTextureNumEi|
|Tile::getCarriedTexture|No|(signed char, int)|IDK|_ZN4Tile17getCarriedTextureEai|
|Tile::isPathfindable|No|(TileSource*, int, int, int)|IDK|_ZN4Tile14isPathfindableEP10TileSourceiii|
|Tile::getIconYOffset|No|() const|IDK|_ZNK4Tile14getIconYOffsetEv|
|Tile::getShape|No|(unsigned char, AABB&, bool)|IDK|_ZN4Tile8getShapeEhR4AABBb|
|CategoryButton::isSecondImage|No|(bool)|IDK|_ZN14CategoryButton13isSecondImageEb|
|CreativeInventoryScreen::renderGameBehind|No|()|IDK|_ZN23CreativeInventoryScreen16renderGameBehindEv|
|CreativeInventoryScreen::isAllowed|No|(int)|IDK|_ZN23CreativeInventoryScreen9isAllowedEi|
|non-virtual thunk to CreativeInventoryScreen::isAllowed|No|(int)|IDK|_ZThn132_N23CreativeInventoryScreen9isAllowedEi|
|FlowerFeature::~FlowerFeature|No|()|IDK|_ZN13FlowerFeatureD2Ev|
|FlowerFeature::~FlowerFeature|No|()|IDK|_ZN13FlowerFeatureD1Ev|
|std::_Sp_counted_base<|No|(__gnu_cxx::_Lock_policy)2>::_M_destroy|IDK|_ZNSt16_Sp_counted_baseILN9__gnu_cxx12_Lock_policyE2EE10_M_destroyEv|
|std::_Sp_counted_base<|No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_base|IDK|_ZNSt16_Sp_counted_baseILN9__gnu_cxx12_Lock_policyE2EED2Ev|
|vtable for std::_Sp_counted_base<|No|(__gnu_cxx::_Lock_policy)2>|IDK|_ZTVSt16_Sp_counted_baseILN9__gnu_cxx12_Lock_policyE2EE|
|std::_Sp_counted_base<|No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_base|IDK|_ZNSt16_Sp_counted_baseILN9__gnu_cxx12_Lock_policyE2EED1Ev|
|std::_Sp_counted_ptr<CategoryButton*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP14CategoryButtonLN9__gnu_cxx12_Lock_policyE2EED2Ev|
|std::_Sp_counted_ptr<CategoryButton*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP14CategoryButtonLN9__gnu_cxx12_Lock_policyE2EED1Ev|
|std::_Sp_counted_ptr<Touch::InventoryPane*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIPN5Touch13InventoryPaneELN9__gnu_cxx12_Lock_policyE2EED2Ev|
|std::_Sp_counted_ptr<Touch::InventoryPane*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIPN5Touch13InventoryPaneELN9__gnu_cxx12_Lock_policyE2EED1Ev|
|std::_Sp_counted_ptr<ImageWithBackground*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP19ImageWithBackgroundLN9__gnu_cxx12_Lock_policyE2EED2Ev|
|std::_Sp_counted_ptr<ImageWithBackground*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP19ImageWithBackgroundLN9__gnu_cxx12_Lock_policyE2EED1Ev|
|std::_Sp_counted_ptr<NinePatchLayer*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP14NinePatchLayerLN9__gnu_cxx12_Lock_policyE2EED2Ev|
|std::_Sp_counted_ptr<NinePatchLayer*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP14NinePatchLayerLN9__gnu_cxx12_Lock_policyE2EED1Ev|
|std::_Sp_counted_ptr<ZoomLayer*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP9ZoomLayerLN9__gnu_cxx12_Lock_policyE2EED2Ev|
|std::_Sp_counted_ptr<ZoomLayer*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP9ZoomLayerLN9__gnu_cxx12_Lock_policyE2EED1Ev|
|std::_Sp_counted_ptr<LoginOption*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP11LoginOptionLN9__gnu_cxx12_Lock_policyE2EED2Ev|
|std::_Sp_counted_ptr<LoginOption*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP11LoginOptionLN9__gnu_cxx12_Lock_policyE2EED1Ev|
|std::_Sp_counted_ptr<TextBox*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP7TextBoxLN9__gnu_cxx12_Lock_policyE2EED2Ev|
|std::_Sp_counted_ptr<TextBox*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP7TextBoxLN9__gnu_cxx12_Lock_policyE2EED1Ev|
|std::_Sp_counted_ptr<Slider*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP6SliderLN9__gnu_cxx12_Lock_policyE2EED2Ev|
|std::_Sp_counted_ptr<Slider*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP6SliderLN9__gnu_cxx12_Lock_policyE2EED1Ev|
|std::_Sp_counted_ptr<OptionsItem*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP11OptionsItemLN9__gnu_cxx12_Lock_policyE2EED2Ev|
|std::_Sp_counted_ptr<OptionsItem*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP11OptionsItemLN9__gnu_cxx12_Lock_policyE2EED1Ev|
|std::_Sp_counted_ptr<OptionButton*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP12OptionButtonLN9__gnu_cxx12_Lock_policyE2EED2Ev|
|std::_Sp_counted_ptr<OptionButton*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP12OptionButtonLN9__gnu_cxx12_Lock_policyE2EED1Ev|
|std::_Sp_counted_ptr<SmoothZoomLayer*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP15SmoothZoomLayerLN9__gnu_cxx12_Lock_policyE2EED2Ev|
|std::_Sp_counted_ptr<SmoothZoomLayer*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP15SmoothZoomLayerLN9__gnu_cxx12_Lock_policyE2EED1Ev|
|std::_Sp_counted_ptr<leveldb::WriteBatch*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIPN7leveldb10WriteBatchELN9__gnu_cxx12_Lock_policyE2EED2Ev|
|std::_Sp_counted_ptr<leveldb::WriteBatch*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIPN7leveldb10WriteBatchELN9__gnu_cxx12_Lock_policyE2EED1Ev|
|DataItem2<signed char>::~DataItem2|No|()|IDK|_ZN9DataItem2IaED2Ev|
|DataItem2<signed char>::~DataItem2|No|()|IDK|_ZN9DataItem2IaED1Ev|
|DataItem2<float>::~DataItem2|No|()|IDK|_ZN9DataItem2IfED2Ev|
|DataItem2<float>::~DataItem2|No|()|IDK|_ZN9DataItem2IfED1Ev|
|DataItem2<int>::~DataItem2|No|()|IDK|_ZN9DataItem2IiED2Ev|
|DataItem2<int>::~DataItem2|No|()|IDK|_ZN9DataItem2IiED1Ev|
|FleeSunGoal::~FleeSunGoal|No|()|IDK|_ZN11FleeSunGoalD2Ev|
|FleeSunGoal::~FleeSunGoal|No|()|IDK|_ZN11FleeSunGoalD1Ev|
|UpdateBlockPacket::~UpdateBlockPacket|No|()|IDK|_ZN17UpdateBlockPacketD2Ev|
|UpdateBlockPacket::~UpdateBlockPacket|No|()|IDK|_ZN17UpdateBlockPacketD1Ev|
|TileEventPacket::~TileEventPacket|No|()|IDK|_ZN15TileEventPacketD2Ev|
|TileEventPacket::~TileEventPacket|No|()|IDK|_ZN15TileEventPacketD1Ev|
|StartGamePacket::~StartGamePacket|No|()|IDK|_ZN15StartGamePacketD2Ev|
|StartGamePacket::~StartGamePacket|No|()|IDK|_ZN15StartGamePacketD1Ev|
|SetTimePacket::~SetTimePacket|No|()|IDK|_ZN13SetTimePacketD2Ev|
|SetTimePacket::~SetTimePacket|No|()|IDK|_ZN13SetTimePacketD1Ev|
|SetSpawnPositionPacket::~SetSpawnPositionPacket|No|()|IDK|_ZN22SetSpawnPositionPacketD2Ev|
|SetSpawnPositionPacket::~SetSpawnPositionPacket|No|()|IDK|_ZN22SetSpawnPositionPacketD1Ev|
|RemovePlayerPacket::~RemovePlayerPacket|No|()|IDK|_ZN18RemovePlayerPacketD2Ev|
|RemovePlayerPacket::~RemovePlayerPacket|No|()|IDK|_ZN18RemovePlayerPacketD1Ev|
|RemoveEntityPacket::~RemoveEntityPacket|No|()|IDK|_ZN18RemoveEntityPacketD2Ev|
|RemoveEntityPacket::~RemoveEntityPacket|No|()|IDK|_ZN18RemoveEntityPacketD1Ev|
|PlayerArmorEquipmentPacket::~PlayerArmorEquipmentPacket|No|()|IDK|_ZN26PlayerArmorEquipmentPacketD2Ev|
|PlayerArmorEquipmentPacket::~PlayerArmorEquipmentPacket|No|()|IDK|_ZN26PlayerArmorEquipmentPacketD1Ev|
|LoginStatusPacket::~LoginStatusPacket|No|()|IDK|_ZN17LoginStatusPacketD2Ev|
|LoginStatusPacket::~LoginStatusPacket|No|()|IDK|_ZN17LoginStatusPacketD1Ev|
|LevelEventPacket::~LevelEventPacket|No|()|IDK|_ZN16LevelEventPacketD2Ev|
|LevelEventPacket::~LevelEventPacket|No|()|IDK|_ZN16LevelEventPacketD1Ev|
|AddItemEntityPacket::~AddItemEntityPacket|No|()|IDK|_ZN19AddItemEntityPacketD2Ev|
|AddItemEntityPacket::~AddItemEntityPacket|No|()|IDK|_ZN19AddItemEntityPacketD1Ev|
|AddEntityPacket::~AddEntityPacket|No|()|IDK|_ZN15AddEntityPacketD2Ev|
|AddEntityPacket::~AddEntityPacket|No|()|IDK|_ZN15AddEntityPacketD1Ev|
|SpiderTargetGoal::~SpiderTargetGoal|No|()|IDK|_ZN16SpiderTargetGoalD2Ev|
|SpiderTargetGoal::~SpiderTargetGoal|No|()|IDK|_ZN16SpiderTargetGoalD1Ev|
|SetEntityLinkPacket::~SetEntityLinkPacket|No|()|IDK|_ZN19SetEntityLinkPacketD2Ev|
|SetEntityLinkPacket::~SetEntityLinkPacket|No|()|IDK|_ZN19SetEntityLinkPacketD1Ev|
|SavannaTreeFeature::~SavannaTreeFeature|No|()|IDK|_ZN18SavannaTreeFeatureD2Ev|
|SavannaTreeFeature::~SavannaTreeFeature|No|()|IDK|_ZN18SavannaTreeFeatureD1Ev|
|VinesFeature::~VinesFeature|No|()|IDK|_ZN12VinesFeatureD2Ev|
|VinesFeature::~VinesFeature|No|()|IDK|_ZN12VinesFeatureD1Ev|
|MelonFeatrue::~MelonFeatrue|No|()|IDK|_ZN12MelonFeatrueD2Ev|
|MelonFeatrue::~MelonFeatrue|No|()|IDK|_ZN12MelonFeatrueD1Ev|
|MegaJungleTreeFeature::~MegaJungleTreeFeature|No|()|IDK|_ZN21MegaJungleTreeFeatureD2Ev|
|MegaJungleTreeFeature::~MegaJungleTreeFeature|No|()|IDK|_ZN21MegaJungleTreeFeatureD1Ev|
|JungleTreeFeature::~JungleTreeFeature|No|()|IDK|_ZN17JungleTreeFeatureD2Ev|
|JungleTreeFeature::~JungleTreeFeature|No|()|IDK|_ZN17JungleTreeFeatureD1Ev|
|GroundBushFeature::~GroundBushFeature|No|()|IDK|_ZN17GroundBushFeatureD2Ev|
|GroundBushFeature::~GroundBushFeature|No|()|IDK|_ZN17GroundBushFeatureD1Ev|
|IcePatchFeature::~IcePatchFeature|No|()|IDK|_ZN15IcePatchFeatureD2Ev|
|IcePatchFeature::~IcePatchFeature|No|()|IDK|_ZN15IcePatchFeatureD1Ev|
|IceSpikeFeature::~IceSpikeFeature|No|()|IDK|_ZN15IceSpikeFeatureD2Ev|
|IceSpikeFeature::~IceSpikeFeature|No|()|IDK|_ZN15IceSpikeFeatureD1Ev|
|SwampTreeFeature::~SwampTreeFeature|No|()|IDK|_ZN16SwampTreeFeatureD2Ev|
|SwampTreeFeature::~SwampTreeFeature|No|()|IDK|_ZN16SwampTreeFeatureD1Ev|
|TallGrassFeature::~TallGrassFeature|No|()|IDK|_ZN16TallGrassFeatureD2Ev|
|TallGrassFeature::~TallGrassFeature|No|()|IDK|_ZN16TallGrassFeatureD1Ev|
|MegaPineTreeFeature::~MegaPineTreeFeature|No|()|IDK|_ZN19MegaPineTreeFeatureD2Ev|
|MegaPineTreeFeature::~MegaPineTreeFeature|No|()|IDK|_ZN19MegaPineTreeFeatureD1Ev|
|RoofTreeFeature::~RoofTreeFeature|No|()|IDK|_ZN15RoofTreeFeatureD2Ev|
|RoofTreeFeature::~RoofTreeFeature|No|()|IDK|_ZN15RoofTreeFeatureD1Ev|
|PineFeature::~PineFeature|No|()|IDK|_ZN11PineFeatureD2Ev|
|PineFeature::~PineFeature|No|()|IDK|_ZN11PineFeatureD1Ev|
|SpruceFeature::~SpruceFeature|No|()|IDK|_ZN13SpruceFeatureD2Ev|
|SpruceFeature::~SpruceFeature|No|()|IDK|_ZN13SpruceFeatureD1Ev|
|OakFeature::~OakFeature|No|()|IDK|_ZN10OakFeatureD2Ev|
|OakFeature::~OakFeature|No|()|IDK|_ZN10OakFeatureD1Ev|
|DesertWellFeature::~DesertWellFeature|No|()|IDK|_ZN17DesertWellFeatureD2Ev|
|DesertWellFeature::~DesertWellFeature|No|()|IDK|_ZN17DesertWellFeatureD1Ev|
|DeadBushFeature::~DeadBushFeature|No|()|IDK|_ZN15DeadBushFeatureD2Ev|
|DeadBushFeature::~DeadBushFeature|No|()|IDK|_ZN15DeadBushFeatureD1Ev|
|SpringFeature::~SpringFeature|No|()|IDK|_ZN13SpringFeatureD2Ev|
|SpringFeature::~SpringFeature|No|()|IDK|_ZN13SpringFeatureD1Ev|
|PumpkinFeature::~PumpkinFeature|No|()|IDK|_ZN14PumpkinFeatureD2Ev|
|PumpkinFeature::~PumpkinFeature|No|()|IDK|_ZN14PumpkinFeatureD1Ev|
|WaterlilyFeature::~WaterlilyFeature|No|()|IDK|_ZN16WaterlilyFeatureD2Ev|
|WaterlilyFeature::~WaterlilyFeature|No|()|IDK|_ZN16WaterlilyFeatureD1Ev|
|CactusFeature::~CactusFeature|No|()|IDK|_ZN13CactusFeatureD2Ev|
|CactusFeature::~CactusFeature|No|()|IDK|_ZN13CactusFeatureD1Ev|
|ReedsFeature::~ReedsFeature|No|()|IDK|_ZN12ReedsFeatureD2Ev|
|ReedsFeature::~ReedsFeature|No|()|IDK|_ZN12ReedsFeatureD1Ev|
|HugeMushroomFeature::~HugeMushroomFeature|No|()|IDK|_ZN19HugeMushroomFeatureD2Ev|
|HugeMushroomFeature::~HugeMushroomFeature|No|()|IDK|_ZN19HugeMushroomFeatureD1Ev|
|OreFeature::~OreFeature|No|()|IDK|_ZN10OreFeatureD2Ev|
|OreFeature::~OreFeature|No|()|IDK|_ZN10OreFeatureD1Ev|
|SandFeature::~SandFeature|No|()|IDK|_ZN11SandFeatureD2Ev|
|SandFeature::~SandFeature|No|()|IDK|_ZN11SandFeatureD1Ev|
|ClayFeature::~ClayFeature|No|()|IDK|_ZN11ClayFeatureD2Ev|
|ClayFeature::~ClayFeature|No|()|IDK|_ZN11ClayFeatureD1Ev|
|RakDataInput::~RakDataInput|No|()|IDK|_ZN12RakDataInputD2Ev|
|RakDataInput::~RakDataInput|No|()|IDK|_ZN12RakDataInputD1Ev|
|RakDataOutput::~RakDataOutput|No|()|IDK|_ZN13RakDataOutputD2Ev|
|RakDataOutput::~RakDataOutput|No|()|IDK|_ZN13RakDataOutputD1Ev|
|StringByteOutput::~StringByteOutput|No|()|IDK|_ZN16StringByteOutputD2Ev|
|StringByteOutput::~StringByteOutput|No|()|IDK|_ZN16StringByteOutputD1Ev|
|StringByteInput::~StringByteInput|No|()|IDK|_ZN15StringByteInputD2Ev|
|StringByteInput::~StringByteInput|No|()|IDK|_ZN15StringByteInputD1Ev|
|InteractPacket::~InteractPacket|No|()|IDK|_ZN14InteractPacketD2Ev|
|InteractPacket::~InteractPacket|No|()|IDK|_ZN14InteractPacketD1Ev|
|EatTileGoal::~EatTileGoal|No|()|IDK|_ZN11EatTileGoalD2Ev|
|EatTileGoal::~EatTileGoal|No|()|IDK|_ZN11EatTileGoalD1Ev|
|RectangleArea::~RectangleArea|No|()|IDK|_ZN13RectangleAreaD2Ev|
|RectangleArea::~RectangleArea|No|()|IDK|_ZN13RectangleAreaD1Ev|
|std::_Sp_counted_deleter<std::vector<std::unique_ptr<LevelChunk, std::default_delete<LevelChunk> >, std::allocator<std::unique_ptr<LevelChunk, std::default_delete<LevelChunk> > > >*, std::__shared_ptr<std::vector<std::unique_ptr<LevelChunk, std::default_delete<LevelChunk> >, std::allocator<std::unique_ptr<LevelChunk, std::default_delete<LevelChunk> > > >, |No|(__gnu_cxx::_Lock_policy)2>::_Deleter<std::allocator<std::vector<std::unique_ptr<LevelChunk, std::default_delete<LevelChunk> >, std::allocator<std::unique_ptr<LevelChunk, std::default_delete<LevelChunk> > > > > >, std::allocator<std::vector<std::unique_ptr<LevelChunk, std::default_delete<LevelChunk> >, std::allocator<std::unique_ptr<LevelChunk, std::default_delete<LevelChunk> > > > >, |IDK|_ZNSt19_Sp_counted_deleterIPSt6vectorISt10unique_ptrI10LevelChunkSt14default_deleteIS2_EESaIS5_EENSt12__shared_ptrIS7_LN9__gnu_cxx12_Lock_policyE2EE8_DeleterISaIS7_EEESE_LSB_2EED2Ev|
|std::_Sp_counted_deleter<std::vector<std::unique_ptr<LevelChunk, std::default_delete<LevelChunk> >, std::allocator<std::unique_ptr<LevelChunk, std::default_delete<LevelChunk> > > >*, std::__shared_ptr<std::vector<std::unique_ptr<LevelChunk, std::default_delete<LevelChunk> >, std::allocator<std::unique_ptr<LevelChunk, std::default_delete<LevelChunk> > > >, |No|(__gnu_cxx::_Lock_policy)2>::_Deleter<std::allocator<std::vector<std::unique_ptr<LevelChunk, std::default_delete<LevelChunk> >, std::allocator<std::unique_ptr<LevelChunk, std::default_delete<LevelChunk> > > > > >, std::allocator<std::vector<std::unique_ptr<LevelChunk, std::default_delete<LevelChunk> >, std::allocator<std::unique_ptr<LevelChunk, std::default_delete<LevelChunk> > > > >, |IDK|_ZNSt19_Sp_counted_deleterIPSt6vectorISt10unique_ptrI10LevelChunkSt14default_deleteIS2_EESaIS5_EENSt12__shared_ptrIS7_LN9__gnu_cxx12_Lock_policyE2EE8_DeleterISaIS7_EEESE_LSB_2EED1Ev|
|std::_Sp_counted_deleter<std::vector<std::unique_ptr<LevelChunk, std::default_delete<LevelChunk> >, std::allocator<std::unique_ptr<LevelChunk, std::default_delete<LevelChunk> > > >*, std::__shared_ptr<std::vector<std::unique_ptr<LevelChunk, std::default_delete<LevelChunk> >, std::allocator<std::unique_ptr<LevelChunk, std::default_delete<LevelChunk> > > >, |No|(__gnu_cxx::_Lock_policy)2>::_Deleter<std::allocator<std::vector<std::unique_ptr<LevelChunk, std::default_delete<LevelChunk> >, std::allocator<std::unique_ptr<LevelChunk, std::default_delete<LevelChunk> > > > > >, std::allocator<std::vector<std::unique_ptr<LevelChunk, std::default_delete<LevelChunk> >, std::allocator<std::unique_ptr<LevelChunk, std::default_delete<LevelChunk> > > > >, |IDK|_ZNSt19_Sp_counted_deleterIPSt6vectorISt10unique_ptrI10LevelChunkSt14default_deleteIS2_EESaIS5_EENSt12__shared_ptrIS7_LN9__gnu_cxx12_Lock_policyE2EE8_DeleterISaIS7_EEESE_LSB_2EE14_M_get_deleterERKSt9type_info|
|std::_Sp_counted_ptr<CategoryButton*, |No|(__gnu_cxx::_Lock_policy)2>::_M_dispose|IDK|_ZNSt15_Sp_counted_ptrIP14CategoryButtonLN9__gnu_cxx12_Lock_policyE2EE10_M_disposeEv|
|std::_Sp_counted_ptr<CategoryButton*, |No|(__gnu_cxx::_Lock_policy)2>::_M_get_deleter|IDK|_ZNSt15_Sp_counted_ptrIP14CategoryButtonLN9__gnu_cxx12_Lock_policyE2EE14_M_get_deleterERKSt9type_info|
|std::_Sp_counted_ptr<Touch::InventoryPane*, |No|(__gnu_cxx::_Lock_policy)2>::_M_dispose|IDK|_ZNSt15_Sp_counted_ptrIPN5Touch13InventoryPaneELN9__gnu_cxx12_Lock_policyE2EE10_M_disposeEv|
|std::_Sp_counted_ptr<Touch::InventoryPane*, |No|(__gnu_cxx::_Lock_policy)2>::_M_get_deleter|IDK|_ZNSt15_Sp_counted_ptrIPN5Touch13InventoryPaneELN9__gnu_cxx12_Lock_policyE2EE14_M_get_deleterERKSt9type_info|
|std::_Sp_counted_ptr<ImageWithBackground*, |No|(__gnu_cxx::_Lock_policy)2>::_M_dispose|IDK|_ZNSt15_Sp_counted_ptrIP19ImageWithBackgroundLN9__gnu_cxx12_Lock_policyE2EE10_M_disposeEv|
|std::_Sp_counted_ptr<ImageWithBackground*, |No|(__gnu_cxx::_Lock_policy)2>::_M_get_deleter|IDK|_ZNSt15_Sp_counted_ptrIP19ImageWithBackgroundLN9__gnu_cxx12_Lock_policyE2EE14_M_get_deleterERKSt9type_info|
|std::_Sp_counted_ptr<NinePatchLayer*, |No|(__gnu_cxx::_Lock_policy)2>::_M_dispose|IDK|_ZNSt15_Sp_counted_ptrIP14NinePatchLayerLN9__gnu_cxx12_Lock_policyE2EE10_M_disposeEv|
|std::_Sp_counted_ptr<NinePatchLayer*, |No|(__gnu_cxx::_Lock_policy)2>::_M_get_deleter|IDK|_ZNSt15_Sp_counted_ptrIP14NinePatchLayerLN9__gnu_cxx12_Lock_policyE2EE14_M_get_deleterERKSt9type_info|
|std::_Sp_counted_ptr<ZoomLayer*, |No|(__gnu_cxx::_Lock_policy)2>::_M_dispose|IDK|_ZNSt15_Sp_counted_ptrIP9ZoomLayerLN9__gnu_cxx12_Lock_policyE2EE10_M_disposeEv|
|std::_Sp_counted_ptr<ZoomLayer*, |No|(__gnu_cxx::_Lock_policy)2>::_M_get_deleter|IDK|_ZNSt15_Sp_counted_ptrIP9ZoomLayerLN9__gnu_cxx12_Lock_policyE2EE14_M_get_deleterERKSt9type_info|
|std::_Sp_counted_ptr<LoginOption*, |No|(__gnu_cxx::_Lock_policy)2>::_M_dispose|IDK|_ZNSt15_Sp_counted_ptrIP11LoginOptionLN9__gnu_cxx12_Lock_policyE2EE10_M_disposeEv|
|std::_Sp_counted_ptr<LoginOption*, |No|(__gnu_cxx::_Lock_policy)2>::_M_get_deleter|IDK|_ZNSt15_Sp_counted_ptrIP11LoginOptionLN9__gnu_cxx12_Lock_policyE2EE14_M_get_deleterERKSt9type_info|
|std::_Sp_counted_ptr<TextBox*, |No|(__gnu_cxx::_Lock_policy)2>::_M_dispose|IDK|_ZNSt15_Sp_counted_ptrIP7TextBoxLN9__gnu_cxx12_Lock_policyE2EE10_M_disposeEv|
|std::_Sp_counted_ptr<TextBox*, |No|(__gnu_cxx::_Lock_policy)2>::_M_get_deleter|IDK|_ZNSt15_Sp_counted_ptrIP7TextBoxLN9__gnu_cxx12_Lock_policyE2EE14_M_get_deleterERKSt9type_info|
|std::_Sp_counted_ptr<Slider*, |No|(__gnu_cxx::_Lock_policy)2>::_M_dispose|IDK|_ZNSt15_Sp_counted_ptrIP6SliderLN9__gnu_cxx12_Lock_policyE2EE10_M_disposeEv|
|std::_Sp_counted_ptr<Slider*, |No|(__gnu_cxx::_Lock_policy)2>::_M_get_deleter|IDK|_ZNSt15_Sp_counted_ptrIP6SliderLN9__gnu_cxx12_Lock_policyE2EE14_M_get_deleterERKSt9type_info|
|std::_Sp_counted_ptr<OptionsItem*, |No|(__gnu_cxx::_Lock_policy)2>::_M_dispose|IDK|_ZNSt15_Sp_counted_ptrIP11OptionsItemLN9__gnu_cxx12_Lock_policyE2EE10_M_disposeEv|
|std::_Sp_counted_ptr<OptionsItem*, |No|(__gnu_cxx::_Lock_policy)2>::_M_get_deleter|IDK|_ZNSt15_Sp_counted_ptrIP11OptionsItemLN9__gnu_cxx12_Lock_policyE2EE14_M_get_deleterERKSt9type_info|
|std::_Sp_counted_ptr<OptionButton*, |No|(__gnu_cxx::_Lock_policy)2>::_M_dispose|IDK|_ZNSt15_Sp_counted_ptrIP12OptionButtonLN9__gnu_cxx12_Lock_policyE2EE10_M_disposeEv|
|std::_Sp_counted_ptr<OptionButton*, |No|(__gnu_cxx::_Lock_policy)2>::_M_get_deleter|IDK|_ZNSt15_Sp_counted_ptrIP12OptionButtonLN9__gnu_cxx12_Lock_policyE2EE14_M_get_deleterERKSt9type_info|
|std::_Sp_counted_ptr<SmoothZoomLayer*, |No|(__gnu_cxx::_Lock_policy)2>::_M_dispose|IDK|_ZNSt15_Sp_counted_ptrIP15SmoothZoomLayerLN9__gnu_cxx12_Lock_policyE2EE10_M_disposeEv|
|std::_Sp_counted_ptr<SmoothZoomLayer*, |No|(__gnu_cxx::_Lock_policy)2>::_M_get_deleter|IDK|_ZNSt15_Sp_counted_ptrIP15SmoothZoomLayerLN9__gnu_cxx12_Lock_policyE2EE14_M_get_deleterERKSt9type_info|
|std::_Sp_counted_ptr<leveldb::WriteBatch*, |No|(__gnu_cxx::_Lock_policy)2>::_M_get_deleter|IDK|_ZNSt15_Sp_counted_ptrIPN7leveldb10WriteBatchELN9__gnu_cxx12_Lock_policyE2EE14_M_get_deleterERKSt9type_info|
|TempEPtr<Entity>::invalidate|No|()|IDK|_ZN8TempEPtrI6EntityE10invalidateEv|
|Stopwatch::~Stopwatch|No|()|IDK|_ZN9StopwatchD0Ev|
|operator delete|No|(void*)|IDK|_ZdlPv|
|Packet::~Packet|No|()|IDK|_ZN6PacketD0Ev|
|IDataOutput::~IDataOutput|No|()|IDK|_ZN11IDataOutputD0Ev|
|IDataInput::~IDataInput|No|()|IDK|_ZN10IDataInputD0Ev|
|DataItem::~DataItem|No|()|IDK|_ZN8DataItemD0Ev|
|TileSourceListener::~TileSourceListener|No|()|IDK|_ZN18TileSourceListenerD0Ev|
|_TickPtr::~_TickPtr|No|()|IDK|_ZN8_TickPtrD0Ev|
|IMoveInput::~IMoveInput|No|()|IDK|_ZN10IMoveInputD0Ev|
|ITouchScreenModel::~ITouchScreenModel|No|()|IDK|_ZN17ITouchScreenModelD0Ev|
|IArea::~IArea|No|()|IDK|_ZN5IAreaD0Ev|
|TargetGoal::~TargetGoal|No|()|IDK|_ZN10TargetGoalD0Ev|
|MegaTreeFeature::~MegaTreeFeature|No|()|IDK|_ZN15MegaTreeFeatureD0Ev|
|Touch::IInventoryPaneCallback::~IInventoryPaneCallback|No|()|IDK|_ZN5Touch22IInventoryPaneCallbackD0Ev|
|NearestAttackableTargetGoal::~NearestAttackableTargetGoal|No|()|IDK|_ZN27NearestAttackableTargetGoalD0Ev|
|LevelListener::~LevelListener|No|()|IDK|_ZN13LevelListenerD0Ev|
|FlowerFeature::~FlowerFeature|No|()|IDK|_ZN13FlowerFeatureD0Ev|
|std::_Sp_counted_base<|No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_base|IDK|_ZNSt16_Sp_counted_baseILN9__gnu_cxx12_Lock_policyE2EED0Ev|
|std::_Sp_counted_ptr<CategoryButton*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP14CategoryButtonLN9__gnu_cxx12_Lock_policyE2EED0Ev|
|std::_Sp_counted_ptr<CategoryButton*, |No|(__gnu_cxx::_Lock_policy)2>::_M_destroy|IDK|_ZNSt15_Sp_counted_ptrIP14CategoryButtonLN9__gnu_cxx12_Lock_policyE2EE10_M_destroyEv|
|std::_Sp_counted_ptr<Touch::InventoryPane*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIPN5Touch13InventoryPaneELN9__gnu_cxx12_Lock_policyE2EED0Ev|
|std::_Sp_counted_ptr<Touch::InventoryPane*, |No|(__gnu_cxx::_Lock_policy)2>::_M_destroy|IDK|_ZNSt15_Sp_counted_ptrIPN5Touch13InventoryPaneELN9__gnu_cxx12_Lock_policyE2EE10_M_destroyEv|
|std::_Sp_counted_ptr<ImageWithBackground*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP19ImageWithBackgroundLN9__gnu_cxx12_Lock_policyE2EED0Ev|
|std::_Sp_counted_ptr<ImageWithBackground*, |No|(__gnu_cxx::_Lock_policy)2>::_M_destroy|IDK|_ZNSt15_Sp_counted_ptrIP19ImageWithBackgroundLN9__gnu_cxx12_Lock_policyE2EE10_M_destroyEv|
|std::_Sp_counted_ptr<NinePatchLayer*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP14NinePatchLayerLN9__gnu_cxx12_Lock_policyE2EED0Ev|
|std::_Sp_counted_ptr<NinePatchLayer*, |No|(__gnu_cxx::_Lock_policy)2>::_M_destroy|IDK|_ZNSt15_Sp_counted_ptrIP14NinePatchLayerLN9__gnu_cxx12_Lock_policyE2EE10_M_destroyEv|
|std::_Sp_counted_ptr<ZoomLayer*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP9ZoomLayerLN9__gnu_cxx12_Lock_policyE2EED0Ev|
|std::_Sp_counted_ptr<ZoomLayer*, |No|(__gnu_cxx::_Lock_policy)2>::_M_destroy|IDK|_ZNSt15_Sp_counted_ptrIP9ZoomLayerLN9__gnu_cxx12_Lock_policyE2EE10_M_destroyEv|
|std::_Sp_counted_ptr<LoginOption*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP11LoginOptionLN9__gnu_cxx12_Lock_policyE2EED0Ev|
|std::_Sp_counted_ptr<LoginOption*, |No|(__gnu_cxx::_Lock_policy)2>::_M_destroy|IDK|_ZNSt15_Sp_counted_ptrIP11LoginOptionLN9__gnu_cxx12_Lock_policyE2EE10_M_destroyEv|
|std::_Sp_counted_ptr<TextBox*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP7TextBoxLN9__gnu_cxx12_Lock_policyE2EED0Ev|
|std::_Sp_counted_ptr<TextBox*, |No|(__gnu_cxx::_Lock_policy)2>::_M_destroy|IDK|_ZNSt15_Sp_counted_ptrIP7TextBoxLN9__gnu_cxx12_Lock_policyE2EE10_M_destroyEv|
|std::_Sp_counted_ptr<Slider*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP6SliderLN9__gnu_cxx12_Lock_policyE2EED0Ev|
|std::_Sp_counted_ptr<Slider*, |No|(__gnu_cxx::_Lock_policy)2>::_M_destroy|IDK|_ZNSt15_Sp_counted_ptrIP6SliderLN9__gnu_cxx12_Lock_policyE2EE10_M_destroyEv|
|std::_Sp_counted_ptr<OptionsItem*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP11OptionsItemLN9__gnu_cxx12_Lock_policyE2EED0Ev|
|std::_Sp_counted_ptr<OptionsItem*, |No|(__gnu_cxx::_Lock_policy)2>::_M_destroy|IDK|_ZNSt15_Sp_counted_ptrIP11OptionsItemLN9__gnu_cxx12_Lock_policyE2EE10_M_destroyEv|
|std::_Sp_counted_ptr<OptionButton*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP12OptionButtonLN9__gnu_cxx12_Lock_policyE2EED0Ev|
|std::_Sp_counted_ptr<OptionButton*, |No|(__gnu_cxx::_Lock_policy)2>::_M_destroy|IDK|_ZNSt15_Sp_counted_ptrIP12OptionButtonLN9__gnu_cxx12_Lock_policyE2EE10_M_destroyEv|
|std::_Sp_counted_ptr<SmoothZoomLayer*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP15SmoothZoomLayerLN9__gnu_cxx12_Lock_policyE2EED0Ev|
|std::_Sp_counted_ptr<SmoothZoomLayer*, |No|(__gnu_cxx::_Lock_policy)2>::_M_destroy|IDK|_ZNSt15_Sp_counted_ptrIP15SmoothZoomLayerLN9__gnu_cxx12_Lock_policyE2EE10_M_destroyEv|
|std::_Sp_counted_ptr<leveldb::WriteBatch*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIPN7leveldb10WriteBatchELN9__gnu_cxx12_Lock_policyE2EED0Ev|
|std::_Sp_counted_ptr<leveldb::WriteBatch*, |No|(__gnu_cxx::_Lock_policy)2>::_M_destroy|IDK|_ZNSt15_Sp_counted_ptrIPN7leveldb10WriteBatchELN9__gnu_cxx12_Lock_policyE2EE10_M_destroyEv|
|DataItem2<signed char>::~DataItem2|No|()|IDK|_ZN9DataItem2IaED0Ev|
|DataItem2<float>::~DataItem2|No|()|IDK|_ZN9DataItem2IfED0Ev|
|DataItem2<int>::~DataItem2|No|()|IDK|_ZN9DataItem2IiED0Ev|
|FleeSunGoal::~FleeSunGoal|No|()|IDK|_ZN11FleeSunGoalD0Ev|
|UpdateBlockPacket::~UpdateBlockPacket|No|()|IDK|_ZN17UpdateBlockPacketD0Ev|
|TileEventPacket::~TileEventPacket|No|()|IDK|_ZN15TileEventPacketD0Ev|
|StartGamePacket::~StartGamePacket|No|()|IDK|_ZN15StartGamePacketD0Ev|
|SetTimePacket::~SetTimePacket|No|()|IDK|_ZN13SetTimePacketD0Ev|
|SetSpawnPositionPacket::~SetSpawnPositionPacket|No|()|IDK|_ZN22SetSpawnPositionPacketD0Ev|
|RemovePlayerPacket::~RemovePlayerPacket|No|()|IDK|_ZN18RemovePlayerPacketD0Ev|
|RemoveEntityPacket::~RemoveEntityPacket|No|()|IDK|_ZN18RemoveEntityPacketD0Ev|
|PlayerArmorEquipmentPacket::~PlayerArmorEquipmentPacket|No|()|IDK|_ZN26PlayerArmorEquipmentPacketD0Ev|
|LoginStatusPacket::~LoginStatusPacket|No|()|IDK|_ZN17LoginStatusPacketD0Ev|
|LevelEventPacket::~LevelEventPacket|No|()|IDK|_ZN16LevelEventPacketD0Ev|
|AddItemEntityPacket::~AddItemEntityPacket|No|()|IDK|_ZN19AddItemEntityPacketD0Ev|
|AddEntityPacket::~AddEntityPacket|No|()|IDK|_ZN15AddEntityPacketD0Ev|
|SpiderTargetGoal::~SpiderTargetGoal|No|()|IDK|_ZN16SpiderTargetGoalD0Ev|
|SetEntityLinkPacket::~SetEntityLinkPacket|No|()|IDK|_ZN19SetEntityLinkPacketD0Ev|
|SavannaTreeFeature::~SavannaTreeFeature|No|()|IDK|_ZN18SavannaTreeFeatureD0Ev|
|VinesFeature::~VinesFeature|No|()|IDK|_ZN12VinesFeatureD0Ev|
|MelonFeatrue::~MelonFeatrue|No|()|IDK|_ZN12MelonFeatrueD0Ev|
|MegaJungleTreeFeature::~MegaJungleTreeFeature|No|()|IDK|_ZN21MegaJungleTreeFeatureD0Ev|
|JungleTreeFeature::~JungleTreeFeature|No|()|IDK|_ZN17JungleTreeFeatureD0Ev|
|GroundBushFeature::~GroundBushFeature|No|()|IDK|_ZN17GroundBushFeatureD0Ev|
|IcePatchFeature::~IcePatchFeature|No|()|IDK|_ZN15IcePatchFeatureD0Ev|
|IceSpikeFeature::~IceSpikeFeature|No|()|IDK|_ZN15IceSpikeFeatureD0Ev|
|SwampTreeFeature::~SwampTreeFeature|No|()|IDK|_ZN16SwampTreeFeatureD0Ev|
|TallGrassFeature::~TallGrassFeature|No|()|IDK|_ZN16TallGrassFeatureD0Ev|
|MegaPineTreeFeature::~MegaPineTreeFeature|No|()|IDK|_ZN19MegaPineTreeFeatureD0Ev|
|RoofTreeFeature::~RoofTreeFeature|No|()|IDK|_ZN15RoofTreeFeatureD0Ev|
|PineFeature::~PineFeature|No|()|IDK|_ZN11PineFeatureD0Ev|
|SpruceFeature::~SpruceFeature|No|()|IDK|_ZN13SpruceFeatureD0Ev|
|OakFeature::~OakFeature|No|()|IDK|_ZN10OakFeatureD0Ev|
|DesertWellFeature::~DesertWellFeature|No|()|IDK|_ZN17DesertWellFeatureD0Ev|
|DeadBushFeature::~DeadBushFeature|No|()|IDK|_ZN15DeadBushFeatureD0Ev|
|SpringFeature::~SpringFeature|No|()|IDK|_ZN13SpringFeatureD0Ev|
|PumpkinFeature::~PumpkinFeature|No|()|IDK|_ZN14PumpkinFeatureD0Ev|
|WaterlilyFeature::~WaterlilyFeature|No|()|IDK|_ZN16WaterlilyFeatureD0Ev|
|CactusFeature::~CactusFeature|No|()|IDK|_ZN13CactusFeatureD0Ev|
|ReedsFeature::~ReedsFeature|No|()|IDK|_ZN12ReedsFeatureD0Ev|
|HugeMushroomFeature::~HugeMushroomFeature|No|()|IDK|_ZN19HugeMushroomFeatureD0Ev|
|OreFeature::~OreFeature|No|()|IDK|_ZN10OreFeatureD0Ev|
|SandFeature::~SandFeature|No|()|IDK|_ZN11SandFeatureD0Ev|
|ClayFeature::~ClayFeature|No|()|IDK|_ZN11ClayFeatureD0Ev|
|RakDataInput::~RakDataInput|No|()|IDK|_ZN12RakDataInputD0Ev|
|RakDataOutput::~RakDataOutput|No|()|IDK|_ZN13RakDataOutputD0Ev|
|StringByteOutput::~StringByteOutput|No|()|IDK|_ZN16StringByteOutputD0Ev|
|StringByteInput::~StringByteInput|No|()|IDK|_ZN15StringByteInputD0Ev|
|InteractPacket::~InteractPacket|No|()|IDK|_ZN14InteractPacketD0Ev|
|EatTileGoal::~EatTileGoal|No|()|IDK|_ZN11EatTileGoalD0Ev|
|RectangleArea::~RectangleArea|No|()|IDK|_ZN13RectangleAreaD0Ev|
|std::vector<ItemInstance, std::allocator<ItemInstance> >::~vector|No|()|IDK|_ZNSt6vectorI12ItemInstanceSaIS0_EED2Ev|
|std::vector<ItemInstance, std::allocator<ItemInstance> >::~vector|No|()|IDK|_ZNSt6vectorI12ItemInstanceSaIS0_EED1Ev|
|BaseContainerMenu::~BaseContainerMenu|No|()|IDK|_ZN17BaseContainerMenuD2Ev|
|vtable for BaseContainerMenu|No|(undefined|IDK|_ZTV17BaseContainerMenu|
|BaseContainerMenu::~BaseContainerMenu|No|()|IDK|_ZN17BaseContainerMenuD1Ev|
|BaseContainerMenu::~BaseContainerMenu|No|()|IDK|_ZN17BaseContainerMenuD0Ev|
|FurnaceMenu::~FurnaceMenu|No|()|IDK|_ZN11FurnaceMenuD2Ev|
|FurnaceMenu::~FurnaceMenu|No|()|IDK|_ZN11FurnaceMenuD1Ev|
|FurnaceMenu::~FurnaceMenu|No|()|IDK|_ZN11FurnaceMenuD0Ev|
|SetEntityDataPacket::~SetEntityDataPacket|No|()|IDK|_ZN19SetEntityDataPacketD2Ev|
|vtable for SetEntityDataPacket|No|(undefined|IDK|_ZTV19SetEntityDataPacket|
|SetEntityDataPacket::~SetEntityDataPacket|No|()|IDK|_ZN19SetEntityDataPacketD1Ev|
|AddMobPacket::~AddMobPacket|No|()|IDK|_ZN12AddMobPacketD2Ev|
|vtable for AddMobPacket|No|(undefined|IDK|_ZTV12AddMobPacket|
|AddMobPacket::~AddMobPacket|No|()|IDK|_ZN12AddMobPacketD1Ev|
|ContainerSetContentPacket::~ContainerSetContentPacket|No|()|IDK|_ZN25ContainerSetContentPacketD2Ev|
|vtable for ContainerSetContentPacket|No|(undefined|IDK|_ZTV25ContainerSetContentPacket|
|ContainerSetContentPacket::~ContainerSetContentPacket|No|()|IDK|_ZN25ContainerSetContentPacketD1Ev|
|CreativeInventoryScreen::filteredItems|No|(undefined|IDK|_ZN23CreativeInventoryScreen13filteredItemsE|
|SetEntityMotionPacket::~SetEntityMotionPacket|No|()|IDK|_ZN21SetEntityMotionPacketD2Ev|
|vtable for SetEntityMotionPacket|No|(undefined|IDK|_ZTV21SetEntityMotionPacket|
|SetEntityMotionPacket::~SetEntityMotionPacket|No|()|IDK|_ZN21SetEntityMotionPacketD1Ev|
|SetEntityMotionPacket::~SetEntityMotionPacket|No|()|IDK|_ZN21SetEntityMotionPacketD0Ev|
|RotateHeadPacket::~RotateHeadPacket|No|()|IDK|_ZN16RotateHeadPacketD2Ev|
|vtable for RotateHeadPacket|No|(undefined|IDK|_ZTV16RotateHeadPacket|
|RotateHeadPacket::~RotateHeadPacket|No|()|IDK|_ZN16RotateHeadPacketD1Ev|
|RotateHeadPacket::~RotateHeadPacket|No|()|IDK|_ZN16RotateHeadPacketD0Ev|
|MoveEntityPacket::~MoveEntityPacket|No|()|IDK|_ZN16MoveEntityPacketD2Ev|
|vtable for MoveEntityPacket|No|(undefined|IDK|_ZTV16MoveEntityPacket|
|MoveEntityPacket::~MoveEntityPacket|No|()|IDK|_ZN16MoveEntityPacketD1Ev|
|MoveEntityPacket::~MoveEntityPacket|No|()|IDK|_ZN16MoveEntityPacketD0Ev|
|std::_Sp_counted_deleter<std::vector<std::unique_ptr<LevelChunk, std::default_delete<LevelChunk> >, std::allocator<std::unique_ptr<LevelChunk, std::default_delete<LevelChunk> > > >*, std::__shared_ptr<std::vector<std::unique_ptr<LevelChunk, std::default_delete<LevelChunk> >, std::allocator<std::unique_ptr<LevelChunk, std::default_delete<LevelChunk> > > >, |No|(__gnu_cxx::_Lock_policy)2>::_Deleter<std::allocator<std::vector<std::unique_ptr<LevelChunk, std::default_delete<LevelChunk> >, std::allocator<std::unique_ptr<LevelChunk, std::default_delete<LevelChunk> > > > > >, std::allocator<std::vector<std::unique_ptr<LevelChunk, std::default_delete<LevelChunk> >, std::allocator<std::unique_ptr<LevelChunk, std::default_delete<LevelChunk> > > > >, |IDK|_ZNSt19_Sp_counted_deleterIPSt6vectorISt10unique_ptrI10LevelChunkSt14default_deleteIS2_EESaIS5_EENSt12__shared_ptrIS7_LN9__gnu_cxx12_Lock_policyE2EE8_DeleterISaIS7_EEESE_LSB_2EED0Ev|
|std::_Sp_counted_deleter<std::vector<std::unique_ptr<LevelChunk, std::default_delete<LevelChunk> >, std::allocator<std::unique_ptr<LevelChunk, std::default_delete<LevelChunk> > > >*, std::__shared_ptr<std::vector<std::unique_ptr<LevelChunk, std::default_delete<LevelChunk> >, std::allocator<std::unique_ptr<LevelChunk, std::default_delete<LevelChunk> > > >, |No|(__gnu_cxx::_Lock_policy)2>::_Deleter<std::allocator<std::vector<std::unique_ptr<LevelChunk, std::default_delete<LevelChunk> >, std::allocator<std::unique_ptr<LevelChunk, std::default_delete<LevelChunk> > > > > >, std::allocator<std::vector<std::unique_ptr<LevelChunk, std::default_delete<LevelChunk> >, std::allocator<std::unique_ptr<LevelChunk, std::default_delete<LevelChunk> > > > >, |IDK|_ZNSt19_Sp_counted_deleterIPSt6vectorISt10unique_ptrI10LevelChunkSt14default_deleteIS2_EESaIS5_EENSt12__shared_ptrIS7_LN9__gnu_cxx12_Lock_policyE2EE8_DeleterISaIS7_EEESE_LSB_2EE10_M_destroyEv|
|StopwatchNLast::~StopwatchNLast|No|()|IDK|_ZN14StopwatchNLastD2Ev|
|operator delete[]|No|(void*)|IDK|_ZdaPv|
|vtable for StopwatchNLast|No|(undefined|IDK|_ZTV14StopwatchNLast|
|StopwatchNLast::~StopwatchNLast|No|()|IDK|_ZN14StopwatchNLastD1Ev|
|StopwatchNLast::~StopwatchNLast|No|()|IDK|_ZN14StopwatchNLastD0Ev|
|operator new|No|(unsigned int)|IDK|_Znwj|
|StringByteInput::readBytes|No|(void*, int)|IDK|_ZN15StringByteInput9readBytesEPvi|
|ByteTag::equals|No|(Tag const&) const|IDK|_ZNK7ByteTag6equalsERK3Tag|
|Tag::equals|No|(Tag const&) const|IDK|_ZNK3Tag6equalsERKS_|
|IntTag::equals|No|(Tag const&) const|IDK|_ZNK6IntTag6equalsERK3Tag|
|ByteTag::toString|No|() const|IDK|_ZNK7ByteTag8toStringEv|
|Tile::getDescriptionId|No|() const|IDK|_ZNK4Tile16getDescriptionIdEv|
|MonsterEggTile::getTypeDescriptionId|No|(int)|IDK|_ZN14MonsterEggTile20getTypeDescriptionIdEi|
|Villager::getHurtSound|No|()|IDK|_ZN8Villager12getHurtSoundEv|
|Villager::getDeathSound|No|()|IDK|_ZN8Villager13getDeathSoundEv|
|Pig::getHurtSound|No|()|IDK|_ZN3Pig12getHurtSoundEv|
|Pig::getDeathSound|No|()|IDK|_ZN3Pig13getDeathSoundEv|
|Spider::getHurtSound|No|()|IDK|_ZN6Spider12getHurtSoundEv|
|Spider::getDeathSound|No|()|IDK|_ZN6Spider13getDeathSoundEv|
|DirtTile::getTypeDescriptionId|No|(int)|IDK|_ZN8DirtTile20getTypeDescriptionIdEi|
|SandTile::getTypeDescriptionId|No|(int)|IDK|_ZN8SandTile20getTypeDescriptionIdEi|
|Tile::getTypeDescriptionId|No|(int)|IDK|_ZN4Tile20getTypeDescriptionIdEi|
|StringByteOutput::writeBytes|No|(void const*, int)|IDK|_ZN16StringByteOutput10writeBytesEPKvi|
|CompoundTag::write|No|(IDataOutput*)|IDK|_ZN11CompoundTag5writeEP11IDataOutput|
|Tag::writeNamedTag|No|(Tag*, IDataOutput*)|IDK|_ZN3Tag13writeNamedTagEPS_P11IDataOutput|
|CropTile::getTexture|No|(signed char, int)|IDK|_ZN8CropTile10getTextureEai|
|TextureAtlasTextureItem::operator[]|No|(int) const|IDK|_ZNK23TextureAtlasTextureItemixEi|
|LiquidTile::getTextureNum|No|(int)|IDK|_ZN10LiquidTile13getTextureNumEi|
|ClothTile::getTexture|No|(signed char, int)|IDK|_ZN9ClothTile10getTextureEai|
|MultiTextureTile::getTexture|No|(signed char, int)|IDK|_ZN16MultiTextureTile10getTextureEai|
|StemTile::getShape|No|(unsigned char, AABB&, bool)|IDK|_ZN8StemTile8getShapeEhR4AABBb|
|AABB::set|No|(Vec3 const&, Vec3 const&)|IDK|_ZN4AABB3setERK4Vec3S2_|
|CactusTile::getAABB|No|(TileSource*, int, int, int, AABB&, int, bool, int)|IDK|_ZN10CactusTile7getAABBEP10TileSourceiiiR4AABBibi|
|Tile::setShape|No|(float, float, float, float, float, float)|IDK|_ZN4Tile8setShapeEffffff|
|StemTile::onFertilized|No|(TileSource*, int, int, int)|IDK|_ZN8StemTile12onFertilizedEP10TileSourceiii|
|Bush::growCrops|No|(TileSource*, int, int, int)|IDK|_ZN4Bush9growCropsEP10TileSourceiii|
|CropTile::onFertilized|No|(TileSource*, int, int, int)|IDK|_ZN8CropTile12onFertilizedEP10TileSourceiii|
|EatTileGoal::start|No|()|IDK|_ZN11EatTileGoal5startEv|
|Level::broadcastEntityEvent|No|(Entity*, char)|IDK|_ZN5Level20broadcastEntityEventEP6Entityc|
|Mob::getNavigation|No|()|IDK|_ZN3Mob13getNavigationEv|
|FleeSunGoal::canContinueToUse|No|()|IDK|_ZN11FleeSunGoal16canContinueToUseEv|
|FleeSunGoal::start|No|()|IDK|_ZN11FleeSunGoal5startEv|
|ChunkSource::discard|No|(std::unique_ptr<LevelChunk, std::default_delete<LevelChunk> >&)|IDK|_ZN11ChunkSource7discardERSt10unique_ptrI10LevelChunkSt14default_deleteIS1_EE|
|TileSource::~TileSource|No|()|IDK|_ZN10TileSourceD2Ev|
|vtable for TileSource|No|(undefined|IDK|_ZTV10TileSource|
|TileSource::~TileSource|No|()|IDK|_ZN10TileSourceD1Ev|
|TileSource::~TileSource|No|()|IDK|_ZN10TileSourceD0Ev|
|ChunkCache::getView|No|(TilePos const&, TilePos const&, ChunkSource::LoadMode, bool, std::function<void |IDK|_ZN10ChunkCache7getViewERK7TilePosS2_N11ChunkSource8LoadModeEbRKSt8functionIFvRP10LevelChunkEESC_|
|ChunkSource::getView|No|(TilePos const&, TilePos const&, ChunkSource::LoadMode, bool, std::function<void |IDK|_ZN11ChunkSource7getViewERK7TilePosS2_NS_8LoadModeEbRKSt8functionIFvRP10LevelChunkEESB_|
|RakDataOutput::writeBytes|No|(void const*, int)|IDK|_ZN13RakDataOutput10writeBytesEPKvi|
|RakNet::BitStream::WriteBits|No|(unsigned char const*, unsigned int, bool)|IDK|_ZN6RakNet9BitStream9WriteBitsEPKhjb|
|OldLogTile::getTypeDescriptionId|No|(int)|IDK|_ZN10OldLogTile20getTypeDescriptionIdEi|
|guard variable for OldLogTile::getTypeDescriptionId|No|(int)::WOOD_NAMES|IDK|_ZGVZN10OldLogTile20getTypeDescriptionIdEiE10WOOD_NAMES|
|OldLogTile::getTypeDescriptionId|No|(int)::WOOD_NAMES|IDK|_ZZN10OldLogTile20getTypeDescriptionIdEiE10WOOD_NAMES|
|std::array<std::string, 4u>::~array|No|()|IDK|_ZNSt5arrayISsLj4EED1Ev|
|ColoredTile::getTypeDescriptionId|No|(int)|IDK|_ZN11ColoredTile20getTypeDescriptionIdEi|
|guard variable for ColoredTile::getTypeDescriptionId|No|(int)::BLOCK_NAMES|IDK|_ZGVZN11ColoredTile20getTypeDescriptionIdEiE11BLOCK_NAMES|
|ColoredTile::getTypeDescriptionId|No|(int)::BLOCK_NAMES|IDK|_ZZN11ColoredTile20getTypeDescriptionIdEiE11BLOCK_NAMES|
|NewLogTile::getTypeDescriptionId|No|(int)|IDK|_ZN10NewLogTile20getTypeDescriptionIdEi|
|guard variable for NewLogTile::getTypeDescriptionId|No|(int)::WOOD_NAMES|IDK|_ZGVZN10NewLogTile20getTypeDescriptionIdEiE10WOOD_NAMES|
|NewLogTile::getTypeDescriptionId|No|(int)::WOOD_NAMES|IDK|_ZZN10NewLogTile20getTypeDescriptionIdEiE10WOOD_NAMES|
|std::array<std::string, 3u>::~array|No|()|IDK|_ZNSt5arrayISsLj3EED1Ev|
|FlowerTile::getTypeDescriptionId|No|(int)|IDK|_ZN10FlowerTile20getTypeDescriptionIdEi|
|guard variable for FlowerTile::getTypeDescriptionId|No|(int)::FLOWER_NAMES|IDK|_ZGVZN10FlowerTile20getTypeDescriptionIdEiE12FLOWER_NAMES|
|FlowerTile::getTypeDescriptionId|No|(int)::FLOWER_NAMES|IDK|_ZZN10FlowerTile20getTypeDescriptionIdEiE12FLOWER_NAMES|
|MessagePacket::~MessagePacket|No|()|IDK|_ZN13MessagePacketD2Ev|
|RakNet::RakString::~RakString|No|()|IDK|_ZN6RakNet9RakStringD1Ev|
|vtable for MessagePacket|No|(undefined|IDK|_ZTV13MessagePacket|
|MessagePacket::~MessagePacket|No|()|IDK|_ZN13MessagePacketD1Ev|
|MessagePacket::~MessagePacket|No|()|IDK|_ZN13MessagePacketD0Ev|
|AddPlayerPacket::~AddPlayerPacket|No|()|IDK|_ZN15AddPlayerPacketD2Ev|
|vtable for AddPlayerPacket|No|(undefined|IDK|_ZTV15AddPlayerPacket|
|AddPlayerPacket::~AddPlayerPacket|No|()|IDK|_ZN15AddPlayerPacketD1Ev|
|GuiElement::~GuiElement|No|()|IDK|_ZN10GuiElementD2Ev|
|GuiComponent::~GuiComponent|No|()|IDK|_ZN12GuiComponentD2Ev|
|vtable for GuiElement|No|(undefined|IDK|_ZTV10GuiElement|
|GuiElement::~GuiElement|No|()|IDK|_ZN10GuiElementD1Ev|
|GuiElement::~GuiElement|No|()|IDK|_ZN10GuiElementD0Ev|
|ServerSideNetworkHandler::onPlayerVerifiedFailed|No|(RestCallTagData const&)|IDK|_ZN24ServerSideNetworkHandler22onPlayerVerifiedFailedERK15RestCallTagData|
|Packet::Packet|No|()|IDK|_ZN6PacketC2Ev|
|vtable for LoginStatusPacket|No|(undefined|IDK|_ZTV17LoginStatusPacket|
|ServerSideNetworkHandler::onTileEvent|No|(TileSource*, int, int, int, int, int)|IDK|_ZN24ServerSideNetworkHandler11onTileEventEP10TileSourceiiiii|
|vtable for TileEventPacket|No|(undefined|IDK|_ZTV15TileEventPacket|
|non-virtual thunk to ServerSideNetworkHandler::onTileEvent|No|(TileSource*, int, int, int, int, int)|IDK|_ZThn4_N24ServerSideNetworkHandler11onTileEventEP10TileSourceiiiii|
|Minecart::canInteractWith|No|(Player*)|IDK|_ZN8Minecart15canInteractWithEP6Player|
|Entity::isRiding|No|()|IDK|_ZN6Entity8isRidingEv|
|leveldb::WriteBatch::WriteBatch|No|()|IDK|_ZN7leveldb10WriteBatchC1Ev|
|std::_Sp_counted_ptr<leveldb::WriteBatch*, |No|(__gnu_cxx::_Lock_policy)2>::_M_dispose|IDK|_ZNSt15_Sp_counted_ptrIPN7leveldb10WriteBatchELN9__gnu_cxx12_Lock_policyE2EE10_M_disposeEv|
|leveldb::WriteBatch::~WriteBatch|No|()|IDK|_ZN7leveldb10WriteBatchD1Ev|
(null)
|DBChunkStorage::compact|No|()|IDK|_ZN14DBChunkStorage7compactEv|
|BackgroundQueuePool::getFor|No|(QueueRole)|IDK|_ZN19BackgroundQueuePool6getForE9QueueRole|
|BackgroundQueue::queue|No|(std::function<bool |IDK|_ZN15BackgroundQueue5queueERKSt8functionIFbvEERKS0_IFvvEEi|
|BackgroundQueue::NOP|No|(undefined|IDK|_ZN15BackgroundQueue3NOPE|
|DBStorage::_write|No|(leveldb::WriteBatch&) const|IDK|_ZNK9DBStorage6_writeERN7leveldb10WriteBatchE|
|ChunkSource::compact|No|()|IDK|_ZN11ChunkSource7compactEv|
|DBChunkStorage::getStats|No|() const|IDK|_ZNK14DBChunkStorage8getStatsEv|
|leveldb::WriteBatch::Capacity|No|() const|IDK|_ZNK7leveldb10WriteBatch8CapacityEv|
|non-virtual thunk to DBChunkStorage::getStats|No|() const|IDK|_ZThn24_NK14DBChunkStorage8getStatsEv|
|WolfModel::~WolfModel|No|()|IDK|_ZN9WolfModelD2Ev|
|ModelPart::~ModelPart|No|()|IDK|_ZN9ModelPartD1Ev|
|Model::~Model|No|()|IDK|_ZN5ModelD2Ev|
|vtable for WolfModel|No|(undefined|IDK|_ZTV9WolfModel|
|WolfModel::~WolfModel|No|()|IDK|_ZN9WolfModelD1Ev|
|Spider::findAttackTarget|No|()|IDK|_ZN6Spider16findAttackTargetEv|
|Level::getNearestPlayer|No|(Entity*, float)|IDK|_ZN5Level16getNearestPlayerEP6Entityf|
|PathfinderMob::getAttackTarget|No|()|IDK|_ZN13PathfinderMob15getAttackTargetEv|
|Level::getEntity|No|(int, bool)|IDK|_ZN5Level9getEntityEib|
|ServerSideNetworkHandler::handle|No|(RakNet::RakNetGUID const&, EntityEventPacket*)|IDK|_ZN24ServerSideNetworkHandler6handleERKN6RakNet10RakNetGUIDEP17EntityEventPacket|
|WolfModel::render|No|(Entity*, float, float, float, float, float, float)|IDK|_ZN9WolfModel6renderEP6Entityffffff|
|ModelPart::render|No|(float)|IDK|_ZN9ModelPart6renderEf|
|WolfModel::prepareMobModel|No|(Mob*, float, float, float)|IDK|_ZN9WolfModel15prepareMobModelEP3Mobfff|
|Wolf::isAngry|No|() const|IDK|_ZNK4Wolf7isAngryEv|
|ModelPart::setPos|No|(float, float, float)|IDK|_ZN9ModelPart6setPosEfff|
|Wolf::getHeadRollAngle|No|(float)|IDK|_ZN4Wolf16getHeadRollAngleEf|
|Wolf::getBodyRollAngle|No|(float, float)|IDK|_ZN4Wolf16getBodyRollAngleEff|
|Mth::_sinScale|No|(undefined|IDK|_ZN3Mth9_sinScaleE|
|Mth::_sin|No|(undefined|IDK|_ZN3Mth4_sinE|
|ItemRenderer::~ItemRenderer|No|()|IDK|_ZN12ItemRendererD2Ev|
|EntityRenderer::~EntityRenderer|No|()|IDK|_ZN14EntityRendererD2Ev|
|vtable for ItemRenderer|No|(undefined|IDK|_ZTV12ItemRenderer|
|ItemRenderer::~ItemRenderer|No|()|IDK|_ZN12ItemRendererD1Ev|
|ItemRenderer::~ItemRenderer|No|()|IDK|_ZN12ItemRendererD0Ev|
|CritParticle2::init|No|(float, float, float, float, float, float, int)|IDK|_ZN13CritParticle24initEffffffi|
|Mth::random|No|()|IDK|_ZN3Mth6randomEv|
|RedDustParticle::init|No|(float, float, float, float, float, float, int)|IDK|_ZN15RedDustParticle4initEffffffi|
|SmokeParticle::init|No|(float, float, float, float, float, float, int)|IDK|_ZN13SmokeParticle4initEffffffi|
|ItemRenderer::render|No|(Entity*, float, float, float, float, float)|IDK|_ZN12ItemRenderer6renderEP6Entityfffff|
|EntityRenderer::isFancy|No|()|IDK|_ZN14EntityRenderer7isFancyEv|
|Entity::setupLighting|No|(bool, float)|IDK|_ZN6Entity13setupLightingEbf|
|TileRenderer::canRender|No|(int)|IDK|_ZN12TileRenderer9canRenderEi|
|EntityRenderer::bindTexture|No|(std::string const&)|IDK|_ZN14EntityRenderer11bindTextureERKSs|
|ItemInHandRenderer::renderItem|No|(Mob*, ItemInstance*)|IDK|_ZN18ItemInHandRenderer10renderItemEP3MobP12ItemInstance|
|ItemInstance::getIcon|No|(int, bool) const|IDK|_ZNK12ItemInstance7getIconEib|
|Tesselator::begin|No|(int)|IDK|_ZN10Tesselator5beginEi|
|Tesselator::normal|No|(Vec3 const&)|IDK|_ZN10Tesselator6normalERK4Vec3|
|Tesselator::setOffset|No|(Vec3 const&)|IDK|_ZN10Tesselator9setOffsetERK4Vec3|
|Tesselator::vertexUV|No|(float, float, float, float, float)|IDK|_ZN10Tesselator8vertexUVEfffff|
|Tesselator::draw|No|(bool)|IDK|_ZN10Tesselator4drawEb|
|Mth::RADDEG|No|(undefined|IDK|_ZN3Mth6RADDEGE|
|ItemRenderer::rndFloats|No|(undefined|IDK|_ZN12ItemRenderer9rndFloatsE|
|EntityRenderer::entityRenderDispatcher|No|(undefined|IDK|_ZN14EntityRenderer22entityRenderDispatcherE|
|Tesselator::instance|No|(undefined|IDK|_ZN10Tesselator8instanceE|
(null)
|Vec3::ZERO|No|(undefined|IDK|_ZN4Vec34ZEROE|
|Pig::isFood|No|(ItemInstance const*) const|IDK|_ZNK3Pig6isFoodEPK12ItemInstance|
|ItemInstance::getId|No|() const|IDK|_ZNK12ItemInstance5getIdEv|
|Item::potato|No|(undefined|IDK|_ZN4Item6potatoE|
|Item::carrot|No|(undefined|IDK|_ZN4Item6carrotE|
|Item::beetroot|No|(undefined|IDK|_ZN4Item8beetrootE|
|MonsterEggTile::destroy|No|(TileSource*, int, int, int, int)|IDK|_ZN14MonsterEggTile7destroyEP10TileSourceiiii|
|Silverfish::Silverfish|No|(TileSource*)|IDK|_ZN10SilverfishC1EP10TileSource|
|MonsterEggTile::spawnResources|No|(TileSource*, int, int, int, int, float)|IDK|_ZN14MonsterEggTile14spawnResourcesEP10TileSourceiiiif|
|SmoothZoomLayer::fillArea|No|(LayerData&, int, int, int, int)|IDK|_ZN15SmoothZoomLayer8fillAreaER9LayerDataiiii|
|Layer::initRandom|No|(long long, long long)|IDK|_ZN5Layer10initRandomExx|
|Layer::nextRandom|No|(int)|IDK|_ZN5Layer10nextRandomEi|
|RiverInitLayer::fillArea|No|(LayerData&, int, int, int, int)|IDK|_ZN14RiverInitLayer8fillAreaER9LayerDataiiii|
|SmoothLayer::fillArea|No|(LayerData&, int, int, int, int)|IDK|_ZN11SmoothLayer8fillAreaER9LayerDataiiii|
|StoneTile::getTexture|No|(signed char, int)|IDK|_ZN9StoneTile10getTextureEai|
|TextureAtlasTextureItem::uvCount|No|() const|IDK|_ZNK23TextureAtlasTextureItem7uvCountEv|
|FlowerTile::getTexture|No|(signed char, int)|IDK|_ZN10FlowerTile10getTextureEai|
|ColoredTile::getTexture|No|(signed char, int)|IDK|_ZN11ColoredTile10getTextureEai|
|StoneTile::getTypeDescriptionId|No|(int)|IDK|_ZN9StoneTile20getTypeDescriptionIdEi|
|guard variable for StoneTile::getTypeDescriptionId|No|(int)::BLOCK_NAMES|IDK|_ZGVZN9StoneTile20getTypeDescriptionIdEiE11BLOCK_NAMES|
|StoneTile::getTypeDescriptionId|No|(int)::BLOCK_NAMES|IDK|_ZZN9StoneTile20getTypeDescriptionIdEiE11BLOCK_NAMES|
|CreativeInventoryScreen::mouseReleased|No|(int, int, int)|IDK|_ZN23CreativeInventoryScreen13mouseReleasedEiii|
|Screen::mouseReleased|No|(int, int, int)|IDK|_ZN6Screen13mouseReleasedEiii|
|Touch::IngameBlockSelectionScreen::removed|No|()|IDK|_ZN5Touch26IngameBlockSelectionScreen7removedEv|
|Gui::inventoryUpdated|No|()|IDK|_ZN3Gui16inventoryUpdatedEv|
|CreativeInventoryScreen::mouseClicked|No|(int, int, int)|IDK|_ZN23CreativeInventoryScreen12mouseClickedEiii|
|Screen::mouseClicked|No|(int, int, int)|IDK|_ZN6Screen12mouseClickedEiii|
|Mouse::getX|No|()|IDK|_ZN5Mouse4getXEv|
|Mouse::getY|No|()|IDK|_ZN5Mouse4getYEv|
|Gui::handleClick|No|(int, int, int)|IDK|_ZN3Gui11handleClickEiii|
|Touch::IngameBlockSelectionScreen::tick|No|()|IDK|_ZN5Touch26IngameBlockSelectionScreen4tickEv|
|Touch::InventoryPane::tick|No|()|IDK|_ZN5Touch13InventoryPane4tickEv|
|Screen::tick|No|()|IDK|_ZN6Screen4tickEv|
|CreativeInventoryScreen::tick|No|()|IDK|_ZN23CreativeInventoryScreen4tickEv|
|Touch::IngameBlockSelectionScreen::buttonClicked|No|(Button*)|IDK|_ZN5Touch26IngameBlockSelectionScreen13buttonClickedEP6Button|
|Minecraft::setScreen|No|(Screen*)|IDK|_ZN9Minecraft9setScreenEP6Screen|
|ScreenChooser::setScreen|No|(ScreenId)|IDK|_ZN13ScreenChooser9setScreenE8ScreenId|
|SurvivalInventoryScreen::SurvivalInventoryScreen|No|(SurvivalInventoryScreen::CraftingType)|IDK|_ZN23SurvivalInventoryScreenC1ENS_12CraftingTypeE|
|ArmorScreen::ArmorScreen|No|()|IDK|_ZN11ArmorScreenC1Ev|
|Minecart::remove|No|()|IDK|_ZN8Minecart6removeEv|
|Entity::remove|No|()|IDK|_ZN6Entity6removeEv|
|Minecart::push|No|(float, float, float)|IDK|_ZN8Minecart4pushEfff|
|Entity::push|No|(float, float, float)|IDK|_ZN6Entity4pushEfff|
|Villager::interactWithPlayer|No|(Player*)|IDK|_ZN8Villager18interactWithPlayerEP6Player|
|Entity::interactWithPlayer|No|(Player*)|IDK|_ZN6Entity18interactWithPlayerEP6Player|
|Villager::newServerAiStep|No|()|IDK|_ZN8Villager15newServerAiStepEv|
|Mob::newServerAiStep|No|()|IDK|_ZN3Mob15newServerAiStepEv|
|FurnaceMenu::setData|No|(int, int)|IDK|_ZN11FurnaceMenu7setDataEii|
|TileEntity::setChanged|No|()|IDK|_ZN10TileEntity10setChangedEv|
|SuspendedTownParticle::~SuspendedTownParticle|No|()|IDK|_ZN21SuspendedTownParticleD2Ev|
|Entity::~Entity|No|()|IDK|_ZN6EntityD2Ev|
|vtable for Particle|No|(undefined|IDK|_ZTV8Particle|
|SuspendedTownParticle::~SuspendedTownParticle|No|()|IDK|_ZN21SuspendedTownParticleD1Ev|
|SuspendedTownParticle::~SuspendedTownParticle|No|()|IDK|_ZN21SuspendedTownParticleD0Ev|
|MobFlameParticle::~MobFlameParticle|No|()|IDK|_ZN16MobFlameParticleD2Ev|
|MobFlameParticle::~MobFlameParticle|No|()|IDK|_ZN16MobFlameParticleD1Ev|
|MobFlameParticle::~MobFlameParticle|No|()|IDK|_ZN16MobFlameParticleD0Ev|
|BreakingItemParticle::~BreakingItemParticle|No|()|IDK|_ZN20BreakingItemParticleD2Ev|
|BreakingItemParticle::~BreakingItemParticle|No|()|IDK|_ZN20BreakingItemParticleD1Ev|
|BreakingItemParticle::~BreakingItemParticle|No|()|IDK|_ZN20BreakingItemParticleD0Ev|
|SmokeParticle::~SmokeParticle|No|()|IDK|_ZN13SmokeParticleD2Ev|
|SmokeParticle::~SmokeParticle|No|()|IDK|_ZN13SmokeParticleD1Ev|
|SmokeParticle::~SmokeParticle|No|()|IDK|_ZN13SmokeParticleD0Ev|
|RedDustParticle::~RedDustParticle|No|()|IDK|_ZN15RedDustParticleD2Ev|
|RedDustParticle::~RedDustParticle|No|()|IDK|_ZN15RedDustParticleD1Ev|
|RedDustParticle::~RedDustParticle|No|()|IDK|_ZN15RedDustParticleD0Ev|
|LavaParticle::~LavaParticle|No|()|IDK|_ZN12LavaParticleD2Ev|
|LavaParticle::~LavaParticle|No|()|IDK|_ZN12LavaParticleD1Ev|
|LavaParticle::~LavaParticle|No|()|IDK|_ZN12LavaParticleD0Ev|
|FlameParticle::~FlameParticle|No|()|IDK|_ZN13FlameParticleD2Ev|
|FlameParticle::~FlameParticle|No|()|IDK|_ZN13FlameParticleD1Ev|
|FlameParticle::~FlameParticle|No|()|IDK|_ZN13FlameParticleD0Ev|
|ExplodeParticle::~ExplodeParticle|No|()|IDK|_ZN15ExplodeParticleD2Ev|
|ExplodeParticle::~ExplodeParticle|No|()|IDK|_ZN15ExplodeParticleD1Ev|
|ExplodeParticle::~ExplodeParticle|No|()|IDK|_ZN15ExplodeParticleD0Ev|
|CritParticle2::~CritParticle2|No|()|IDK|_ZN13CritParticle2D2Ev|
|CritParticle2::~CritParticle2|No|()|IDK|_ZN13CritParticle2D1Ev|
|CritParticle2::~CritParticle2|No|()|IDK|_ZN13CritParticle2D0Ev|
|BubbleParticle::~BubbleParticle|No|()|IDK|_ZN14BubbleParticleD2Ev|
|BubbleParticle::~BubbleParticle|No|()|IDK|_ZN14BubbleParticleD1Ev|
|BubbleParticle::~BubbleParticle|No|()|IDK|_ZN14BubbleParticleD0Ev|
|TerrainParticle::~TerrainParticle|No|()|IDK|_ZN15TerrainParticleD2Ev|
|TerrainParticle::~TerrainParticle|No|()|IDK|_ZN15TerrainParticleD1Ev|
|TerrainParticle::~TerrainParticle|No|()|IDK|_ZN15TerrainParticleD0Ev|
|FallingTile::~FallingTile|No|()|IDK|_ZN11FallingTileD2Ev|
|vtable for FallingTile|No|(undefined|IDK|_ZTV11FallingTile|
|FallingTile::~FallingTile|No|()|IDK|_ZN11FallingTileD1Ev|
|FallingTile::~FallingTile|No|()|IDK|_ZN11FallingTileD0Ev|
|HangingEntity::~HangingEntity|No|()|IDK|_ZN13HangingEntityD2Ev|
|vtable for HangingEntity|No|(undefined|IDK|_ZTV13HangingEntity|
|HangingEntity::~HangingEntity|No|()|IDK|_ZN13HangingEntityD1Ev|
|HangingEntity::~HangingEntity|No|()|IDK|_ZN13HangingEntityD0Ev|
|FlameParticle::render|No|(Tesselator&, float, float, float, float, float, float)|IDK|_ZN13FlameParticle6renderER10Tesselatorffffff|
|Particle::render|No|(Tesselator&, float, float, float, float, float, float)|IDK|_ZN8Particle6renderER10Tesselatorffffff|
|LavaParticle::render|No|(Tesselator&, float, float, float, float, float, float)|IDK|_ZN12LavaParticle6renderER10Tesselatorffffff|
|RedDustParticle::render|No|(Tesselator&, float, float, float, float, float, float)|IDK|_ZN15RedDustParticle6renderER10Tesselatorffffff|
|TerrainParticle::render|No|(Tesselator&, float, float, float, float, float, float)|IDK|_ZN15TerrainParticle6renderER10Tesselatorffffff|
|Tesselator::color|No|(float, float, float)|IDK|_ZN10Tesselator5colorEfff|
|Particle::yOff|No|(undefined|IDK|_ZN8Particle4yOffE|
|Particle::xOff|No|(undefined|IDK|_ZN8Particle4xOffE|
|Particle::zOff|No|(undefined|IDK|_ZN8Particle4zOffE|
|MobFlameParticle::render|No|(Tesselator&, float, float, float, float, float, float)|IDK|_ZN16MobFlameParticle6renderER10Tesselatorffffff|
|GuiElement::render|No|(Minecraft*, int, int)|IDK|_ZN10GuiElement6renderEP9Minecraftii|
|NinePatchLayer::setSize|No|(float, float)|IDK|_ZN14NinePatchLayer7setSizeEff|
|NinePatchLayer::draw|No|(Tesselator&, float, float)|IDK|_ZN14NinePatchLayer4drawER10Tesselatorff|
|GuiComponent::fill|No|(int, int, int, int, int)|IDK|_ZN12GuiComponent4fillEiiiii|
|CategoryButton::renderBg|No|(Minecraft*, int, int)|IDK|_ZN14CategoryButton8renderBgEP9Minecraftii|
|GuiElement::drawSelected|No|()|IDK|_ZN10GuiElement12drawSelectedEv|
|GuiComponent::drawRect|No|(int, int, int, int, int, int)|IDK|_ZN12GuiComponent8drawRectEiiiiii|
|GuiElement::drawSliderSelected|No|()|IDK|_ZN10GuiElement18drawSliderSelectedEv|
|Pig::interactWithPlayer|No|(Player*)|IDK|_ZN3Pig18interactWithPlayerEP6Player|
|Animal::interactWithPlayer|No|(Player*)|IDK|_ZN6Animal18interactWithPlayerEP6Player|
|Tile::getAABB|No|(TileSource*, int, int, int, AABB&, int, bool, int)|IDK|_ZN4Tile7getAABBEP10TileSourceiiiR4AABBibi|
|AABB::move|No|(float, float, float)|IDK|_ZN4AABB4moveEfff|
|ZoomLayer::fillArea|No|(LayerData&, int, int, int, int)|IDK|_ZN9ZoomLayer8fillAreaER9LayerDataiiii|
|Layer::random|No|(int*, int)|IDK|_ZN5Layer6randomEPii|
|Spider::aiStep|No|()|IDK|_ZN6Spider6aiStepEv|
|Monster::aiStep|No|()|IDK|_ZN7Monster6aiStepEv|
|MessagePacket::write|No|(RakNet::BitStream*)|IDK|_ZN13MessagePacket5writeEPN6RakNet9BitStreamE|
|RakNet::RakString::Serialize|No|(RakNet::BitStream*) const|IDK|_ZNK6RakNet9RakString9SerializeEPNS_9BitStreamE|
|MessagePacket::read|No|(RakNet::BitStream*)|IDK|_ZN13MessagePacket4readEPN6RakNet9BitStreamE|
|RakNet::RakString::Deserialize|No|(RakNet::BitStream*)|IDK|_ZN6RakNet9RakString11DeserializeEPNS_9BitStreamE|
|ChatPacket::write|No|(RakNet::BitStream*)|IDK|_ZN10ChatPacket5writeEPN6RakNet9BitStreamE|
|RakNet::RakString::Serialize|No|(char const*, RakNet::BitStream*)|IDK|_ZN6RakNet9RakString9SerializeEPKcPNS_9BitStreamE|
|ServerSideNetworkHandler::onNewClient|No|(RakNet::RakNetGUID const&)|IDK|_ZN24ServerSideNetworkHandler11onNewClientERKN6RakNet10RakNetGUIDE|
|RakNet::RakNetGUID::ToString|No|() const|IDK|_ZNK6RakNet10RakNetGUID8ToStringEv|
|ServerSideNetworkHandler::handle|No|(RakNet::RakNetGUID const&, ContainerSetContentPacket*)|IDK|_ZN24ServerSideNetworkHandler6handleERKN6RakNet10RakNetGUIDEP25ContainerSetContentPacket|
|NetEventCallback::findPlayer|No|(Level*, RakNet::RakNetGUID const*)|IDK|_ZN16NetEventCallback10findPlayerEP5LevelPKN6RakNet10RakNetGUIDE|
|FillingContainer::getLinkedSlotsCount|No|()|IDK|_ZN16FillingContainer19getLinkedSlotsCountEv|
|ServerSideNetworkHandler::handle|No|(RakNet::RakNetGUID const&, ContainerClosePacket*)|IDK|_ZN24ServerSideNetworkHandler6handleERKN6RakNet10RakNetGUIDEP20ContainerClosePacket|
|ServerPlayer::doCloseContainer|No|()|IDK|_ZN12ServerPlayer16doCloseContainerEv|
|ServerSideNetworkHandler::handle|No|(RakNet::RakNetGUID const&, ContainerSetSlotPacket*)|IDK|_ZN24ServerSideNetworkHandler6handleERKN6RakNet10RakNetGUIDEP22ContainerSetSlotPacket|
|ItemInstance::isItem|No|(ItemInstance const*)|IDK|_ZN12ItemInstance6isItemEPKS_|
|ItemInstance::setNull|No|()|IDK|_ZN12ItemInstance7setNullEv|
|Player::setArmor|No|(int, ItemInstance const*)|IDK|_ZN6Player8setArmorEiPK12ItemInstance|
|CakeTile::getShape|No|(unsigned char, AABB&, bool)|IDK|_ZN8CakeTile8getShapeEhR4AABBb|
|AABB::set|No|(float, float, float, float, float, float)|IDK|_ZN4AABB3setEffffff|
|InvisibleTile::clip|No|(TileSource*, int, int, int, Vec3 const&, Vec3 const&, bool, int)|IDK|_ZN13InvisibleTile4clipEP10TileSourceiiiRK4Vec3S4_bi|
|HitResult::HitResult|No|()|IDK|_ZN9HitResultC1Ev|
|StoneBeachBiome::~StoneBeachBiome|No|()|IDK|_ZN15StoneBeachBiomeD2Ev|
|Biome::~Biome|No|()|IDK|_ZN5BiomeD2Ev|
|vtable for StoneBeachBiome|No|(undefined|IDK|_ZTV15StoneBeachBiome|
|StoneBeachBiome::~StoneBeachBiome|No|()|IDK|_ZN15StoneBeachBiomeD1Ev|
|StoneBeachBiome::~StoneBeachBiome|No|()|IDK|_ZN15StoneBeachBiomeD0Ev|
|PlainsBiome::~PlainsBiome|No|()|IDK|_ZN11PlainsBiomeD2Ev|
|vtable for PlainsBiome|No|(undefined|IDK|_ZTV11PlainsBiome|
|PlainsBiome::~PlainsBiome|No|()|IDK|_ZN11PlainsBiomeD1Ev|
|PlainsBiome::~PlainsBiome|No|()|IDK|_ZN11PlainsBiomeD0Ev|
|SpiderAttackGoal::~SpiderAttackGoal|No|()|IDK|_ZN16SpiderAttackGoalD2Ev|
|MeleeAttackGoal::~MeleeAttackGoal|No|()|IDK|_ZN15MeleeAttackGoalD2Ev|
|vtable for SpiderAttackGoal|No|(undefined|IDK|_ZTV16SpiderAttackGoal|
|SpiderAttackGoal::~SpiderAttackGoal|No|()|IDK|_ZN16SpiderAttackGoalD1Ev|
|SpiderAttackGoal::~SpiderAttackGoal|No|()|IDK|_ZN16SpiderAttackGoalD0Ev|
|QuartzBlockTile::getTexture|No|(signed char, int)|IDK|_ZN15QuartzBlockTile10getTextureEai|
|SandStoneTile::getTexture|No|(signed char, int)|IDK|_ZN13SandStoneTile10getTextureEai|
|RakDataInput::readBytes|No|(void*, int)|IDK|_ZN12RakDataInput9readBytesEPvi|
|IDataInput::hasBytesLeft|No|(int) const|IDK|_ZNK10IDataInput12hasBytesLeftEi|
|RakNet::BitStream::ReadBits|No|(unsigned char*, unsigned int, bool)|IDK|_ZN6RakNet9BitStream8ReadBitsEPhjb|
|Touch::IngameBlockSelectionScreen::mouseClicked|No|(int, int, int)|IDK|_ZN5Touch26IngameBlockSelectionScreen12mouseClickedEiii|
|Touch::IngameBlockSelectionScreen::mouseReleased|No|(int, int, int)|IDK|_ZN5Touch26IngameBlockSelectionScreen13mouseReleasedEiii|
|CritParticle2::render|No|(Tesselator&, float, float, float, float, float, float)|IDK|_ZN13CritParticle26renderER10Tesselatorffffff|
|LiquidTile::getAABB|No|(TileSource*, int, int, int, AABB&, int, bool, int)|IDK|_ZN10LiquidTile7getAABBEP10TileSourceiiiR4AABBibi|
|AABB::EMPTY|No|(undefined|IDK|_ZN4AABB5EMPTYE|
|Vec3::ONE|No|(undefined|IDK|_ZN4Vec33ONEE|
|ReedTile::getAABB|No|(TileSource*, int, int, int, AABB&, int, bool, int)|IDK|_ZN8ReedTile7getAABBEP10TileSourceiiiR4AABBibi|
|WebTile::getAABB|No|(TileSource*, int, int, int, AABB&, int, bool, int)|IDK|_ZN7WebTile7getAABBEP10TileSourceiiiR4AABBibi|
|Tile::getDestroyProgress|No|(Player*)|IDK|_ZN4Tile18getDestroyProgressEP6Player|
|Player::canDestroy|No|(Tile*)|IDK|_ZN6Player10canDestroyEP4Tile|
|Player::getDestroySpeed|No|(Tile*)|IDK|_ZN6Player15getDestroySpeedEP4Tile|
|ServerSideNetworkHandler::onNewChunkFor|No|(Player&, LevelChunk&)|IDK|_ZN24ServerSideNetworkHandler13onNewChunkForER6PlayerR10LevelChunk|
|BackgroundQueuePool::getMain|No|()|IDK|_ZN19BackgroundQueuePool7getMainEv|
|non-virtual thunk to ServerSideNetworkHandler::onNewChunkFor|No|(Player&, LevelChunk&)|IDK|_ZThn4_N24ServerSideNetworkHandler13onNewChunkForER6PlayerR10LevelChunk|
|TopSnowTile::getAABB|No|(TileSource*, int, int, int, AABB&, int, bool, int)|IDK|_ZN11TopSnowTile7getAABBEP10TileSourceiiiR4AABBibi|
|BreakingItemParticle::render|No|(Tesselator&, float, float, float, float, float, float)|IDK|_ZN20BreakingItemParticle6renderER10Tesselatorffffff|
|Pig::canBeControlledByRider|No|()|IDK|_ZN3Pig22canBeControlledByRiderEv|
|HangingEntity::normalTick|No|()|IDK|_ZN13HangingEntity10normalTickEv|
|HangingEntity::interactWithPlayer|No|(Player*)|IDK|_ZN13HangingEntity18interactWithPlayerEP6Player|
|Inventory::getSelected|No|()|IDK|_ZN9Inventory11getSelectedEv|
|Item::bow|No|(undefined|IDK|_ZN4Item3bowE|
|HangingEntity::move|No|(float, float, float)|IDK|_ZN13HangingEntity4moveEfff|
|HangingEntity::push|No|(float, float, float)|IDK|_ZN13HangingEntity4pushEfff|
|HangingEntity::hurt|No|(Entity*, int)|IDK|_ZN13HangingEntity4hurtEP6Entityi|
|MobFlameParticle::normalTick|No|()|IDK|_ZN16MobFlameParticle10normalTickEv|
|WorldLimitChunkSource::requestChunk|No|(ChunkPos const&, ChunkSource::LoadMode)|IDK|_ZN21WorldLimitChunkSource12requestChunkERK8ChunkPosN11ChunkSource8LoadModeE|
|CreativeInventoryScreen::keyPressed|No|(int)|IDK|_ZN23CreativeInventoryScreen10keyPressedEi|
|Screen::keyPressed|No|(int)|IDK|_ZN6Screen10keyPressedEi|
|Touch::InventoryPane::onSelectItem|No|()|IDK|_ZN5Touch13InventoryPane12onSelectItemEv|
|CreativeInventoryScreen::controllerDirectionChanged|No|(int, Controller::StickDirection)|IDK|_ZN23CreativeInventoryScreen26controllerDirectionChangedEiN10Controller14StickDirectionE|
|Touch::InventoryPane::setControllerDirection|No|(Controller::StickDirection)|IDK|_ZN5Touch13InventoryPane22setControllerDirectionEN10Controller14StickDirectionE|
|CreativeInventoryScreen::controllerDirectionHeld|No|(int, Controller::StickDirection)|IDK|_ZN23CreativeInventoryScreen23controllerDirectionHeldEiN10Controller14StickDirectionE|
|ListTag::equals|No|(Tag const&) const|IDK|_ZNK7ListTag6equalsERK3Tag|
|BaseContainerMenu::setListener|No|(IContainerListener*)|IDK|_ZN17BaseContainerMenu11setListenerEP18IContainerListener|
|FurnaceMenu::setListener|No|(IContainerListener*)|IDK|_ZN11FurnaceMenu11setListenerEP18IContainerListener|
|MainChunkSource::~MainChunkSource|No|()|IDK|_ZN15MainChunkSourceD2Ev|
|ChunkRefCount::~ChunkRefCount|No|()|IDK|_ZN13ChunkRefCountD1Ev|
|AppPlatformListener::~AppPlatformListener|No|()|IDK|_ZN19AppPlatformListenerD2Ev|
|ChunkSource::~ChunkSource|No|()|IDK|_ZN11ChunkSourceD2Ev|
|vtable for MainChunkSource|No|(undefined|IDK|_ZTV15MainChunkSource|
|MainChunkSource::~MainChunkSource|No|()|IDK|_ZN15MainChunkSourceD1Ev|
|non-virtual thunk to MainChunkSource::~MainChunkSource|No|()|IDK|_ZThn20_N15MainChunkSourceD1Ev|
|MainChunkSource::~MainChunkSource|No|()|IDK|_ZN15MainChunkSourceD0Ev|
|non-virtual thunk to MainChunkSource::~MainChunkSource|No|()|IDK|_ZThn20_N15MainChunkSourceD0Ev|
|MainChunkSource::releaseChunk|No|(LevelChunk&)|IDK|_ZN15MainChunkSource12releaseChunkER10LevelChunk|
|ChunkRefCount::release|No|()|IDK|_ZN13ChunkRefCount7releaseEv|
|Level::onChunkDiscarded|No|(LevelChunk&)|IDK|_ZN5Level16onChunkDiscardedER10LevelChunk|
|Entity::sharedRandom|No|(undefined|IDK|_ZN6Entity12sharedRandomE|
|Random::genrand_int32|No|()::mag01|IDK|_ZZN6Random13genrand_int32EvE5mag01|
|WorldLimitChunkSource::getExistingChunk|No|(ChunkPos const&)|IDK|_ZN21WorldLimitChunkSource16getExistingChunkERK8ChunkPos|
|ContainerSetContentPacket::~ContainerSetContentPacket|No|()|IDK|_ZN25ContainerSetContentPacketD0Ev|
|TempEPtr<Entity>::~TempEPtr|No|()|IDK|_ZN8TempEPtrI6EntityED2Ev|
|vtable for TempEPtr<Entity>|No|(undefined|IDK|_ZTV8TempEPtrI6EntityE|
|TempEPtr<Entity>::~TempEPtr|No|()|IDK|_ZN8TempEPtrI6EntityED1Ev|
|AvoidMobTypeGoal::~AvoidMobTypeGoal|No|()|IDK|_ZN16AvoidMobTypeGoalD2Ev|
|vtable for AvoidMobTypeGoal|No|(undefined|IDK|_ZTV16AvoidMobTypeGoal|
|AvoidMobTypeGoal::~AvoidMobTypeGoal|No|()|IDK|_ZN16AvoidMobTypeGoalD1Ev|
|SpiderAttackGoal::getAttackReachSqr|No|()|IDK|_ZN16SpiderAttackGoal17getAttackReachSqrEv|
|TempEPtr<Entity>::~TempEPtr|No|()|IDK|_ZN8TempEPtrI6EntityED0Ev|
|AvoidMobTypeGoal::~AvoidMobTypeGoal|No|()|IDK|_ZN16AvoidMobTypeGoalD0Ev|
|StringTag::equals|No|(Tag const&) const|IDK|_ZNK9StringTag6equalsERK3Tag|
|ChatPacket::read|No|(RakNet::BitStream*)|IDK|_ZN10ChatPacket4readEPN6RakNet9BitStreamE|
|RakNet::RakString::RakString|No|()|IDK|_ZN6RakNet9RakStringC1Ev|
|CompoundTag::equals|No|(Tag const&) const|IDK|_ZNK11CompoundTag6equalsERK3Tag|
|WolfModel::~WolfModel|No|()|IDK|_ZN9WolfModelD0Ev|
|Tile::clip|No|(TileSource*, int, int, int, Vec3 const&, Vec3 const&, bool, int)|IDK|_ZN4Tile4clipEP10TileSourceiiiRK4Vec3S4_bi|
|AABB::AABB|No|()|IDK|_ZN4AABBC1Ev|
|HitResult::HitResult|No|(int, int, int, int, Vec3 const&)|IDK|_ZN9HitResultC1EiiiiRK4Vec3|
|AddMobPacket::~AddMobPacket|No|()|IDK|_ZN12AddMobPacketD0Ev|
|AvoidMobTypeGoal::tick|No|()|IDK|_ZN16AvoidMobTypeGoal4tickEv|
|Entity::distanceToSqr|No|(Entity*)|IDK|_ZN6Entity13distanceToSqrEPS_|
|PathNavigation::setSpeed|No|(float)|IDK|_ZN14PathNavigation8setSpeedEf|
|TouchAreaModel::~TouchAreaModel|No|()|IDK|_ZN14TouchAreaModelD2Ev|
|vtable for TouchAreaModel|No|(undefined|IDK|_ZTV14TouchAreaModel|
|TouchAreaModel::~TouchAreaModel|No|()|IDK|_ZN14TouchAreaModelD1Ev|
|TouchAreaModel::~TouchAreaModel|No|()|IDK|_ZN14TouchAreaModelD0Ev|
|PostprocessingManager::~PostprocessingManager|No|()|IDK|_ZN21PostprocessingManagerD2Ev|
|PostprocessingManager::~PostprocessingManager|No|()|IDK|_ZN21PostprocessingManagerD1Ev|
|SetEntityDataPacket::~SetEntityDataPacket|No|()|IDK|_ZN19SetEntityDataPacketD0Ev|
|AddPlayerPacket::~AddPlayerPacket|No|()|IDK|_ZN15AddPlayerPacketD0Ev|
|Minecart::push|No|(Entity*)|IDK|_ZN8Minecart4pushEP6Entity|
|Entity::isMob|No|() const|IDK|_ZNK6Entity5isMobEv|
|LoginStatusPacket::write|No|(RakNet::BitStream*)|IDK|_ZN17LoginStatusPacket5writeEPN6RakNet9BitStreamE|
|RakNet::BitStream::ReverseBytes|No|(unsigned char*, unsigned char*, unsigned int)|IDK|_ZN6RakNet9BitStream12ReverseBytesEPhS1_j|
|RakNet::BitStream::IsNetworkOrderInternal|No|()|IDK|_ZN6RakNet9BitStream22IsNetworkOrderInternalEv|
|guard variable for RakNet::BitStream::IsNetworkOrder|No|()::r|IDK|_ZGVZN6RakNet9BitStream14IsNetworkOrderEvE1r|
|RakNet::BitStream::IsNetworkOrder|No|()::r|IDK|_ZZN6RakNet9BitStream14IsNetworkOrderEvE1r|
|RemoveEntityPacket::write|No|(RakNet::BitStream*)|IDK|_ZN18RemoveEntityPacket5writeEPN6RakNet9BitStreamE|
|MainChunkSource::getExistingChunk|No|(ChunkPos const&)|IDK|_ZN15MainChunkSource16getExistingChunkERK8ChunkPos|
|ChunkRefCount::get|No|() const|IDK|_ZNK13ChunkRefCount3getEv|
|std::array<std::string, 4u>::~array|No|()|IDK|_ZNSt5arrayISsLj4EED2Ev|
|std::array<std::string, 3u>::~array|No|()|IDK|_ZNSt5arrayISsLj3EED2Ev|
|RemoveEntityPacket::read|No|(RakNet::BitStream*)|IDK|_ZN18RemoveEntityPacket4readEPN6RakNet9BitStreamE|
|LoginStatusPacket::read|No|(RakNet::BitStream*)|IDK|_ZN17LoginStatusPacket4readEPN6RakNet9BitStreamE|
|RotateHeadPacket::write|No|(RakNet::BitStream*)|IDK|_ZN16RotateHeadPacket5writeEPN6RakNet9BitStreamE|
|Tile::~Tile|No|()|IDK|_ZN4TileD2Ev|
|vtable for Tile|No|(undefined|IDK|_ZTV4Tile|
|Tile::~Tile|No|()|IDK|_ZN4TileD1Ev|
|ChatPacket::~ChatPacket|No|()|IDK|_ZN10ChatPacketD2Ev|
|vtable for ChatPacket|No|(undefined|IDK|_ZTV10ChatPacket|
|ChatPacket::~ChatPacket|No|()|IDK|_ZN10ChatPacketD1Ev|
|AddPaintingPacket::~AddPaintingPacket|No|()|IDK|_ZN17AddPaintingPacketD2Ev|
|vtable for AddPaintingPacket|No|(undefined|IDK|_ZTV17AddPaintingPacket|
|AddPaintingPacket::~AddPaintingPacket|No|()|IDK|_ZN17AddPaintingPacketD1Ev|
|TransparentTile::~TransparentTile|No|()|IDK|_ZN15TransparentTileD2Ev|
|TransparentTile::~TransparentTile|No|()|IDK|_ZN15TransparentTileD1Ev|
|HalfTransparentTile::~HalfTransparentTile|No|()|IDK|_ZN19HalfTransparentTileD2Ev|
|HalfTransparentTile::~HalfTransparentTile|No|()|IDK|_ZN19HalfTransparentTileD1Ev|
|MonsterEggTile::~MonsterEggTile|No|()|IDK|_ZN14MonsterEggTileD2Ev|
|MonsterEggTile::~MonsterEggTile|No|()|IDK|_ZN14MonsterEggTileD1Ev|
|InvisibleTile::~InvisibleTile|No|()|IDK|_ZN13InvisibleTileD2Ev|
|InvisibleTile::~InvisibleTile|No|()|IDK|_ZN13InvisibleTileD1Ev|
|IceTile::~IceTile|No|()|IDK|_ZN7IceTileD2Ev|
|IceTile::~IceTile|No|()|IDK|_ZN7IceTileD1Ev|
|DirtTile::~DirtTile|No|()|IDK|_ZN8DirtTileD2Ev|
|DirtTile::~DirtTile|No|()|IDK|_ZN8DirtTileD1Ev|
|ClayTile::~ClayTile|No|()|IDK|_ZN8ClayTileD2Ev|
|ClayTile::~ClayTile|No|()|IDK|_ZN8ClayTileD1Ev|
|CakeTile::~CakeTile|No|()|IDK|_ZN8CakeTileD2Ev|
|CakeTile::~CakeTile|No|()|IDK|_ZN8CakeTileD1Ev|
|BookshelfTile::~BookshelfTile|No|()|IDK|_ZN13BookshelfTileD2Ev|
|BookshelfTile::~BookshelfTile|No|()|IDK|_ZN13BookshelfTileD1Ev|
|CactusTile::~CactusTile|No|()|IDK|_ZN10CactusTileD2Ev|
|CactusTile::~CactusTile|No|()|IDK|_ZN10CactusTileD1Ev|
|DirectionalTile::~DirectionalTile|No|()|IDK|_ZN15DirectionalTileD2Ev|
|DirectionalTile::~DirectionalTile|No|()|IDK|_ZN15DirectionalTileD1Ev|
|WorkbenchTile::~WorkbenchTile|No|()|IDK|_ZN13WorkbenchTileD2Ev|
|WorkbenchTile::~WorkbenchTile|No|()|IDK|_ZN13WorkbenchTileD1Ev|
|WebTile::~WebTile|No|()|IDK|_ZN7WebTileD2Ev|
|WebTile::~WebTile|No|()|IDK|_ZN7WebTileD1Ev|
|TopSnowTile::~TopSnowTile|No|()|IDK|_ZN11TopSnowTileD2Ev|
|TopSnowTile::~TopSnowTile|No|()|IDK|_ZN11TopSnowTileD1Ev|
|ThinFenceTile::~ThinFenceTile|No|()|IDK|_ZN13ThinFenceTileD2Ev|
|ThinFenceTile::~ThinFenceTile|No|()|IDK|_ZN13ThinFenceTileD1Ev|
|StonecutterTile::~StonecutterTile|No|()|IDK|_ZN15StonecutterTileD2Ev|
|StonecutterTile::~StonecutterTile|No|()|IDK|_ZN15StonecutterTileD1Ev|
|SnowTile::~SnowTile|No|()|IDK|_ZN8SnowTileD2Ev|
|SnowTile::~SnowTile|No|()|IDK|_ZN8SnowTileD1Ev|
|ReedTile::~ReedTile|No|()|IDK|_ZN8ReedTileD2Ev|
|ReedTile::~ReedTile|No|()|IDK|_ZN8ReedTileD1Ev|
|RedStoneOreTile::~RedStoneOreTile|No|()|IDK|_ZN15RedStoneOreTileD2Ev|
|RedStoneOreTile::~RedStoneOreTile|No|()|IDK|_ZN15RedStoneOreTileD1Ev|
|QuartzBlockTile::~QuartzBlockTile|No|()|IDK|_ZN15QuartzBlockTileD2Ev|
|QuartzBlockTile::~QuartzBlockTile|No|()|IDK|_ZN15QuartzBlockTileD1Ev|
|MetalTile::~MetalTile|No|()|IDK|_ZN9MetalTileD2Ev|
|MetalTile::~MetalTile|No|()|IDK|_ZN9MetalTileD1Ev|
|OreTile::~OreTile|No|()|IDK|_ZN7OreTileD2Ev|
|OreTile::~OreTile|No|()|IDK|_ZN7OreTileD1Ev|
|ObsidianTile::~ObsidianTile|No|()|IDK|_ZN12ObsidianTileD2Ev|
|ObsidianTile::~ObsidianTile|No|()|IDK|_ZN12ObsidianTileD1Ev|
|IntTag::~IntTag|No|()|IDK|_ZN6IntTagD2Ev|
|vtable for Tag|No|(undefined|IDK|_ZTV3Tag|
|IntTag::~IntTag|No|()|IDK|_ZN6IntTagD1Ev|
|ByteTag::~ByteTag|No|()|IDK|_ZN7ByteTagD2Ev|
|ByteTag::~ByteTag|No|()|IDK|_ZN7ByteTagD1Ev|
|BedTile::~BedTile|No|()|IDK|_ZN7BedTileD2Ev|
|BedTile::~BedTile|No|()|IDK|_ZN7BedTileD1Ev|
|SandTile::~SandTile|No|()|IDK|_ZN8SandTileD2Ev|
|SandTile::~SandTile|No|()|IDK|_ZN8SandTileD1Ev|
|GravelTile::~GravelTile|No|()|IDK|_ZN10GravelTileD2Ev|
|GravelTile::~GravelTile|No|()|IDK|_ZN10GravelTileD1Ev|
|GlassTile::~GlassTile|No|()|IDK|_ZN9GlassTileD2Ev|
|GlassTile::~GlassTile|No|()|IDK|_ZN9GlassTileD1Ev|
|StemTile::~StemTile|No|()|IDK|_ZN8StemTileD2Ev|
|StemTile::~StemTile|No|()|IDK|_ZN8StemTileD1Ev|
|HayBlockTile::~HayBlockTile|No|()|IDK|_ZN12HayBlockTileD2Ev|
|HayBlockTile::~HayBlockTile|No|()|IDK|_ZN12HayBlockTileD1Ev|
|MobSpawnerTile::~MobSpawnerTile|No|()|IDK|_ZN14MobSpawnerTileD2Ev|
|MobSpawnerTile::~MobSpawnerTile|No|()|IDK|_ZN14MobSpawnerTileD1Ev|
|NetherReactorTile::~NetherReactorTile|No|()|IDK|_ZN17NetherReactorTileD2Ev|
|NetherReactorTile::~NetherReactorTile|No|()|IDK|_ZN17NetherReactorTileD1Ev|
|SetTimePacket::write|No|(RakNet::BitStream*)|IDK|_ZN13SetTimePacket5writeEPN6RakNet9BitStreamE|
|RakNet::BitStream::Write0|No|()|IDK|_ZN6RakNet9BitStream6Write0Ev|
|RakNet::BitStream::Write1|No|()|IDK|_ZN6RakNet9BitStream6Write1Ev|
|SetEntityDataPacket::write|No|(RakNet::BitStream*)|IDK|_ZN19SetEntityDataPacket5writeEPN6RakNet9BitStreamE|
|SynchedEntityData::pack|No|(std::vector<DataItem*, std::allocator<DataItem*> >*, IDataOutput*)|IDK|_ZN17SynchedEntityData4packEPSt6vectorIP8DataItemSaIS2_EEP11IDataOutput|
|vtable for RakDataOutput|No|(undefined|IDK|_ZTV13RakDataOutput|
|SetTimePacket::read|No|(RakNet::BitStream*)|IDK|_ZN13SetTimePacket4readEPN6RakNet9BitStreamE|
|RemovePlayerPacket::write|No|(RakNet::BitStream*)|IDK|_ZN18RemovePlayerPacket5writeEPN6RakNet9BitStreamE|
|std::shared_ptr<TextureAtlas>::~shared_ptr|No|()|IDK|_ZNSt10shared_ptrI12TextureAtlasED2Ev|
|std::shared_ptr<TextureAtlas>::~shared_ptr|No|()|IDK|_ZNSt10shared_ptrI12TextureAtlasED1Ev|
|SmoothLayer::~SmoothLayer|No|()|IDK|_ZN11SmoothLayerD2Ev|
|vtable for Layer|No|(undefined|IDK|_ZTV5Layer|
|SmoothLayer::~SmoothLayer|No|()|IDK|_ZN11SmoothLayerD1Ev|
|ZoomLayer::~ZoomLayer|No|()|IDK|_ZN9ZoomLayerD2Ev|
|ZoomLayer::~ZoomLayer|No|()|IDK|_ZN9ZoomLayerD1Ev|
|RiverInitLayer::~RiverInitLayer|No|()|IDK|_ZN14RiverInitLayerD2Ev|
|RiverInitLayer::~RiverInitLayer|No|()|IDK|_ZN14RiverInitLayerD1Ev|
|SmoothZoomLayer::~SmoothZoomLayer|No|()|IDK|_ZN15SmoothZoomLayerD2Ev|
|SmoothZoomLayer::~SmoothZoomLayer|No|()|IDK|_ZN15SmoothZoomLayerD1Ev|
|InteractPacket::write|No|(RakNet::BitStream*)|IDK|_ZN14InteractPacket5writeEPN6RakNet9BitStreamE|
|Tile::~Tile|No|()|IDK|_ZN4TileD0Ev|
|Minecart::~Minecart|No|()|IDK|_ZN8MinecartD2Ev|
|vtable for Minecart|No|(undefined|IDK|_ZTV8Minecart|
|Minecart::~Minecart|No|()|IDK|_ZN8MinecartD1Ev|
|SetSpawnPositionPacket::write|No|(RakNet::BitStream*)|IDK|_ZN22SetSpawnPositionPacket5writeEPN6RakNet9BitStreamE|
|RemovePlayerPacket::read|No|(RakNet::BitStream*)|IDK|_ZN18RemovePlayerPacket4readEPN6RakNet9BitStreamE|
|GuiElementContainer::clearAll|No|()|IDK|_ZN19GuiElementContainer8clearAllEv|
|DBChunkStorage::onLowMemory|No|()|IDK|_ZN14DBChunkStorage11onLowMemoryEv|
|non-virtual thunk to DBChunkStorage::onLowMemory|No|()|IDK|_ZThn20_N14DBChunkStorage11onLowMemoryEv|
|DirectionalTile::~DirectionalTile|No|()|IDK|_ZN15DirectionalTileD0Ev|
|ByteTag::~ByteTag|No|()|IDK|_ZN7ByteTagD0Ev|
|HalfTransparentTile::~HalfTransparentTile|No|()|IDK|_ZN19HalfTransparentTileD0Ev|
|TransparentTile::~TransparentTile|No|()|IDK|_ZN15TransparentTileD0Ev|
|WorkbenchTile::~WorkbenchTile|No|()|IDK|_ZN13WorkbenchTileD0Ev|
|CakeTile::~CakeTile|No|()|IDK|_ZN8CakeTileD0Ev|
|ThinFenceTile::~ThinFenceTile|No|()|IDK|_ZN13ThinFenceTileD0Ev|
|StonecutterTile::~StonecutterTile|No|()|IDK|_ZN15StonecutterTileD0Ev|
|WebTile::~WebTile|No|()|IDK|_ZN7WebTileD0Ev|
|TopSnowTile::~TopSnowTile|No|()|IDK|_ZN11TopSnowTileD0Ev|
|BookshelfTile::~BookshelfTile|No|()|IDK|_ZN13BookshelfTileD0Ev|
|ObsidianTile::~ObsidianTile|No|()|IDK|_ZN12ObsidianTileD0Ev|
|InvisibleTile::~InvisibleTile|No|()|IDK|_ZN13InvisibleTileD0Ev|
|IceTile::~IceTile|No|()|IDK|_ZN7IceTileD0Ev|
|DirtTile::~DirtTile|No|()|IDK|_ZN8DirtTileD0Ev|
|ClayTile::~ClayTile|No|()|IDK|_ZN8ClayTileD0Ev|
|RedStoneOreTile::~RedStoneOreTile|No|()|IDK|_ZN15RedStoneOreTileD0Ev|
|QuartzBlockTile::~QuartzBlockTile|No|()|IDK|_ZN15QuartzBlockTileD0Ev|
|SnowTile::~SnowTile|No|()|IDK|_ZN8SnowTileD0Ev|
|ReedTile::~ReedTile|No|()|IDK|_ZN8ReedTileD0Ev|
|IntTag::~IntTag|No|()|IDK|_ZN6IntTagD0Ev|
|MetalTile::~MetalTile|No|()|IDK|_ZN9MetalTileD0Ev|
|OreTile::~OreTile|No|()|IDK|_ZN7OreTileD0Ev|
|AddPaintingPacket::~AddPaintingPacket|No|()|IDK|_ZN17AddPaintingPacketD0Ev|
|MonsterEggTile::~MonsterEggTile|No|()|IDK|_ZN14MonsterEggTileD0Ev|
|CactusTile::~CactusTile|No|()|IDK|_ZN10CactusTileD0Ev|
|ChatPacket::~ChatPacket|No|()|IDK|_ZN10ChatPacketD0Ev|
|Tile::SoundType::~SoundType|No|()|IDK|_ZN4Tile9SoundTypeD2Ev|
|Tile::SoundType::~SoundType|No|()|IDK|_ZN4Tile9SoundTypeD1Ev|
(null)
|SandTile::~SandTile|No|()|IDK|_ZN8SandTileD0Ev|
|HayBlockTile::~HayBlockTile|No|()|IDK|_ZN12HayBlockTileD0Ev|
|MobSpawnerTile::~MobSpawnerTile|No|()|IDK|_ZN14MobSpawnerTileD0Ev|
|NetherReactorTile::~NetherReactorTile|No|()|IDK|_ZN17NetherReactorTileD0Ev|
|StemTile::~StemTile|No|()|IDK|_ZN8StemTileD0Ev|
|BedTile::~BedTile|No|()|IDK|_ZN7BedTileD0Ev|
|ListTag::~ListTag|No|()|IDK|_ZN7ListTagD2Ev|
|vtable for ListTag|No|(undefined|IDK|_ZTV7ListTag|
|ListTag::~ListTag|No|()|IDK|_ZN7ListTagD1Ev|
|GlassTile::~GlassTile|No|()|IDK|_ZN9GlassTileD0Ev|
|GravelTile::~GravelTile|No|()|IDK|_ZN10GravelTileD0Ev|
|StringTag::~StringTag|No|()|IDK|_ZN9StringTagD2Ev|
|vtable for StringTag|No|(undefined|IDK|_ZTV9StringTag|
|StringTag::~StringTag|No|()|IDK|_ZN9StringTagD1Ev|
|ClothTileItem::~ClothTileItem|No|()|IDK|_ZN13ClothTileItemD2Ev|
|vtable for Item|No|(undefined|IDK|_ZTV4Item|
|ClothTileItem::~ClothTileItem|No|()|IDK|_ZN13ClothTileItemD1Ev|
|LeafTileItem::~LeafTileItem|No|()|IDK|_ZN12LeafTileItemD2Ev|
|LeafTileItem::~LeafTileItem|No|()|IDK|_ZN12LeafTileItemD1Ev|
|SaplingTileItem::~SaplingTileItem|No|()|IDK|_ZN15SaplingTileItemD2Ev|
|SaplingTileItem::~SaplingTileItem|No|()|IDK|_ZN15SaplingTileItemD1Ev|
|StoneSlabTileItem::~StoneSlabTileItem|No|()|IDK|_ZN17StoneSlabTileItemD2Ev|
|StoneSlabTileItem::~StoneSlabTileItem|No|()|IDK|_ZN17StoneSlabTileItemD1Ev|
|WaterLilyTileItem::~WaterLilyTileItem|No|()|IDK|_ZN17WaterLilyTileItemD2Ev|
|WaterLilyTileItem::~WaterLilyTileItem|No|()|IDK|_ZN17WaterLilyTileItemD1Ev|
|PlayerArmorEquipmentPacket::write|No|(RakNet::BitStream*)|IDK|_ZN26PlayerArmorEquipmentPacket5writeEPN6RakNet9BitStreamE|
|SetEntityLinkPacket::write|No|(RakNet::BitStream*)|IDK|_ZN19SetEntityLinkPacket5writeEPN6RakNet9BitStreamE|
|LeafTile::~LeafTile|No|()|IDK|_ZN8LeafTileD2Ev|
|vtable for LeafTile|No|(undefined|IDK|_ZTV8LeafTile|
|LeafTile::~LeafTile|No|()|IDK|_ZN8LeafTileD1Ev|
|LeafTile::~LeafTile|No|()|IDK|_ZN8LeafTileD0Ev|
|InteractPacket::read|No|(RakNet::BitStream*)|IDK|_ZN14InteractPacket4readEPN6RakNet9BitStreamE|
|SetSpawnPositionPacket::read|No|(RakNet::BitStream*)|IDK|_ZN22SetSpawnPositionPacket4readEPN6RakNet9BitStreamE|
|SmoothZoomLayer::~SmoothZoomLayer|No|()|IDK|_ZN15SmoothZoomLayerD0Ev|
|ZoomLayer::~ZoomLayer|No|()|IDK|_ZN9ZoomLayerD0Ev|
|SmoothLayer::~SmoothLayer|No|()|IDK|_ZN11SmoothLayerD0Ev|
|RiverInitLayer::~RiverInitLayer|No|()|IDK|_ZN14RiverInitLayerD0Ev|
|UpdateBlockPacket::write|No|(RakNet::BitStream*)|IDK|_ZN17UpdateBlockPacket5writeEPN6RakNet9BitStreamE|
|SetEntityDataPacket::read|No|(RakNet::BitStream*)|IDK|_ZN19SetEntityDataPacket4readEPN6RakNet9BitStreamE|
|SynchedEntityData::unpack|No|(IDataInput*)|IDK|_ZN17SynchedEntityData6unpackEP10IDataInput|
|vtable for RakDataInput|No|(undefined|IDK|_ZTV12RakDataInput|
|SetEntityMotionPacket::write|No|(RakNet::BitStream*)|IDK|_ZN21SetEntityMotionPacket5writeEPN6RakNet9BitStreamE|
|Minecart::~Minecart|No|()|IDK|_ZN8MinecartD0Ev|
|ContainerSetContentPacket::write|No|(RakNet::BitStream*)|IDK|_ZN25ContainerSetContentPacket5writeEPN6RakNet9BitStreamE|
|PacketUtil::writeItemInstance|No|(ItemInstance const&, RakNet::BitStream*)|IDK|_ZN10PacketUtil17writeItemInstanceERK12ItemInstancePN6RakNet9BitStreamE|
|OldLogTile::~OldLogTile|No|()|IDK|_ZN10OldLogTileD2Ev|
|vtable for LogTile|No|(undefined|IDK|_ZTV7LogTile|
|OldLogTile::~OldLogTile|No|()|IDK|_ZN10OldLogTileD1Ev|
|NewLogTile::~NewLogTile|No|()|IDK|_ZN10NewLogTileD2Ev|
|NewLogTile::~NewLogTile|No|()|IDK|_ZN10NewLogTileD1Ev|
|ListTag::~ListTag|No|()|IDK|_ZN7ListTagD0Ev|
|PlayerArmorEquipmentPacket::read|No|(RakNet::BitStream*)|IDK|_ZN26PlayerArmorEquipmentPacket4readEPN6RakNet9BitStreamE|
|StringTag::~StringTag|No|()|IDK|_ZN9StringTagD0Ev|
|ImageButton::~ImageButton|No|()|IDK|_ZN11ImageButtonD2Ev|
|vtable for ImageButton|No|(undefined|IDK|_ZTV11ImageButton|
|vtable for Button|No|(undefined|IDK|_ZTV6Button|
|ImageButton::~ImageButton|No|()|IDK|_ZN11ImageButtonD1Ev|
|SandStoneTile::~SandStoneTile|No|()|IDK|_ZN13SandStoneTileD2Ev|
|vtable for MultiTextureTile|No|(undefined|IDK|_ZTV16MultiTextureTile|
|SandStoneTile::~SandStoneTile|No|()|IDK|_ZN13SandStoneTileD1Ev|
|Minecart::getInteractText|No|(Player*)|IDK|_ZN8Minecart15getInteractTextEP6Player|
|I18n::get|No|(std::string const&)|IDK|_ZN4I18n3getERKSs|
|CategoryButton::~CategoryButton|No|()|IDK|_ZN14CategoryButtonD2Ev|
|CategoryButton::~CategoryButton|No|()|IDK|_ZN14CategoryButtonD1Ev|
|SetEntityLinkPacket::read|No|(RakNet::BitStream*)|IDK|_ZN19SetEntityLinkPacket4readEPN6RakNet9BitStreamE|
|OptionButton::~OptionButton|No|()|IDK|_ZN12OptionButtonD2Ev|
|OptionButton::~OptionButton|No|()|IDK|_ZN12OptionButtonD1Ev|
|LeafTileItem::~LeafTileItem|No|()|IDK|_ZN12LeafTileItemD0Ev|
|StoneSlabTileItem::~StoneSlabTileItem|No|()|IDK|_ZN17StoneSlabTileItemD0Ev|
|LiquidTile::~LiquidTile|No|()|IDK|_ZN10LiquidTileD2Ev|
|vtable for LiquidTile|No|(undefined|IDK|_ZTV10LiquidTile|
|LiquidTile::~LiquidTile|No|()|IDK|_ZN10LiquidTileD1Ev|
|WaterLilyTileItem::~WaterLilyTileItem|No|()|IDK|_ZN17WaterLilyTileItemD0Ev|
|ClothTileItem::~ClothTileItem|No|()|IDK|_ZN13ClothTileItemD0Ev|
|ClothTile::~ClothTile|No|()|IDK|_ZN9ClothTileD2Ev|
|vtable for ClothTile|No|(undefined|IDK|_ZTV9ClothTile|
|ClothTile::~ClothTile|No|()|IDK|_ZN9ClothTileD1Ev|
|MultiTextureTile::~MultiTextureTile|No|()|IDK|_ZN16MultiTextureTileD2Ev|
|MultiTextureTile::~MultiTextureTile|No|()|IDK|_ZN16MultiTextureTileD1Ev|
|ColoredTile::~ColoredTile|No|()|IDK|_ZN11ColoredTileD2Ev|
|vtable for ColoredTile|No|(undefined|IDK|_ZTV11ColoredTile|
|ColoredTile::~ColoredTile|No|()|IDK|_ZN11ColoredTileD1Ev|
|StoneTile::~StoneTile|No|()|IDK|_ZN9StoneTileD2Ev|
|vtable for StoneTile|No|(undefined|IDK|_ZTV9StoneTile|
|StoneTile::~StoneTile|No|()|IDK|_ZN9StoneTileD1Ev|
|SaplingTileItem::~SaplingTileItem|No|()|IDK|_ZN15SaplingTileItemD0Ev|
|CropTile::~CropTile|No|()|IDK|_ZN8CropTileD2Ev|
|vtable for CropTile|No|(undefined|IDK|_ZTV8CropTile|
|CropTile::~CropTile|No|()|IDK|_ZN8CropTileD1Ev|
|StringTag::load|No|(IDataInput*)|IDK|_ZN9StringTag4loadEP10IDataInput|
|TileEventPacket::write|No|(RakNet::BitStream*)|IDK|_ZN15TileEventPacket5writeEPN6RakNet9BitStreamE|
|LevelEventPacket::write|No|(RakNet::BitStream*)|IDK|_ZN16LevelEventPacket5writeEPN6RakNet9BitStreamE|
|UpdateBlockPacket::read|No|(RakNet::BitStream*)|IDK|_ZN17UpdateBlockPacket4readEPN6RakNet9BitStreamE|
|OldLogTile::~OldLogTile|No|()|IDK|_ZN10OldLogTileD0Ev|
|NewLogTile::~NewLogTile|No|()|IDK|_ZN10NewLogTileD0Ev|
|StoneTile::~StoneTile|No|()|IDK|_ZN9StoneTileD0Ev|
|ColoredTile::~ColoredTile|No|()|IDK|_ZN11ColoredTileD0Ev|
|ClothTile::~ClothTile|No|()|IDK|_ZN9ClothTileD0Ev|
|MultiTextureTile::~MultiTextureTile|No|()|IDK|_ZN16MultiTextureTileD0Ev|
|ImageButton::~ImageButton|No|()|IDK|_ZN11ImageButtonD0Ev|
|LiquidTile::~LiquidTile|No|()|IDK|_ZN10LiquidTileD0Ev|
|CropTile::~CropTile|No|()|IDK|_ZN8CropTileD0Ev|
|CategoryButton::~CategoryButton|No|()|IDK|_ZN14CategoryButtonD0Ev|
|OptionButton::~OptionButton|No|()|IDK|_ZN12OptionButtonD0Ev|
|SandStoneTile::~SandStoneTile|No|()|IDK|_ZN13SandStoneTileD0Ev|
|Tile::setDescriptionId|No|(std::string const&)|IDK|_ZN4Tile16setDescriptionIdERKSs|
|Tile::TILE_DESCRIPTION_PREFIX|No|(undefined|IDK|_ZN4Tile23TILE_DESCRIPTION_PREFIXE|
|GuiElementContainer::~GuiElementContainer|No|()|IDK|_ZN19GuiElementContainerD2Ev|
|vtable for GuiElementContainer|No|(undefined|IDK|_ZTV19GuiElementContainer|
|GuiElementContainer::~GuiElementContainer|No|()|IDK|_ZN19GuiElementContainerD1Ev|
|GuiElementContainer::~GuiElementContainer|No|()|IDK|_ZN19GuiElementContainerD0Ev|
|OptionsGroup::~OptionsGroup|No|()|IDK|_ZN12OptionsGroupD2Ev|
|vtable for OptionsGroup|No|(undefined|IDK|_ZTV12OptionsGroup|
|OptionsGroup::~OptionsGroup|No|()|IDK|_ZN12OptionsGroupD1Ev|
|OptionsGroup::~OptionsGroup|No|()|IDK|_ZN12OptionsGroupD0Ev|
|MoveEntityPacket::write|No|(RakNet::BitStream*)|IDK|_ZN16MoveEntityPacket5writeEPN6RakNet9BitStreamE|
|AddPaintingPacket::write|No|(RakNet::BitStream*)|IDK|_ZN17AddPaintingPacket5writeEPN6RakNet9BitStreamE|
|RakNet::RakString::NonVariadic|No|(char const*)|IDK|_ZN6RakNet9RakString11NonVariadicEPKc|
|GuiElementContainer::setTextboxText|No|(std::string const&)|IDK|_ZN19GuiElementContainer14setTextboxTextERKSs|
|GuiElementContainer::keyPressed|No|(Minecraft*, int)|IDK|_ZN19GuiElementContainer10keyPressedEP9Minecrafti|
|IntTag::copy|No|() const|IDK|_ZNK6IntTag4copyEv|
|Tag::Tag|No|(std::string const&)|IDK|_ZN3TagC2ERKSs|
|vtable for IntTag|No|(undefined|IDK|_ZTV6IntTag|
|ByteTag::copy|No|() const|IDK|_ZNK7ByteTag4copyEv|
|vtable for ByteTag|No|(undefined|IDK|_ZTV7ByteTag|
|GuiElementContainer::topRender|No|(Minecraft*, int, int)|IDK|_ZN19GuiElementContainer9topRenderEP9Minecraftii|
|GuiElementContainer::focusuedMouseReleased|No|(Minecraft*, int, int, int)|IDK|_ZN19GuiElementContainer21focusuedMouseReleasedEP9Minecraftiii|
|GuiElementContainer::mouseClicked|No|(Minecraft*, int, int, int)|IDK|_ZN19GuiElementContainer12mouseClickedEP9Minecraftiii|
|GuiElementContainer::mouseReleased|No|(Minecraft*, int, int, int)|IDK|_ZN19GuiElementContainer13mouseReleasedEP9Minecraftiii|
|GuiElementContainer::focusuedMouseClicked|No|(Minecraft*, int, int, int)|IDK|_ZN19GuiElementContainer20focusuedMouseClickedEP9Minecraftiii|
|GuiElementContainer::render|No|(Minecraft*, int, int)|IDK|_ZN19GuiElementContainer6renderEP9Minecraftii|
|OptionsGroup::render|No|(Minecraft*, int, int)|IDK|_ZN12OptionsGroup6renderEP9Minecraftii|
|Font::drawShadow|No|(std::string const&, float, float, int)|IDK|_ZN4Font10drawShadowERKSsffi|
|GuiElementContainer::backPressed|No|(Minecraft*, bool)|IDK|_ZN19GuiElementContainer11backPressedEP9Minecraftb|
|GuiElementContainer::setupPositions|No|()|IDK|_ZN19GuiElementContainer14setupPositionsEv|
|AddMobPacket::write|No|(RakNet::BitStream*)|IDK|_ZN12AddMobPacket5writeEPN6RakNet9BitStreamE|
|PacketUtil::Rot_degreesToChar|No|(float)|IDK|_ZN10PacketUtil17Rot_degreesToCharEf|
|SynchedEntityData::packAll|No|(IDataOutput*) const|IDK|_ZNK17SynchedEntityData7packAllEP11IDataOutput|
|OptionsGroup::setupPositions|No|()|IDK|_ZN12OptionsGroup14setupPositionsEv|
|AddItemEntityPacket::write|No|(RakNet::BitStream*)|IDK|_ZN19AddItemEntityPacket5writeEPN6RakNet9BitStreamE|
|StringTag::copy|No|() const|IDK|_ZNK9StringTag4copyEv|
|GuiElementContainer::keyboardNewChar|No|(Minecraft*, std::string, bool)|IDK|_ZN19GuiElementContainer15keyboardNewCharEP9MinecraftSsb|
|AddEntityPacket::write|No|(RakNet::BitStream*)|IDK|_ZN15AddEntityPacket5writeEPN6RakNet9BitStreamE|
|Tile::getName|No|() const|IDK|_ZNK4Tile7getNameEv|
|StartGamePacket::write|No|(RakNet::BitStream*)|IDK|_ZN15StartGamePacket5writeEPN6RakNet9BitStreamE|
|AddPlayerPacket::write|No|(RakNet::BitStream*)|IDK|_ZN15AddPlayerPacket5writeEPN6RakNet9BitStreamE|
|ClothTileItem::getDescriptionId|No|(ItemInstance const*) const|IDK|_ZNK13ClothTileItem16getDescriptionIdEPK12ItemInstance|
|TileItem::getDescriptionId|No|() const|IDK|_ZNK8TileItem16getDescriptionIdEv|
|ItemInstance::getAuxValue|No|() const|IDK|_ZNK12ItemInstance11getAuxValueEv|
|DyePowderItem::COLOR_DESCS|No|(undefined|IDK|_ZN13DyePowderItem11COLOR_DESCSE|
|StoneSlabTileItem::getDescriptionId|No|(ItemInstance const*) const|IDK|_ZNK17StoneSlabTileItem16getDescriptionIdEPK12ItemInstance|
|StoneSlabTile::SLAB_NAMES_COUNT|No|(undefined|IDK|_ZN13StoneSlabTile16SLAB_NAMES_COUNTE|
|StoneSlabTile::SLAB_NAMES|No|(undefined|IDK|_ZN13StoneSlabTile10SLAB_NAMESE|
|LavaParticle::init|No|(float, float, float, float, float, float, int)|IDK|_ZN12LavaParticle4initEffffffi|
|BubbleParticle::init|No|(float, float, float, float, float, float, int)|IDK|_ZN14BubbleParticle4initEffffffi|
|LavaParticle::normalTick|No|()|IDK|_ZN12LavaParticle10normalTickEv|
|Level::addParticle|No|(ParticleType, float, float, float, float, float, float, int)|IDK|_ZN5Level11addParticleE12ParticleTypeffffffi|
|MobFlameParticle::init|No|(float, float, float, float, float, float, int)|IDK|_ZN16MobFlameParticle4initEffffffi|
|SuspendedTownParticle::init|No|(float, float, float, float, float, float, int)|IDK|_ZN21SuspendedTownParticle4initEffffffi|
|ExplodeParticle::init|No|(float, float, float, float, float, float, int)|IDK|_ZN15ExplodeParticle4initEffffffi|
|FlameParticle::init|No|(float, float, float, float, float, float, int)|IDK|_ZN13FlameParticle4initEffffffi|
|IntTag::toString|No|() const|IDK|_ZNK6IntTag8toStringEv|
|ClothTileItem::getName|No|(ItemInstance const*) const|IDK|_ZNK13ClothTileItem7getNameEPK12ItemInstance|
|StringTag::toString|No|() const|IDK|_ZNK9StringTag8toStringEv|
|Touch::IngameBlockSelectionScreen::render|No|(int, int, float)|IDK|_ZN5Touch26IngameBlockSelectionScreen6renderEiif|
|Screen::render|No|(int, int, float)|IDK|_ZN6Screen6renderEiif|
|ScrollingPane::render|No|(int, int, float, Minecraft*)|IDK|_ZN13ScrollingPane6renderEiifP9Minecraft|
|Textures::bindTexture|No|(std::string const&)|IDK|_ZN8Textures11bindTextureERKSs|
|GuiComponent::blit|No|(int, int, int, int, int, int, int, int)|IDK|_ZN12GuiComponent4blitEiiiiiiii|
|Gui::renderToolBar|No|(float, float)|IDK|_ZN3Gui13renderToolBarEff|
|Gui::renderOnSelectItemNameText|No|(int, Font*, int)|IDK|_ZN3Gui26renderOnSelectItemNameTextEiP4Fonti|
|StoneSlabTileItem::getName|No|(ItemInstance const*) const|IDK|_ZNK17StoneSlabTileItem7getNameEPK12ItemInstance|
|ServerSideNetworkHandler::~ServerSideNetworkHandler|No|()|IDK|_ZN24ServerSideNetworkHandlerD2Ev|
|Level::removeListener|No|(LevelListener*)|IDK|_ZN5Level14removeListenerEP13LevelListener|
|vtable for ServerSideNetworkHandler|No|(undefined|IDK|_ZTV24ServerSideNetworkHandler|
|vtable for NetEventCallback|No|(undefined|IDK|_ZTV16NetEventCallback|
|ServerSideNetworkHandler::~ServerSideNetworkHandler|No|()|IDK|_ZN24ServerSideNetworkHandlerD1Ev|
|non-virtual thunk to ServerSideNetworkHandler::~ServerSideNetworkHandler|No|()|IDK|_ZThn4_N24ServerSideNetworkHandlerD1Ev|
|ServerSideNetworkHandler::~ServerSideNetworkHandler|No|()|IDK|_ZN24ServerSideNetworkHandlerD0Ev|
|non-virtual thunk to ServerSideNetworkHandler::~ServerSideNetworkHandler|No|()|IDK|_ZThn4_N24ServerSideNetworkHandlerD0Ev|
|FlowerTile::~FlowerTile|No|()|IDK|_ZN10FlowerTileD2Ev|
|vtable for FlowerTile|No|(undefined|IDK|_ZTV10FlowerTile|
|FlowerTile::~FlowerTile|No|()|IDK|_ZN10FlowerTileD1Ev|
|LeafTileItem::getDescription|No|(ItemInstance const*) const|IDK|_ZNK12LeafTileItem14getDescriptionEPK12ItemInstance|
|Item::getDescription|No|(ItemInstance const*) const|IDK|_ZNK4Item14getDescriptionEPK12ItemInstance|
|SaplingTileItem::getDescription|No|(ItemInstance const*) const|IDK|_ZNK15SaplingTileItem14getDescriptionEPK12ItemInstance|
|CompoundTag::toString|No|() const|IDK|_ZNK11CompoundTag8toStringEv|
|QuartzBlockTile::getDescriptionId|No|(ItemInstance const*) const|IDK|_ZNK15QuartzBlockTile16getDescriptionIdEPK12ItemInstance|
|Touch::IngameBlockSelectionScreen::addItem|No|(Touch::InventoryPane const*, int)|IDK|_ZN5Touch26IngameBlockSelectionScreen7addItemEPKNS_13InventoryPaneEi|
|Inventory::getLinkedSlotForItem|No|(int)|IDK|_ZN9Inventory20getLinkedSlotForItemEi|
|Gui::getNumSlots|No|()|IDK|_ZN3Gui11getNumSlotsEv|
|Inventory::moveToSelectionSlot|No|(int, int)|IDK|_ZN9Inventory19moveToSelectionSlotEii|
|SoundEngine::playUI|No|(std::string const&, float, float)|IDK|_ZN11SoundEngine6playUIERKSsff|
|ItemInstance::getName|No|() const|IDK|_ZNK12ItemInstance7getNameEv|
|Gui::showPopupNotice|No|(std::string const&)|IDK|_ZN3Gui15showPopupNoticeERKSs|
|Gui::flashSlot|No|(int)|IDK|_ZN3Gui9flashSlotEi|
|non-virtual thunk to Touch::IngameBlockSelectionScreen::addItem|No|(Touch::InventoryPane const*, int)|IDK|_ZThn132_N5Touch26IngameBlockSelectionScreen7addItemEPKNS_13InventoryPaneEi|
|ListTag::toString|No|() const|IDK|_ZNK7ListTag8toStringEv|
|Tag::getTagName|No|(char)|IDK|_ZN3Tag10getTagNameEc|
|GuiElementContainer::removeChild|No|(std::shared_ptr<GuiElement>)|IDK|_ZN19GuiElementContainer11removeChildESt10shared_ptrI10GuiElementE|
|SaplingTileItem::getName|No|(ItemInstance const*) const|IDK|_ZNK15SaplingTileItem7getNameEPK12ItemInstance|
|Item::getName|No|(ItemInstance const*) const|IDK|_ZNK4Item7getNameEPK12ItemInstance|
|LeafTileItem::getName|No|(ItemInstance const*) const|IDK|_ZNK12LeafTileItem7getNameEPK12ItemInstance|
|OptionsGroup::createStepSlider|No|(Options::Option const*, Minecraft*)|IDK|_ZN12OptionsGroup16createStepSliderEPKN7Options6OptionEP9Minecraft|
|Options::getValues|No|(Options::Option const*)|IDK|_ZN7Options9getValuesEPKNS_6OptionE|
|Slider::Slider|No|(Minecraft*, Options::Option const*, std::vector<int, std::allocator<int> > const&)|IDK|_ZN6SliderC1EP9MinecraftPKN7Options6OptionERKSt6vectorIiSaIiEE|
|OptionsItem::OptionsItem|No|(Options::Option const*, std::shared_ptr<GuiElement>)|IDK|_ZN11OptionsItemC1EPKN7Options6OptionESt10shared_ptrI10GuiElementE|
|vtable for std::_Sp_counted_ptr<Slider*, |No|(__gnu_cxx::_Lock_policy)2>|IDK|_ZTVSt15_Sp_counted_ptrIP6SliderLN9__gnu_cxx12_Lock_policyE2EE|
|vtable for std::_Sp_counted_ptr<OptionsItem*, |No|(__gnu_cxx::_Lock_policy)2>|IDK|_ZTVSt15_Sp_counted_ptrIP11OptionsItemLN9__gnu_cxx12_Lock_policyE2EE|
|OptionsGroup::createProgressSlider|No|(Options::Option const*, Minecraft*)|IDK|_ZN12OptionsGroup20createProgressSliderEPKN7Options6OptionEP9Minecraft|
|Options::getProgrssMin|No|(Options::Option const*)|IDK|_ZN7Options13getProgrssMinEPKNS_6OptionE|
|Options::getProgrssMax|No|(Options::Option const*)|IDK|_ZN7Options13getProgrssMaxEPKNS_6OptionE|
|Slider::Slider|No|(Minecraft*, Options::Option const*, float, float)|IDK|_ZN6SliderC1EP9MinecraftPKN7Options6OptionEff|
|CreativeInventoryScreen::setupPositions|No|()|IDK|_ZN23CreativeInventoryScreen14setupPositionsEv|
|Minecraft::useController|No|()|IDK|_ZN9Minecraft13useControllerEv|
|Touch::InventoryPane::InventoryPane|No|(Touch::IInventoryPaneCallback*, Minecraft*, IntRectangle const&, int, float, int, int, int, bool, bool, bool)|IDK|_ZN5Touch13InventoryPaneC1EPNS_22IInventoryPaneCallbackEP9MinecraftRK12IntRectangleifiiibbb|
|vtable for std::_Sp_counted_ptr<Touch::InventoryPane*, |No|(__gnu_cxx::_Lock_policy)2>|IDK|_ZTVSt15_Sp_counted_ptrIPN5Touch13InventoryPaneELN9__gnu_cxx12_Lock_policyE2EE|
|ListTag::print|No|(std::string const&, PrintStream&) const|IDK|_ZNK7ListTag5printERKSsR11PrintStream|
|Tag::print|No|(std::string const&, PrintStream&) const|IDK|_ZNK3Tag5printERKSsR11PrintStream|
|CompoundTag::print|No|(std::string const&, PrintStream&) const|IDK|_ZNK11CompoundTag5printERKSsR11PrintStream|
|CreativeInventoryScreen::~CreativeInventoryScreen|No|()|IDK|_ZN23CreativeInventoryScreenD2Ev|
|Screen::~Screen|No|()|IDK|_ZN6ScreenD2Ev|
|vtable for CreativeInventoryScreen|No|(undefined|IDK|_ZTV23CreativeInventoryScreen|
|CreativeInventoryScreen::~CreativeInventoryScreen|No|()|IDK|_ZN23CreativeInventoryScreenD1Ev|
|non-virtual thunk to CreativeInventoryScreen::~CreativeInventoryScreen|No|()|IDK|_ZThn132_N23CreativeInventoryScreenD1Ev|
|CreativeInventoryScreen::~CreativeInventoryScreen|No|()|IDK|_ZN23CreativeInventoryScreenD0Ev|
|non-virtual thunk to CreativeInventoryScreen::~CreativeInventoryScreen|No|()|IDK|_ZThn132_N23CreativeInventoryScreenD0Ev|
|FlowerTile::~FlowerTile|No|()|IDK|_ZN10FlowerTileD0Ev|
|GuiElementContainer::suppressOtherGUI|No|()|IDK|_ZN19GuiElementContainer16suppressOtherGUIEv|
|PlainsBiome::getTreeFeature|No|(Random*)|IDK|_ZN11PlainsBiome14getTreeFeatureEP6Random|
|OakFeature::place|No|(TileSource*, int, int, int, Random&) const|IDK|_ZNK10OakFeature5placeEP10TileSourceiiiR6Random|
|TreeFeature::place|No|(TileSource*, int, int, int, Random&, int) const|IDK|_ZNK11TreeFeature5placeEP10TileSourceiiiR6Randomi|
|MegaTreeFeature::place|No|(TileSource*, int, int, int, Random&) const|IDK|_ZNK15MegaTreeFeature5placeEP10TileSourceiiiR6Random|
|JungleTreeFeature::place|No|(TileSource*, int, int, int, Random&) const|IDK|_ZNK17JungleTreeFeature5placeEP10TileSourceiiiR6Random|
|LeafTile::getResourceCount|No|(Random*)|IDK|_ZN8LeafTile16getResourceCountEP6Random|
|GravelTile::getResource|No|(int, Random*)|IDK|_ZN10GravelTile11getResourceEiP6Random|
|Item::flint|No|(undefined|IDK|_ZN4Item5flintE|
|OreTile::getResourceCount|No|(Random*)|IDK|_ZN7OreTile16getResourceCountEP6Random|
|RedStoneOreTile::getResourceCount|No|(Random*)|IDK|_ZN15RedStoneOreTile16getResourceCountEP6Random|
|ServerSideNetworkHandler::addMoveEntityPacket|No|(Entity const*)|IDK|_ZN24ServerSideNetworkHandler19addMoveEntityPacketEPK6Entity|
|Random::genrand_int32|No|()|IDK|_ZN6Random13genrand_int32Ev|
|SpruceFeature::place|No|(TileSource*, int, int, int, Random&) const|IDK|_ZNK13SpruceFeature5placeEP10TileSourceiiiR6Random|
|TreeFeature::prepareSpawn|No|(TileSource*, int, int, int, int) const|IDK|_ZNK11TreeFeature12prepareSpawnEP10TileSourceiiii|
|TreeFeature::_placeTrunk|No|(TileSource*, int, int, int, Random&, int) const|IDK|_ZNK11TreeFeature11_placeTrunkEP10TileSourceiiiR6Randomi|
|TreeFeature::placeLeaf|No|(TileSource*, int, int, int) const|IDK|_ZNK11TreeFeature9placeLeafEP10TileSourceiii|
|Tile::spawnResources|No|(TileSource*, int, int, int, int, float)|IDK|_ZN4Tile14spawnResourcesEP10TileSourceiiiif|
|ItemInstance::ItemInstance|No|(int, int, int)|IDK|_ZN12ItemInstanceC1Eiii|
|ItemEntity::ItemEntity|No|(TileSource*, float, float, float, ItemInstance const&)|IDK|_ZN10ItemEntityC1EP10TileSourcefffRK12ItemInstance|
|CropTile::spawnResources|No|(TileSource*, int, int, int, int, float)|IDK|_ZN8CropTile14spawnResourcesEP10TileSourceiiiif|
|ItemInstance::ItemInstance|No|(Item const*)|IDK|_ZN12ItemInstanceC1EPK4Item|
|PlainsBiome::getRandomFlowerTypeAndData|No|(Random&, TilePos const&)|IDK|_ZN11PlainsBiome26getRandomFlowerTypeAndDataER6RandomRK7TilePos|
|PerlinSimplexNoise::getValue|No|(float, float) const|IDK|_ZNK18PerlinSimplexNoise8getValueEff|
|Tile::redFlower|No|(undefined|IDK|_ZN4Tile9redFlowerE|
|Tile::yellowFlower|No|(undefined|IDK|_ZN4Tile12yellowFlowerE|
|Tile::SoundType::SoundType|No|(std::string const&, float, float)|IDK|_ZN4Tile9SoundTypeC2ERKSsff|
|Tile::SoundType::SoundType|No|(std::string const&, float, float)|IDK|_ZN4Tile9SoundTypeC1ERKSsff|
|Path::~Path|No|()|IDK|_ZN4PathD2Ev|
|Path::~Path|No|()|IDK|_ZN4PathD1Ev|
|PathfinderMob::~PathfinderMob|No|()|IDK|_ZN13PathfinderMobD2Ev|
|Mob::~Mob|No|()|IDK|_ZN3MobD2Ev|
|vtable for PathfinderMob|No|(undefined|IDK|_ZTV13PathfinderMob|
|PathfinderMob::~PathfinderMob|No|()|IDK|_ZN13PathfinderMobD1Ev|
|PathfinderMob::~PathfinderMob|No|()|IDK|_ZN13PathfinderMobD0Ev|
|Pig::~Pig|No|()|IDK|_ZN3PigD2Ev|
|vtable for AgableMob|No|(undefined|IDK|_ZTV9AgableMob|
|Pig::~Pig|No|()|IDK|_ZN3PigD1Ev|
|Pig::~Pig|No|()|IDK|_ZN3PigD0Ev|
|Villager::~Villager|No|()|IDK|_ZN8VillagerD2Ev|
|Villager::~Villager|No|()|IDK|_ZN8VillagerD1Ev|
|Villager::~Villager|No|()|IDK|_ZN8VillagerD0Ev|
|Spider::~Spider|No|()|IDK|_ZN6SpiderD2Ev|
|vtable for Monster|No|(undefined|IDK|_ZTV7Monster|
|Spider::~Spider|No|()|IDK|_ZN6SpiderD1Ev|
|Spider::~Spider|No|()|IDK|_ZN6SpiderD0Ev|
|Path::Path|No|(arrayWithLength<Node*>)|IDK|_ZN4PathC2E15arrayWithLengthIP4NodeE|
|operator new[]|No|(unsigned int)|IDK|_Znaj|
|Path::Path|No|(arrayWithLength<Node*>)|IDK|_ZN4PathC1E15arrayWithLengthIP4NodeE|
|Path::next|No|()|IDK|_ZN4Path4nextEv|
|Path::isDone|No|()|IDK|_ZN4Path6isDoneEv|
|Path::last|No|()|IDK|_ZN4Path4lastEv|
|Path::get|No|(int)|IDK|_ZN4Path3getEi|
|Path::getSize|No|()|IDK|_ZN4Path7getSizeEv|
|Path::setSize|No|(int)|IDK|_ZN4Path7setSizeEi|
|Path::getIndex|No|()|IDK|_ZN4Path8getIndexEv|
|Path::setIndex|No|(int)|IDK|_ZN4Path8setIndexEi|
|Path::getPos|No|(Entity const*, int)|IDK|_ZN4Path6getPosEPK6Entityi|
|Path::currentPos|No|(Entity const*)|IDK|_ZN4Path10currentPosEPK6Entity|
|Path::currentPos|No|()|IDK|_ZN4Path10currentPosEv|
|Path::sameAs|No|(Path*)|IDK|_ZN4Path6sameAsEPS_|
|Path::endsIn|No|(Vec3*)|IDK|_ZN4Path6endsInEP4Vec3|
|Path::endsInXZ|No|(Vec3*)|IDK|_ZN4Path8endsInXZEP4Vec3|
|StemTile::getConnectedTexture|No|()|IDK|_ZN8StemTile19getConnectedTextureEv|
|EatTileGoal::EatTileGoal|No|(Mob*)|IDK|_ZN11EatTileGoalC2EP3Mob|
|Goal::Goal|No|(Mob*)|IDK|_ZN4GoalC2EP3Mob|
|Goal::setRequiredControlFlags|No|(int)|IDK|_ZN4Goal23setRequiredControlFlagsEi|
|vtable for EatTileGoal|No|(undefined|IDK|_ZTV11EatTileGoal|
|EatTileGoal::EatTileGoal|No|(Mob*)|IDK|_ZN11EatTileGoalC1EP3Mob|
|Bounds::Bounds|No|(TilePos const&, TilePos const&, int, bool)|IDK|_ZN6BoundsC2ERK7TilePosS2_ib|
|Bounds::Bounds|No|(TilePos const&, TilePos const&, int, bool)|IDK|_ZN6BoundsC1ERK7TilePosS2_ib|
|TouchscreenInput::clear|No|()|IDK|_ZN16TouchscreenInput5clearEv|
|TouchscreenInput::~TouchscreenInput|No|()|IDK|_ZN16TouchscreenInputD2Ev|
|MeshBuffer::~MeshBuffer|No|()|IDK|_ZN10MeshBufferD1Ev|
|vtable for TouchscreenInput|No|(undefined|IDK|_ZTV16TouchscreenInput|
|TouchscreenInput::~TouchscreenInput|No|()|IDK|_ZN16TouchscreenInputD1Ev|
|non-virtual thunk to TouchscreenInput::~TouchscreenInput|No|()|IDK|_ZThn20_N16TouchscreenInputD1Ev|
|TouchscreenInput::~TouchscreenInput|No|()|IDK|_ZN16TouchscreenInputD0Ev|
|non-virtual thunk to TouchscreenInput::~TouchscreenInput|No|()|IDK|_ZThn20_N16TouchscreenInputD0Ev|
|TouchscreenInput::isButtonDown|No|(int)|IDK|_ZN16TouchscreenInput12isButtonDownEi|
|TouchscreenInput::getRectangleArea|No|()|IDK|_ZN16TouchscreenInput16getRectangleAreaEv|
|TouchscreenInput::getPauseRectangleArea|No|()|IDK|_ZN16TouchscreenInput21getPauseRectangleAreaEv|
|TouchscreenInput::drawRectangleArea|No|(Tesselator&, RectangleArea*, int, int, float)|IDK|_ZN16TouchscreenInput17drawRectangleAreaER10TesselatorP13RectangleAreaiif|
|Gui::InvGuiScale|No|(undefined|IDK|_ZN3Gui11InvGuiScaleE|
|TouchscreenInput::drawRectangleArea|No|(Tesselator&, RectangleArea*, int, int, float, float)|IDK|_ZN16TouchscreenInput17drawRectangleAreaER10TesselatorP13RectangleAreaiiff|
|TouchscreenInput::canInteract|No|()|IDK|_ZN16TouchscreenInput11canInteractEv|
|TouchscreenInput::tick|No|(Player*)|IDK|_ZN16TouchscreenInput4tickEP6Player|
|MouseDevice::getX|No|()|IDK|_ZN11MouseDevice4getXEv|
|MouseDevice::getY|No|()|IDK|_ZN11MouseDevice4getYEv|
|Multitouch::_activePointerThisUpdateCount|No|(undefined|IDK|_ZN10Multitouch29_activePointerThisUpdateCountE|
|Multitouch::_activePointerThisUpdateList|No|(undefined|IDK|_ZN10Multitouch28_activePointerThisUpdateListE|
|Multitouch::_pointers|No|(undefined|IDK|_ZN10Multitouch9_pointersE|
|Multitouch::_wasPressed|No|(undefined|IDK|_ZN10Multitouch11_wasPressedE|
|Multitouch::_wasReleased|No|(undefined|IDK|_ZN10Multitouch12_wasReleasedE|
|vtable for InteractPacket|No|(undefined|IDK|_ZTV14InteractPacket|
|TouchscreenInput::rebuild|No|()|IDK|_ZN16TouchscreenInput7rebuildEv|
|Tesselator::colorABGR|No|(int)|IDK|_ZN10Tesselator9colorABGREi|
|Font::width|No|(std::string const&)|IDK|_ZN4Font5widthERKSs|
|Font::height|No|(std::string const&, int)|IDK|_ZN4Font6heightERKSsi|
|Font::draw|No|(std::string const&, float, float, int)|IDK|_ZN4Font4drawERKSsffi|
|TouchscreenInput::render|No|(float)|IDK|_ZN16TouchscreenInput6renderEf|
|TouchscreenInput::allowPicking|No|(float, float)|IDK|_ZN16TouchscreenInput12allowPickingEff|
|DBChunkStorage::ChunkKey::ChunkKey|No|(ChunkPos const&)|IDK|_ZN14DBChunkStorage8ChunkKeyC2ERK8ChunkPos|
|DBChunkStorage::ChunkKey::ChunkKey|No|(ChunkPos const&)|IDK|_ZN14DBChunkStorage8ChunkKeyC1ERK8ChunkPos|
|DBChunkStorage::ChunkKey::ChunkKey|No|(LevelChunk const&)|IDK|_ZN14DBChunkStorage8ChunkKeyC2ERK10LevelChunk|
|DBChunkStorage::ChunkKey::ChunkKey|No|(LevelChunk const&)|IDK|_ZN14DBChunkStorage8ChunkKeyC1ERK10LevelChunk|
|DBChunkStorage::ChunkKey::asSlice|No|() const|IDK|_ZNK14DBChunkStorage8ChunkKey7asSliceEv|
|DBChunkStorage::DBChunkStorage|No|(ChunkSource*, DBStorage*)|IDK|_ZN14DBChunkStorageC2EP11ChunkSourceP9DBStorage|
|ChunkSource::ChunkSource|No|(ChunkSource*, bool)|IDK|_ZN11ChunkSourceC2EPS_b|
|AppPlatformListener::AppPlatformListener|No|()|IDK|_ZN19AppPlatformListenerC2Ev|
|MemoryTracker::MemoryTracker|No|(std::string const&, MemoryTracker*)|IDK|_ZN13MemoryTrackerC2ERKSsPS_|
|vtable for DBChunkStorage|No|(undefined|IDK|_ZTV14DBChunkStorage|
|DBChunkStorage::DBChunkStorage|No|(ChunkSource*, DBStorage*)|IDK|_ZN14DBChunkStorageC1EP11ChunkSourceP9DBStorage|
|DBChunkStorage::_writeBatch|No|()|IDK|_ZN14DBChunkStorage11_writeBatchEv|
|vtable for std::_Sp_counted_deleter<std::vector<std::unique_ptr<LevelChunk, std::default_delete<LevelChunk> >, std::allocator<std::unique_ptr<LevelChunk, std::default_delete<LevelChunk> > > >*, std::__shared_ptr<std::vector<std::unique_ptr<LevelChunk, std::default_delete<LevelChunk> >, std::allocator<std::unique_ptr<LevelChunk, std::default_delete<LevelChunk> > > >, |No|(__gnu_cxx::_Lock_policy)2>::_Deleter<std::allocator<std::vector<std::unique_ptr<LevelChunk, std::default_delete<LevelChunk> >, std::allocator<std::unique_ptr<LevelChunk, std::default_delete<LevelChunk> > > > > >, std::allocator<std::vector<std::unique_ptr<LevelChunk, std::default_delete<LevelChunk> >, std::allocator<std::unique_ptr<LevelChunk, std::default_delete<LevelChunk> > > > >, |IDK|_ZTVSt19_Sp_counted_deleterIPSt6vectorISt10unique_ptrI10LevelChunkSt14default_deleteIS2_EESaIS5_EENSt12__shared_ptrIS7_LN9__gnu_cxx12_Lock_policyE2EE8_DeleterISaIS7_EEESE_LSB_2EE|
|DBChunkStorage::hintDiscardBatchEnd|No|()|IDK|_ZN14DBChunkStorage19hintDiscardBatchEndEv|
|DBChunkStorage::_getBuffer|No|()|IDK|_ZN14DBChunkStorage10_getBufferEv|
|leveldb::WriteBatch::Clear|No|()|IDK|_ZN7leveldb10WriteBatch5ClearEv|
|vtable for std::_Sp_counted_ptr<leveldb::WriteBatch*, |No|(__gnu_cxx::_Lock_policy)2>|IDK|_ZTVSt15_Sp_counted_ptrIPN7leveldb10WriteBatchELN9__gnu_cxx12_Lock_policyE2EE|
|WolfModel::WolfModel|No|()|IDK|_ZN9WolfModelC2Ev|
|Model::Model|No|()|IDK|_ZN5ModelC2Ev|
|ModelPart::ModelPart|No|(int, int, int, int)|IDK|_ZN9ModelPartC1Eiiii|
|ModelPart::setModel|No|(Model*)|IDK|_ZN9ModelPart8setModelEP5Model|
|ModelPart::addBox|No|(float, float, float, int, int, int, float)|IDK|_ZN9ModelPart6addBoxEfffiiif|
|ModelPart::texOffs|No|(int, int)|IDK|_ZN9ModelPart7texOffsEii|
|WolfModel::WolfModel|No|()|IDK|_ZN9WolfModelC1Ev|
|ItemRenderer::ItemRenderer|No|()|IDK|_ZN12ItemRendererC2Ev|
|EntityRenderer::EntityRenderer|No|()|IDK|_ZN14EntityRendererC2Ev|
|ItemRenderer::inited|No|(undefined|IDK|_ZN12ItemRenderer6initedE|
|ItemRenderer::ItemRenderer|No|()|IDK|_ZN12ItemRendererC1Ev|
|ItemRenderer::teardown_static|No|()|IDK|_ZN12ItemRenderer15teardown_staticEv|
|ItemRenderer::tileRenderer|No|(undefined|IDK|_ZN12ItemRenderer12tileRendererE|
|ItemRenderer::getAtlasPos|No|(ItemInstance const*)|IDK|_ZN12ItemRenderer11getAtlasPosEPK12ItemInstance|
|ItemRenderer::fillRect|No|(Tesselator&, float, float, float, float, int)|IDK|_ZN12ItemRenderer8fillRectER10Tesselatorffffi|
|Tesselator::color|No|(int)|IDK|_ZN10Tesselator5colorEi|
|Tesselator::vertex|No|(float, float, float)|IDK|_ZN10Tesselator6vertexEfff|
|ItemRenderer::renderGuiItemDecorations|No|(ItemInstance const*, float, float)|IDK|_ZN12ItemRenderer24renderGuiItemDecorationsEPK12ItemInstanceff|
|ItemInstance::isDamaged|No|() const|IDK|_ZNK12ItemInstance9isDamagedEv|
|ItemInstance::getDamageValue|No|() const|IDK|_ZNK12ItemInstance14getDamageValueEv|
|ItemInstance::getMaxDamage|No|() const|IDK|_ZNK12ItemInstance12getMaxDamageEv|
|ItemRenderer::blit|No|(float, float, float, float, float, float)|IDK|_ZN12ItemRenderer4blitEffffff|
|ItemRenderer::renderGuiItemCorrect|No|(Font*, Textures*, ItemInstance const*, int, int)|IDK|_ZN12ItemRenderer20renderGuiItemCorrectEP4FontP8TexturesPK12ItemInstanceii|
|TileRenderer::renderGuiTile|No|(FullTile const&, float, float)|IDK|_ZN12TileRenderer13renderGuiTileERK8FullTileff|
|ItemRenderer::iconBlit|No|(float, float, TextureUVCoordinateSet const&, float, float, float, float, int, float)|IDK|_ZN12ItemRenderer8iconBlitEffRK22TextureUVCoordinateSetffffif|
|Tesselator::color|No|(float, float, float, float)|IDK|_ZN10Tesselator5colorEffff|
|ItemRenderer::renderGuiItemInChunk|No|(ItemRenderChunkType, Textures*, ItemInstance const*, float, float, float, float, float)|IDK|_ZN12ItemRenderer20renderGuiItemInChunkE19ItemRenderChunkTypeP8TexturesPK12ItemInstancefffff|
|Tesselator::scale3d|No|(float, float, float)|IDK|_ZN10Tesselator7scale3dEfff|
|Tesselator::tilt|No|()|IDK|_ZN10Tesselator4tiltEv|
|Tesselator::resetScale|No|()|IDK|_ZN10Tesselator10resetScaleEv|
|Tesselator::resetTilt|No|()|IDK|_ZN10Tesselator9resetTiltEv|
|ItemRenderer::renderGuiItemNew|No|(Textures*, ItemInstance const*, int, float, float, float, float, float)|IDK|_ZN12ItemRenderer16renderGuiItemNewEP8TexturesPK12ItemInstanceifffff|
|NetherReactorTile::allPlayersCloseToReactor|No|(Level*, int, int, int)|IDK|_ZN17NetherReactorTile24allPlayersCloseToReactorEP5Leveliii|
|NetherReactorTile::canSpawnStartNetherReactor|No|(Player*, int, int, int)|IDK|_ZN17NetherReactorTile26canSpawnStartNetherReactorEP6Playeriii|
|MonsterEggTile::isCompatibleHostBlock|No|(int, int)|IDK|_ZN14MonsterEggTile21isCompatibleHostBlockEii|
|MonsterEggTile::getDataForHostBlock|No|(int, int)|IDK|_ZN14MonsterEggTile19getDataForHostBlockEii|
|Cube::Cube|No|(ModelPart*, int, int, float, float, float, int, int, int, float)|IDK|_ZN4CubeC2EP9ModelPartiifffiiif|
|PolygonQuad::PolygonQuad|No|(VertexPT*, VertexPT*, VertexPT*, VertexPT*, int, int, int, int, int, int)|IDK|_ZN11PolygonQuadC1EP8VertexPTS1_S1_S1_iiiiii|
|PolygonQuad::mirror|No|()|IDK|_ZN11PolygonQuad6mirrorEv|
|Cube::Cube|No|(ModelPart*, int, int, float, float, float, int, int, int, float)|IDK|_ZN4CubeC1EP9ModelPartiifffiiif|
|Cube::compile|No|(Tesselator&, float)|IDK|_ZN4Cube7compileER10Tesselatorf|
|PolygonQuad::render|No|(Tesselator&, float)|IDK|_ZN11PolygonQuad6renderER10Tesselatorf|
|Cube::setId|No|(std::string const&)|IDK|_ZN4Cube5setIdERKSs|
|SmoothZoomLayer::SmoothZoomLayer|No|(long, std::shared_ptr<Layer>&)|IDK|_ZN15SmoothZoomLayerC2ElRSt10shared_ptrI5LayerE|
|Layer::Layer|No|(long long)|IDK|_ZN5LayerC2Ex|
|vtable for SmoothZoomLayer|No|(undefined|IDK|_ZTV15SmoothZoomLayer|
|SmoothZoomLayer::SmoothZoomLayer|No|(long, std::shared_ptr<Layer>&)|IDK|_ZN15SmoothZoomLayerC1ElRSt10shared_ptrI5LayerE|
|SmoothZoomLayer::zoom|No|(long, std::shared_ptr<Layer>&, int)|IDK|_ZN15SmoothZoomLayer4zoomElRSt10shared_ptrI5LayerEi|
|vtable for std::_Sp_counted_ptr<SmoothZoomLayer*, |No|(__gnu_cxx::_Lock_policy)2>|IDK|_ZTVSt15_Sp_counted_ptrIP15SmoothZoomLayerLN9__gnu_cxx12_Lock_policyE2EE|
|HangingEntity::setPosition|No|(int, int, int)|IDK|_ZN13HangingEntity11setPositionEiii|
|HangingEntity::init|No|()|IDK|_ZN13HangingEntity4initEv|
|HangingEntity::HangingEntity|No|(TileSource*)|IDK|_ZN13HangingEntityC2EP10TileSource|
|Entity::Entity|No|(TileSource*)|IDK|_ZN6EntityC2EP10TileSource|
|HangingEntity::HangingEntity|No|(TileSource*)|IDK|_ZN13HangingEntityC1EP10TileSource|
|HangingEntity::HangingEntity|No|(TileSource*, int, int, int, int)|IDK|_ZN13HangingEntityC2EP10TileSourceiiii|
|HangingEntity::HangingEntity|No|(TileSource*, int, int, int, int)|IDK|_ZN13HangingEntityC1EP10TileSourceiiii|
|HangingEntity::offs|No|(int)|IDK|_ZN13HangingEntity4offsEi|
|HangingEntity::setDir|No|(int)|IDK|_ZN13HangingEntity6setDirEi|
|Direction::DIRECTION_OPPOSITE|No|(undefined|IDK|_ZN9Direction18DIRECTION_OPPOSITEE|
|LevelChunk::operator new|No|(unsigned int)|IDK|_ZN10LevelChunknwEj|
|PoolAllocator::get|No|()|IDK|_ZN13PoolAllocator3getEv|
|LevelChunk::operator delete|No|(void*)|IDK|_ZN10LevelChunkdlEPv|
|PoolAllocator::release|No|(void*)|IDK|_ZN13PoolAllocator7releaseEPv|
|LevelChunk::trimMemoryPool|No|()|IDK|_ZN10LevelChunk14trimMemoryPoolEv|
|PoolAllocator::trim|No|()|IDK|_ZN13PoolAllocator4trimEv|
|LevelChunk::~LevelChunk|No|()|IDK|_ZN10LevelChunkD2Ev|
|LevelChunk::~LevelChunk|No|()|IDK|_ZN10LevelChunkD1Ev|
|std::_Sp_counted_deleter<std::vector<std::unique_ptr<LevelChunk, std::default_delete<LevelChunk> >, std::allocator<std::unique_ptr<LevelChunk, std::default_delete<LevelChunk> > > >*, std::__shared_ptr<std::vector<std::unique_ptr<LevelChunk, std::default_delete<LevelChunk> >, std::allocator<std::unique_ptr<LevelChunk, std::default_delete<LevelChunk> > > >, |No|(__gnu_cxx::_Lock_policy)2>::_Deleter<std::allocator<std::vector<std::unique_ptr<LevelChunk, std::default_delete<LevelChunk> >, std::allocator<std::unique_ptr<LevelChunk, std::default_delete<LevelChunk> > > > > >, std::allocator<std::vector<std::unique_ptr<LevelChunk, std::default_delete<LevelChunk> >, std::allocator<std::unique_ptr<LevelChunk, std::default_delete<LevelChunk> > > > >, |IDK|_ZNSt19_Sp_counted_deleterIPSt6vectorISt10unique_ptrI10LevelChunkSt14default_deleteIS2_EESaIS5_EENSt12__shared_ptrIS7_LN9__gnu_cxx12_Lock_policyE2EE8_DeleterISaIS7_EEESE_LSB_2EE10_M_disposeEv|
|ChunkCache::ChunkCache|No|(ChunkSource*)|IDK|_ZN10ChunkCacheC2EP11ChunkSource|
|vtable for ChunkCache|No|(undefined|IDK|_ZTV10ChunkCache|
|ChunkCache::ChunkCache|No|(ChunkSource*)|IDK|_ZN10ChunkCacheC1EP11ChunkSource|
|ChunkCache::~ChunkCache|No|()|IDK|_ZN10ChunkCacheD2Ev|
|ChunkCache::~ChunkCache|No|()|IDK|_ZN10ChunkCacheD1Ev|
|non-virtual thunk to ChunkCache::~ChunkCache|No|()|IDK|_ZThn20_N10ChunkCacheD1Ev|
|ChunkCache::~ChunkCache|No|()|IDK|_ZN10ChunkCacheD0Ev|
|non-virtual thunk to ChunkCache::~ChunkCache|No|()|IDK|_ZThn20_N10ChunkCacheD0Ev|
|WorldLimitChunkSource::~WorldLimitChunkSource|No|()|IDK|_ZN21WorldLimitChunkSourceD2Ev|
|vtable for WorldLimitChunkSource|No|(undefined|IDK|_ZTV21WorldLimitChunkSource|
|WorldLimitChunkSource::~WorldLimitChunkSource|No|()|IDK|_ZN21WorldLimitChunkSourceD1Ev|
|WorldLimitChunkSource::~WorldLimitChunkSource|No|()|IDK|_ZN21WorldLimitChunkSourceD0Ev|
|DBChunkStorage::~DBChunkStorage|No|()|IDK|_ZN14DBChunkStorageD2Ev|
|BackgroundQueuePool::getQueuesFor|No|(QueueRole)|IDK|_ZN19BackgroundQueuePool12getQueuesForE9QueueRole|
|BackgroundQueue::sync|No|()|IDK|_ZN15BackgroundQueue4syncEv|
|MemoryTracker::~MemoryTracker|No|()|IDK|_ZN13MemoryTrackerD2Ev|
|DBChunkStorage::~DBChunkStorage|No|()|IDK|_ZN14DBChunkStorageD1Ev|
|non-virtual thunk to DBChunkStorage::~DBChunkStorage|No|()|IDK|_ZThn20_N14DBChunkStorageD1Ev|
|non-virtual thunk to DBChunkStorage::~DBChunkStorage|No|()|IDK|_ZThn24_N14DBChunkStorageD1Ev|
|DBChunkStorage::~DBChunkStorage|No|()|IDK|_ZN14DBChunkStorageD0Ev|
|non-virtual thunk to DBChunkStorage::~DBChunkStorage|No|()|IDK|_ZThn20_N14DBChunkStorageD0Ev|
|non-virtual thunk to DBChunkStorage::~DBChunkStorage|No|()|IDK|_ZThn24_N14DBChunkStorageD0Ev|
|LevelChunk::_resetDirtyCounter|No|(int&, int)|IDK|_ZN10LevelChunk18_resetDirtyCounterERii|
|_needsToCreateTileEntity|No|(Tile*, Tile*)|IDK|_Z24_needsToCreateTileEntityP4TileS0_|
|_needsToRemoveTileEntity|No|(Tile*, Tile*)|IDK|_Z24_needsToRemoveTileEntityP4TileS0_|
|LevelChunk::recalcHeightmap|No|()|IDK|_ZN10LevelChunk15recalcHeightmapEv|
|LevelChunk::isAt|No|(int, int)|IDK|_ZN10LevelChunk4isAtEii|
|LevelChunk::getHeightmap|No|(ChunkTilePos const&) const|IDK|_ZNK10LevelChunk12getHeightmapERK12ChunkTilePos|
|LevelChunk::recalcBlockLights|No|()|IDK|_ZN10LevelChunk17recalcBlockLightsEv|
|LevelChunk::setData|No|(ChunkTilePos const&, int)|IDK|_ZN10LevelChunk7setDataERK12ChunkTilePosi|
|LevelChunk::getBrightness|No|(LightLayer const&, ChunkTilePos const&)|IDK|_ZN10LevelChunk13getBrightnessERK10LightLayerRK12ChunkTilePos|
|LightLayer::Sky|No|(undefined|IDK|_ZN10LightLayer3SkyE|
|LightLayer::Block|No|(undefined|IDK|_ZN10LightLayer5BlockE|
|LevelChunk::setBrightness|No|(LightLayer const&, ChunkTilePos const&, unsigned char)|IDK|_ZN10LevelChunk13setBrightnessERK10LightLayerRK12ChunkTilePosh|
|LevelChunk::getRawBrightness|No|(ChunkTilePos const&, unsigned char)|IDK|_ZN10LevelChunk16getRawBrightnessERK12ChunkTilePosh|
|LevelChunk::hasEntity|No|(Entity&)|IDK|_ZN10LevelChunk9hasEntityER6Entity|
|LevelChunk::removeEntity|No|(Entity&)|IDK|_ZN10LevelChunk12removeEntityER6Entity|
|LevelChunk::isSkyLit|No|(ChunkTilePos const&)|IDK|_ZN10LevelChunk8isSkyLitERK12ChunkTilePos|
|LevelChunk::tryChangeState|No|(ChunkState, ChunkState)|IDK|_ZN10LevelChunk14tryChangeStateE10ChunkStateS0_|
|LevelChunk::changeState|No|(ChunkState, ChunkState)|IDK|_ZN10LevelChunk11changeStateE10ChunkStateS0_|
|LevelChunk::getTileEntity|No|(ChunkTilePos const&)|IDK|_ZN10LevelChunk13getTileEntityERK12ChunkTilePos|
|TileEntity::isRemoved|No|() const|IDK|_ZNK10TileEntity9isRemovedEv|
|LevelChunk::hasTileEntity|No|(ChunkTilePos const&)|IDK|_ZN10LevelChunk13hasTileEntityERK12ChunkTilePos|
|LevelChunk::getTileEntityMap|No|() const|IDK|_ZNK10LevelChunk16getTileEntityMapEv|
|LevelChunk::serializeTerrain|No|(IDataOutput&) const|IDK|_ZNK10LevelChunk16serializeTerrainER11IDataOutput|
|LevelChunk::deserializeTerrain|No|(IDataInput&)|IDK|_ZN10LevelChunk18deserializeTerrainER10IDataInput|
|LevelChunk::needsTerrainSave|No|(int) const|IDK|_ZNK10LevelChunk16needsTerrainSaveEi|
|LevelChunk::needsTileEntitySave|No|(int) const|IDK|_ZNK10LevelChunk19needsTileEntitySaveEi|
|LevelChunk::needsEntitySave|No|(int) const|IDK|_ZNK10LevelChunk15needsEntitySaveEi|
|MainChunkSource::onAppSuspended|No|()|IDK|_ZN15MainChunkSource14onAppSuspendedEv|
|non-virtual thunk to MainChunkSource::onAppSuspended|No|()|IDK|_ZThn20_N15MainChunkSource14onAppSuspendedEv|
|LevelChunk::getBiome|No|(ChunkTilePos const&)|IDK|_ZN10LevelChunk8getBiomeERK12ChunkTilePos|
|Biome::getBiome|No|(int)|IDK|_ZN5Biome8getBiomeEi|
|LevelChunk::setBiome|No|(Biome const&, ChunkTilePos const&)|IDK|_ZN10LevelChunk8setBiomeERK5BiomeRK12ChunkTilePos|
|LevelChunk::setGrassColor|No|(int, ChunkTilePos const&)|IDK|_ZN10LevelChunk13setGrassColorEiRK12ChunkTilePos|
|LevelChunk::getGrassColor|No|(ChunkTilePos const&)|IDK|_ZN10LevelChunk13getGrassColorERK12ChunkTilePos|
|LevelChunk::findHighestNonEmptyTile|No|(ChunkTilePos const&) const|IDK|_ZNK10LevelChunk23findHighestNonEmptyTileERK12ChunkTilePos|
|LevelChunk::findHighestNonEmptyTile|No|() const|IDK|_ZNK10LevelChunk23findHighestNonEmptyTileEv|
|LevelChunk::setPendingEntities|No|(std::string&)|IDK|_ZN10LevelChunk18setPendingEntitiesERSs|
|LevelChunk::setUnsaved|No|()|IDK|_ZN10LevelChunk10setUnsavedEv|
|LevelChunk::setSaved|No|()|IDK|_ZN10LevelChunk8setSavedEv|
|LevelChunk::onTilesChanged|No|()|IDK|_ZN10LevelChunk14onTilesChangedEv|
|LevelChunk::onTileEntityChanged|No|()|IDK|_ZN10LevelChunk19onTileEntityChangedEv|
|LevelChunk::needsUpgradeFix|No|() const|IDK|_ZNK10LevelChunk15needsUpgradeFixEv|
|getRawTimeS|No|()|IDK|_Z11getRawTimeSv|
|getTimeS|No|()|IDK|_Z8getTimeSv|
|Stopwatch::stop|No|()|IDK|_ZN9Stopwatch4stopEv|
|Stopwatch::stopContinue|No|()|IDK|_ZN9Stopwatch12stopContinueEv|
|getTimeMs|No|()|IDK|_Z9getTimeMsv|
|sleepMs|No|(int)|IDK|_Z7sleepMsi|
|getEpochTimeS|No|()|IDK|_Z13getEpochTimeSv|
|Stopwatch::start|No|()|IDK|_ZN9Stopwatch5startEv|
|Stopwatch::getLast|No|()|IDK|_ZN9Stopwatch7getLastEv|
|StopwatchNLast::stop|No|()|IDK|_ZN14StopwatchNLast4stopEv|
|Stopwatch::getTotal|No|()|IDK|_ZN9Stopwatch8getTotalEv|
|Stopwatch::getMax|No|()|IDK|_ZN9Stopwatch6getMaxEv|
|StopwatchNLast::print|No|(std::string const&)|IDK|_ZN14StopwatchNLast5printERKSs|
|Stopwatch::getCount|No|()|IDK|_ZN9Stopwatch8getCountEv|
|Stopwatch::reset|No|()|IDK|_ZN9Stopwatch5resetEv|
|Stopwatch::Stopwatch|No|()|IDK|_ZN9StopwatchC2Ev|
|Stopwatch::Stopwatch|No|()|IDK|_ZN9StopwatchC1Ev|
|StopwatchNLast::StopwatchNLast|No|(int)|IDK|_ZN14StopwatchNLastC2Ei|
|StopwatchNLast::StopwatchNLast|No|(int)|IDK|_ZN14StopwatchNLastC1Ei|
|Stopwatch::printEvery|No|(int, std::string const&)|IDK|_ZN9Stopwatch10printEveryEiRKSs|
|StopwatchHandler::print|No|()|IDK|_ZN16StopwatchHandler5printEv|
|StopwatchHandler::printEvery|No|(int)|IDK|_ZN16StopwatchHandler10printEveryEi|
|TickNextTickData::TickNextTickData|No|(TileSource*, TilePos const&, int, long)|IDK|_ZN16TickNextTickDataC2EP10TileSourceRK7TilePosil|
|TickNextTickData::TickNextTickData|No|(TileSource*, TilePos const&, int, long)|IDK|_ZN16TickNextTickDataC1EP10TileSourceRK7TilePosil|
|TickNextTickData::operator==|No|(TickNextTickData const&) const|IDK|_ZNK16TickNextTickDataeqERKS_|
|TickNextTickData::operator<|No|(TickNextTickData const&) const|IDK|_ZNK16TickNextTickDataltERKS_|
|TickNextTickData::operator>|No|(TickNextTickData const&) const|IDK|_ZNK16TickNextTickDatagtERKS_|
|TickNextTickData::getLevel|No|() const|IDK|_ZNK16TickNextTickData8getLevelEv|
|TickNextTickData::getRandom|No|() const|IDK|_ZNK16TickNextTickData9getRandomEv|
|BiomeDecorator::_placeFeature|No|(TileSource*, std::unique_ptr<Feature, std::default_delete<Feature> > const&, TilePos const&, Random&)|IDK|_ZN14BiomeDecorator13_placeFeatureEP10TileSourceRKSt10unique_ptrI7FeatureSt14default_deleteIS3_EERK7TilePosR6Random|
|BiomeDecorator::decorateDepthSpan|No|(TileSource*, Random&, TilePos const&, int, std::unique_ptr<Feature, std::default_delete<Feature> >&, int, int)|IDK|_ZN14BiomeDecorator17decorateDepthSpanEP10TileSourceR6RandomRK7TilePosiRSt10unique_ptrI7FeatureSt14default_deleteIS8_EEii|
|BiomeDecorator::decorateDepthAverage|No|(TileSource*, Random&, TilePos const&, int, std::unique_ptr<Feature, std::default_delete<Feature> >&, int, int)|IDK|_ZN14BiomeDecorator20decorateDepthAverageEP10TileSourceR6RandomRK7TilePosiRSt10unique_ptrI7FeatureSt14default_deleteIS8_EEii|
|BiomeDecorator::decorateOres|No|(TileSource*, Random&, TilePos const&)|IDK|_ZN14BiomeDecorator12decorateOresEP10TileSourceR6RandomRK7TilePos|
|Touch::IngameBlockSelectionScreen::IngameBlockSelectionScreen|No|()|IDK|_ZN5Touch26IngameBlockSelectionScreenC2Ev|
|GuiComponent::GuiComponent|No|()|IDK|_ZN12GuiComponentC2Ev|
|Touch::THeader::THeader|No|(int, std::string const&)|IDK|_ZN5Touch7THeaderC1EiRKSs|
|Touch::TButton::TButton|No|(int, std::string const&, Minecraft*, bool)|IDK|_ZN5Touch7TButtonC1EiRKSsP9Minecraftb|
|vtable for Screen|No|(undefined|IDK|_ZTV6Screen|
|vtable for Touch::IngameBlockSelectionScreen|No|(undefined|IDK|_ZTVN5Touch26IngameBlockSelectionScreenE|
|Touch::IngameBlockSelectionScreen::IngameBlockSelectionScreen|No|()|IDK|_ZN5Touch26IngameBlockSelectionScreenC1Ev|
|Touch::IngameBlockSelectionScreen::getSlotPosX|No|(int)|IDK|_ZN5Touch26IngameBlockSelectionScreen11getSlotPosXEi|
|Touch::IngameBlockSelectionScreen::getSlotPosY|No|(int)|IDK|_ZN5Touch26IngameBlockSelectionScreen11getSlotPosYEi|
|Touch::IngameBlockSelectionScreen::renderDemoOverlay|No|()|IDK|_ZN5Touch26IngameBlockSelectionScreen17renderDemoOverlayEv|
|Minecart::createMinecart|No|(TileSource*, float, float, float, int)|IDK|_ZN8Minecart14createMinecartEP10TileSourcefffi|
|MinecartRideable::MinecartRideable|No|(TileSource*, float, float, float)|IDK|_ZN16MinecartRideableC1EP10TileSourcefff|
|Minecart::destroy|No|(Entity*)|IDK|_ZN8Minecart7destroyEP6Entity|
|ItemInstance::ItemInstance|No|(Item const*, int)|IDK|_ZN12ItemInstanceC1EPK4Itemi|
|Item::minecart|No|(undefined|IDK|_ZN4Item8minecartE|
|Minecart::getDamage|No|()|IDK|_ZN8Minecart9getDamageEv|
|SynchedEntityData::getFloat|No|(int) const|IDK|_ZNK17SynchedEntityData8getFloatEi|
|Minecart::getHurtTime|No|()|IDK|_ZN8Minecart11getHurtTimeEv|
|SynchedEntityData::getInt|No|(int) const|IDK|_ZNK17SynchedEntityData6getIntEi|
|Minecart::getHurtDir|No|()|IDK|_ZN8Minecart10getHurtDirEv|
|Minecart::getDefaultDisplayTile|No|()|IDK|_ZN8Minecart21getDefaultDisplayTileEv|
|Minecart::getDefaultDisplayData|No|()|IDK|_ZN8Minecart21getDefaultDisplayDataEv|
|Minecart::getDefaultDisplayOffset|No|()|IDK|_ZN8Minecart23getDefaultDisplayOffsetEv|
|Minecart::hasCustomDisplay|No|()|IDK|_ZN8Minecart16hasCustomDisplayEv|
|SynchedEntityData::getByte|No|(int) const|IDK|_ZNK17SynchedEntityData7getByteEi|
|Minecart::getDisplayTile|No|()|IDK|_ZN8Minecart14getDisplayTileEv|
|Minecart::getDisplayData|No|()|IDK|_ZN8Minecart14getDisplayDataEv|
|Minecart::getDisplayOffset|No|()|IDK|_ZN8Minecart16getDisplayOffsetEv|
|Minecart::setCustomName|No|(std::string const&)|IDK|_ZN8Minecart13setCustomNameERKSs|
|Minecart::getAName|No|()|IDK|_ZN8Minecart8getANameEv|
|Minecart::hasCustomName|No|()|IDK|_ZN8Minecart13hasCustomNameEv|
|Minecart::getCustomName|No|()|IDK|_ZN8Minecart13getCustomNameEv|
|Minecart::comeOffTrack|No|(float)|IDK|_ZN8Minecart12comeOffTrackEf|
|Minecart::applyNaturalSlowdown|No|()|IDK|_ZN8Minecart20applyNaturalSlowdownEv|
|GuiElementContainer::getChildren|No|()|IDK|_ZN19GuiElementContainer11getChildrenEv|
|AvoidMobTypeGoal::AvoidMobTypeGoal|No|(PathfinderMob*, int, float, float, float)|IDK|_ZN16AvoidMobTypeGoalC2EP13PathfinderMobifff|
|AvoidMobTypeGoal::AvoidMobTypeGoal|No|(PathfinderMob*, int, float, float, float)|IDK|_ZN16AvoidMobTypeGoalC1EP13PathfinderMobifff|
|Villager::getProfession|No|()|IDK|_ZN8Villager13getProfessionEv|
|ParticleEngine::ParticleEngine|No|(Level*, Textures*)|IDK|_ZN14ParticleEngineC2EP5LevelP8Textures|
|ParticleEngine::ParticleEngine|No|(Level*, Textures*)|IDK|_ZN14ParticleEngineC1EP5LevelP8Textures|
|ParticleEngine::_get|No|(ParticleType)|IDK|_ZN14ParticleEngine4_getE12ParticleType|
|ParticleEngine::_release|No|(Particle*)|IDK|_ZN14ParticleEngine8_releaseEP8Particle|
|ParticleEngine::tick|No|()|IDK|_ZN14ParticleEngine4tickEv|
|ParticleEngine::renderParticleLayer|No|(bool, float, float, float, float, float, float)|IDK|_ZN14ParticleEngine19renderParticleLayerEbffffff|
|ParticleEngine::render|No|(Entity*, float)|IDK|_ZN14ParticleEngine6renderEP6Entityf|
|Particle::playerViewDir|No|(undefined|IDK|_ZN8Particle13playerViewDirE|
|ParticleEngine::countParticles|No|()|IDK|_ZN14ParticleEngine14countParticlesEv|
|ParticleEngine::clear|No|()|IDK|_ZN14ParticleEngine5clearEv|
|ParticleEngine::setLevel|No|(Level*)|IDK|_ZN14ParticleEngine8setLevelEP5Level|
|ParticleEngine::~ParticleEngine|No|()|IDK|_ZN14ParticleEngineD2Ev|
|ParticleEngine::~ParticleEngine|No|()|IDK|_ZN14ParticleEngineD1Ev|
|Vec3::Vec3|No|(TilePos const&)|IDK|_ZN4Vec3C2ERK7TilePos|
|Vec3::Vec3|No|(TilePos const&)|IDK|_ZN4Vec3C1ERK7TilePos|
|OptionsGroup::createTextBox|No|(Options::Option const*, Minecraft*)|IDK|_ZN12OptionsGroup13createTextBoxEPKN7Options6OptionEP9Minecraft|
|TextBox::TextBox|No|(Minecraft*, Options::Option const*, std::string const&)|IDK|_ZN7TextBoxC1EP9MinecraftPKN7Options6OptionERKSs|
|TextBox::setValidChars|No|(char const*, unsigned int)|IDK|_ZN7TextBox13setValidCharsEPKcj|
|vtable for std::_Sp_counted_ptr<TextBox*, |No|(__gnu_cxx::_Lock_policy)2>|IDK|_ZTVSt15_Sp_counted_ptrIP7TextBoxLN9__gnu_cxx12_Lock_policyE2EE|
|TextBox::extendedAcsii|No|(undefined|IDK|_ZN7TextBox13extendedAcsiiE|
|OptionsGroup::addOptionItem|No|(Options::Option const*, Minecraft*)|IDK|_ZN12OptionsGroup13addOptionItemEPKN7Options6OptionEP9Minecraft|
|Options::hideOption|No|(Options::Option const*)|IDK|_ZN7Options10hideOptionEPKNS_6OptionE|
|OptionsGroup::addLoginItem|No|(Minecraft*)|IDK|_ZN12OptionsGroup12addLoginItemEP9Minecraft|
|LoginOption::LoginOption|No|(Minecraft*)|IDK|_ZN11LoginOptionC1EP9Minecraft|
|vtable for std::_Sp_counted_ptr<LoginOption*, |No|(__gnu_cxx::_Lock_policy)2>|IDK|_ZTVSt15_Sp_counted_ptrIP11LoginOptionLN9__gnu_cxx12_Lock_policyE2EE|
|GuiElement::GuiElement|No|(bool, bool, int, int, int, int)|IDK|_ZN10GuiElementC2Ebbiiii|
|GuiElement::GuiElement|No|(bool, bool, int, int, int, int)|IDK|_ZN10GuiElementC1Ebbiiii|
|GuiElementContainer::GuiElementContainer|No|(bool, bool, int, int, int, int)|IDK|_ZN19GuiElementContainerC2Ebbiiii|
|GuiElementContainer::GuiElementContainer|No|(bool, bool, int, int, int, int)|IDK|_ZN19GuiElementContainerC1Ebbiiii|
|OptionsGroup::OptionsGroup|No|(std::string)|IDK|_ZN12OptionsGroupC2ESs|
|OptionsGroup::OptionsGroup|No|(std::string)|IDK|_ZN12OptionsGroupC1ESs|
|GuiElement::setVisible|No|(bool)|IDK|_ZN10GuiElement10setVisibleEb|
|GuiElement::clearBackground|No|()|IDK|_ZN10GuiElement15clearBackgroundEv|
|GuiElement::setBackground|No|(unsigned int)|IDK|_ZN10GuiElement13setBackgroundEj|
|GuiElement::setBackground|No|(Minecraft*, std::string const&, IntRectangle const&, int, int)|IDK|_ZN10GuiElement13setBackgroundEP9MinecraftRKSsRK12IntRectangleii|
|NinePatchFactory::NinePatchFactory|No|(Textures*, std::string const&)|IDK|_ZN16NinePatchFactoryC1EP8TexturesRKSs|
|NinePatchFactory::createSymmetrical|No|(IntRectangle const&, int, int, float, float)|IDK|_ZN16NinePatchFactory17createSymmetricalERK12IntRectangleiiff|
|GuiElement::setActiveAndVisibility|No|(bool, bool)|IDK|_ZN10GuiElement22setActiveAndVisibilityEbb|
|GuiElement::setActiveAndVisibility|No|(bool)|IDK|_ZN10GuiElement22setActiveAndVisibilityEb|
|GuiElement::isSelected|No|()|IDK|_ZN10GuiElement10isSelectedEv|
|GuiElement::setSelected|No|(bool)|IDK|_ZN10GuiElement11setSelectedEb|
|ImageButton::render|No|(Minecraft*, int, int)|IDK|_ZN11ImageButton6renderEP9Minecraftii|
|GuiComponent::drawCenteredString|No|(Font*, std::string const&, int, int, int)|IDK|_ZN12GuiComponent18drawCenteredStringEP4FontRKSsiii|
|Textures::getTextureData|No|(std::string const&)|IDK|_ZN8Textures14getTextureDataERKSs|
|CreativeInventoryScreen::updateTabButtonSelection|No|()|IDK|_ZN23CreativeInventoryScreen24updateTabButtonSelectionEv|
|WeighedTreasureItem::addChestItems|No|(Random&, std::vector<WeighedTreasureItem, std::allocator<WeighedTreasureItem> > const&, FillingContainer*, int)|IDK|_ZN19WeighedTreasureItem13addChestItemsER6RandomRKSt6vectorIS_SaIS_EEP16FillingContaineri|
|Mth::nextInt|No|(Random&, int, int)|IDK|_ZN3Mth7nextIntER6Randomii|
|ItemInstance::getMaxStackSize|No|() const|IDK|_ZNK12ItemInstance15getMaxStackSizeEv|
|ItemInstance::clone|No|(ItemInstance const*)|IDK|_ZN12ItemInstance5cloneEPKS_|
|EntityTileRenderer::render|No|(Tile*, int, float)|IDK|_ZN18EntityTileRenderer6renderEP4Tileif|
|TileEntityRenderDispatcher::getInstance|No|()|IDK|_ZN26TileEntityRenderDispatcher11getInstanceEv|
|TileEntityRenderDispatcher::render|No|(TileEntity&, Vec3 const&, float)|IDK|_ZN26TileEntityRenderDispatcher6renderER10TileEntityRK4Vec3f|
|TextureUVCoordinateSet::fix|No|()|IDK|_ZN22TextureUVCoordinateSet3fixEv|
|TextureUVCoordinateSet::TextureUVCoordinateSet|No|(float, float, float, float, float, float, int, TextureFile)|IDK|_ZN22TextureUVCoordinateSetC2Effffffi11TextureFile|
|TextureUVCoordinateSet::TextureUVCoordinateSet|No|(float, float, float, float, float, float, int, TextureFile)|IDK|_ZN22TextureUVCoordinateSetC1Effffffi11TextureFile|
|RedDustParticle::normalTick|No|()|IDK|_ZN15RedDustParticle10normalTickEv|
|SmokeParticle::render|No|(Tesselator&, float, float, float, float, float, float)|IDK|_ZN13SmokeParticle6renderER10Tesselatorffffff|
|ExplodeParticle::normalTick|No|()|IDK|_ZN15ExplodeParticle10normalTickEv|
|TextureUVCoordinateSet::TextureUVCoordinateSet|No|()|IDK|_ZN22TextureUVCoordinateSetC2Ev|
|TextureUVCoordinateSet::TextureUVCoordinateSet|No|()|IDK|_ZN22TextureUVCoordinateSetC1Ev|
|ParticleEngine::create|No|(ParticleType)|IDK|_ZN14ParticleEngine6createE12ParticleType|
|Level::getLocalPlayer|No|()|IDK|_ZN5Level14getLocalPlayerEv|
|Particle::Particle|No|(TileSource*, ParticleType, std::string const&)|IDK|_ZN8ParticleC2EP10TileSource12ParticleTypeRKSs|
|Entity::setSize|No|(float, float)|IDK|_ZN6Entity7setSizeEff|
|SplashParticle::SplashParticle|No|(TileSource*, ParticleType)|IDK|_ZN14SplashParticleC1EP10TileSource12ParticleType|
|Particle::PARTICLE_ATLAS|No|(undefined|IDK|_ZN8Particle14PARTICLE_ATLASE|
|vtable for DripParticle|No|(undefined|IDK|_ZTV12DripParticle|
|vtable for BubbleParticle|No|(undefined|IDK|_ZTV14BubbleParticle|
|vtable for CritParticle2|No|(undefined|IDK|_ZTV13CritParticle2|
|vtable for SmokeParticle|No|(undefined|IDK|_ZTV13SmokeParticle|
|vtable for ExplodeParticle|No|(undefined|IDK|_ZTV15ExplodeParticle|
|vtable for FlameParticle|No|(undefined|IDK|_ZTV13FlameParticle|
|vtable for LavaParticle|No|(undefined|IDK|_ZTV12LavaParticle|
|vtable for RedDustParticle|No|(undefined|IDK|_ZTV15RedDustParticle|
|Particle::ITEMS_ATLAS|No|(undefined|IDK|_ZN8Particle11ITEMS_ATLASE|
|vtable for BreakingItemParticle|No|(undefined|IDK|_ZTV20BreakingItemParticle|
|MobFlameParticle::FLAME_ATLAS|No|(undefined|IDK|_ZN16MobFlameParticle11FLAME_ATLASE|
|vtable for MobFlameParticle|No|(undefined|IDK|_ZTV16MobFlameParticle|
|vtable for HeartParticle|No|(undefined|IDK|_ZTV13HeartParticle|
|Particle::TERRAIN_ATLAS|No|(undefined|IDK|_ZN8Particle13TERRAIN_ATLASE|
|vtable for TerrainParticle|No|(undefined|IDK|_ZTV15TerrainParticle|
|vtable for SuspendedTownParticle|No|(undefined|IDK|_ZTV21SuspendedTownParticle|
|vtable for PortalParticle|No|(undefined|IDK|_ZTV14PortalParticle|
|Pig::hasSaddle|No|()|IDK|_ZN3Pig9hasSaddleEv|
|RiverInitLayer::RiverInitLayer|No|(long, std::shared_ptr<Layer>&)|IDK|_ZN14RiverInitLayerC2ElRSt10shared_ptrI5LayerE|
|vtable for RiverInitLayer|No|(undefined|IDK|_ZTV14RiverInitLayer|
|RiverInitLayer::RiverInitLayer|No|(long, std::shared_ptr<Layer>&)|IDK|_ZN14RiverInitLayerC1ElRSt10shared_ptrI5LayerE|
|BaseContainerMenu::BaseContainerMenu|No|(int)|IDK|_ZN17BaseContainerMenuC2Ei|
|BaseContainerMenu::BaseContainerMenu|No|(int)|IDK|_ZN17BaseContainerMenuC1Ei|
|FurnaceMenu::FurnaceMenu|No|(FurnaceTileEntity*)|IDK|_ZN11FurnaceMenuC2EP17FurnaceTileEntity|
|vtable for FurnaceMenu|No|(undefined|IDK|_ZTV11FurnaceMenu|
|FurnaceMenu::FurnaceMenu|No|(FurnaceTileEntity*)|IDK|_ZN11FurnaceMenuC1EP17FurnaceTileEntity|
|LiquidTile::getHeightFromData|No|(int)|IDK|_ZN10LiquidTile17getHeightFromDataEi|
|LiquidTile::fizz|No|(Level*, int, int, int)|IDK|_ZN10LiquidTile4fizzEP5Leveliii|
|Level::playSound|No|(float, float, float, std::string const&, float, float)|IDK|_ZN5Level9playSoundEfffRKSsff|
|PlainsBiome::PlainsBiome|No|(int)|IDK|_ZN11PlainsBiomeC2Ei|
|Biome::Biome|No|(int, Biome::BiomeType)|IDK|_ZN5BiomeC2EiNS_9BiomeTypeE|
|Biome::setTemperatureAndDownfall|No|(float, float)|IDK|_ZN5Biome25setTemperatureAndDownfallEff|
|Biome::setDepthAndScale|No|(Biome::BiomeHeight const&)|IDK|_ZN5Biome16setDepthAndScaleERKNS_11BiomeHeightE|
|Biome::HEIGHTS_LOWLANDS|No|(undefined|IDK|_ZN5Biome16HEIGHTS_LOWLANDSE|
|PlainsBiome::PlainsBiome|No|(int)|IDK|_ZN11PlainsBiomeC1Ei|
|PlainsBiome::createMutatedCopy|No|(int)|IDK|_ZN11PlainsBiome17createMutatedCopyEi|
|Biome::setName|No|(std::string const&)|IDK|_ZN5Biome7setNameERKSs|
|LeafTile::setFancy|No|(bool)|IDK|_ZN8LeafTile8setFancyEb|
|ZoomLayer::ZoomLayer|No|(long, std::shared_ptr<Layer>)|IDK|_ZN9ZoomLayerC2ElSt10shared_ptrI5LayerE|
|vtable for ZoomLayer|No|(undefined|IDK|_ZTV9ZoomLayer|
|ZoomLayer::ZoomLayer|No|(long, std::shared_ptr<Layer>)|IDK|_ZN9ZoomLayerC1ElSt10shared_ptrI5LayerE|
|ZoomLayer::zoom|No|(long, std::shared_ptr<Layer>&, int)|IDK|_ZN9ZoomLayer4zoomElRSt10shared_ptrI5LayerEi|
|vtable for std::_Sp_counted_ptr<ZoomLayer*, |No|(__gnu_cxx::_Lock_policy)2>|IDK|_ZTVSt15_Sp_counted_ptrIP9ZoomLayerLN9__gnu_cxx12_Lock_policyE2EE|
|PathfinderMob::PathfinderMob|No|(TileSource*)|IDK|_ZN13PathfinderMobC2EP10TileSource|
|Mob::Mob|No|(TileSource*)|IDK|_ZN3MobC2EP10TileSource|
|PathfinderMob::PathfinderMob|No|(TileSource*)|IDK|_ZN13PathfinderMobC1EP10TileSource|
|PathfinderMob::isPathFinding|No|()|IDK|_ZN13PathfinderMob13isPathFindingEv|
|PathfinderMob::setPath|No|(Path*)|IDK|_ZN13PathfinderMob7setPathEP4Path|
|PathfinderMob::findRandomStrollLocation|No|()|IDK|_ZN13PathfinderMob24findRandomStrollLocationEv|
|Level::findPath|No|(Entity*, int, int, int, float, bool, bool, bool, bool)|IDK|_ZN5Level8findPathEP6Entityiiifbbbb|
|PathfinderMob::getNoActionTime|No|()|IDK|_ZN13PathfinderMob15getNoActionTimeEv|
|PostprocessingManager::PostprocessingManager|No|()|IDK|_ZN21PostprocessingManagerC2Ev|
|PostprocessingManager::PostprocessingManager|No|()|IDK|_ZN21PostprocessingManagerC1Ev|
|PostprocessingManager::_release|No|(ChunkPos const&)|IDK|_ZN21PostprocessingManager8_releaseERK8ChunkPos|
|FallingTile::init|No|()|IDK|_ZN11FallingTile4initEv|
|FallingTile::FallingTile|No|(TileSource*, float, float, float, FullTile, bool)|IDK|_ZN11FallingTileC2EP10TileSourcefff8FullTileb|
|FallingTile::FallingTile|No|(TileSource*, float, float, float, FullTile, bool)|IDK|_ZN11FallingTileC1EP10TileSourcefff8FullTileb|
|FallingTile::FallingTile|No|(TileSource*)|IDK|_ZN11FallingTileC2EP10TileSource|
|FallingTile::FallingTile|No|(TileSource*)|IDK|_ZN11FallingTileC1EP10TileSource|
|FallingTile::getLevel|No|()|IDK|_ZN11FallingTile8getLevelEv|
|Village::Village|No|()|IDK|_ZN7VillageC2Ev|
|Village::Village|No|()|IDK|_ZN7VillageC1Ev|
|Village::Village|No|(Level*)|IDK|_ZN7VillageC2EP5Level|
|Village::Village|No|(Level*)|IDK|_ZN7VillageC1EP5Level|
|Village::setLevel|No|(Level*)|IDK|_ZN7Village8setLevelEP5Level|
|Village::countGolem|No|()|IDK|_ZN7Village10countGolemEv|
|Village::getClosestDoorInfo|No|(int, int, int)|IDK|_ZN7Village18getClosestDoorInfoEiii|
|Village::getBestDoorInfo|No|(int, int, int)|IDK|_ZN7Village15getBestDoorInfoEiii|
|Village::getDoorInfo|No|(int, int, int)|IDK|_ZN7Village11getDoorInfoEiii|
|Village::calcInfo|No|()|IDK|_ZN7Village8calcInfoEv|
|Village::resetNoBreedTimer|No|()|IDK|_ZN7Village17resetNoBreedTimerEv|
|Village::isBreedTimerOk|No|()|IDK|_ZN7Village14isBreedTimerOkEv|
|Spider::getModelScale|No|()|IDK|_ZN6Spider13getModelScaleEv|
|Spider::isClimbing|No|()|IDK|_ZN6Spider10isClimbingEv|
|Spider::onLadder|No|()|IDK|_ZN6Spider8onLadderEv|
|Spider::makeStepSound|No|()|IDK|_ZN6Spider13makeStepSoundEv|
|AddPlayerPacket::AddPlayerPacket|No|(Player const*)|IDK|_ZN15AddPlayerPacketC2EPK6Player|
|RakNet::RakString::operator=|No|(RakNet::RakString const&)|IDK|_ZN6RakNet9RakStringaSERKS0_|
|AddPlayerPacket::AddPlayerPacket|No|(Player const*)|IDK|_ZN15AddPlayerPacketC1EPK6Player|
|PlayerArmorEquipmentPacket::PlayerArmorEquipmentPacket|No|(Player*)|IDK|_ZN26PlayerArmorEquipmentPacketC2EP6Player|
|Player::getArmor|No|(int)|IDK|_ZN6Player8getArmorEi|
|vtable for PlayerArmorEquipmentPacket|No|(undefined|IDK|_ZTV26PlayerArmorEquipmentPacket|
|PlayerArmorEquipmentPacket::PlayerArmorEquipmentPacket|No|(Player*)|IDK|_ZN26PlayerArmorEquipmentPacketC1EP6Player|
|ServerSideNetworkHandler::redistributePacket|No|(Packet*, RakNet::RakNetGUID const&)|IDK|_ZN24ServerSideNetworkHandler18redistributePacketEP6PacketRKN6RakNet10RakNetGUIDE|
|RakNet::RakNetGUID::RakNetGUID|No|()|IDK|_ZN6RakNet10RakNetGUIDC1Ev|
|RakNet::SystemAddress::SystemAddress|No|()|IDK|_ZN6RakNet13SystemAddressC1Ev|
|RakNet::SystemAddress::operator=|No|(RakNet::SystemAddress const&)|IDK|_ZN6RakNet13SystemAddressaSERKS0_|
|ServerSideNetworkHandler::onEntityRemoved|No|(Entity&)|IDK|_ZN24ServerSideNetworkHandler15onEntityRemovedER6Entity|
|vtable for RemoveEntityPacket|No|(undefined|IDK|_ZTV18RemoveEntityPacket|
|vtable for RemovePlayerPacket|No|(undefined|IDK|_ZTV18RemovePlayerPacket|
|non-virtual thunk to ServerSideNetworkHandler::onEntityRemoved|No|(Entity&)|IDK|_ZThn4_N24ServerSideNetworkHandler15onEntityRemovedER6Entity|
|ServerSideNetworkHandler::handle|No|(RakNet::RakNetGUID const&, InteractPacket*)|IDK|_ZN24ServerSideNetworkHandler6handleERKN6RakNet10RakNetGUIDEP14InteractPacket|
|ServerSideNetworkHandler::handle|No|(RakNet::RakNetGUID const&, RespawnPacket*)|IDK|_ZN24ServerSideNetworkHandler6handleERKN6RakNet10RakNetGUIDEP13RespawnPacket|
|NetEventCallback::handle|No|(Level*, RakNet::RakNetGUID const&, RespawnPacket*)|IDK|_ZN16NetEventCallback6handleEP5LevelRKN6RakNet10RakNetGUIDEP13RespawnPacket|
|ServerSideNetworkHandler::handle|No|(RakNet::RakNetGUID const&, SetEntityLinkPacket*)|IDK|_ZN24ServerSideNetworkHandler6handleERKN6RakNet10RakNetGUIDEP19SetEntityLinkPacket|
|ServerSideNetworkHandler::levelEvent|No|(Mob*, int, int, int, int, int)|IDK|_ZN24ServerSideNetworkHandler10levelEventEP3Mobiiiii|
|vtable for LevelEventPacket|No|(undefined|IDK|_ZTV16LevelEventPacket|
|non-virtual thunk to ServerSideNetworkHandler::levelEvent|No|(Mob*, int, int, int, int, int)|IDK|_ZThn4_N24ServerSideNetworkHandler10levelEventEP3Mobiiiii|
|ServerSideNetworkHandler::onEntityAdded|No|(Entity&)|IDK|_ZN24ServerSideNetworkHandler13onEntityAddedER6Entity|
|SynchedEntityData::packDirty|No|()|IDK|_ZN17SynchedEntityData9packDirtyEv|
|non-virtual thunk to ServerSideNetworkHandler::onEntityAdded|No|(Entity&)|IDK|_ZThn4_N24ServerSideNetworkHandler13onEntityAddedER6Entity|
|ServerSideNetworkHandler::displayGameMessage|No|(std::string const&, std::string const&)|IDK|_ZN24ServerSideNetworkHandler18displayGameMessageERKSsS1_|
|Gui::addMessage|No|(std::string const&, std::string const&, int)|IDK|_ZN3Gui10addMessageERKSsS1_i|
|ServerSideNetworkHandler::handle|No|(RakNet::RakNetGUID const&, MessagePacket*)|IDK|_ZN24ServerSideNetworkHandler6handleERKN6RakNet10RakNetGUIDEP13MessagePacket|
|ServerSideNetworkHandler::onDisconnect|No|(RakNet::RakNetGUID const&)|IDK|_ZN24ServerSideNetworkHandler12onDisconnectERKN6RakNet10RakNetGUIDE|
|RakNet::RakNetGUID::operator==|No|(RakNet::RakNetGUID const&) const|IDK|_ZNK6RakNet10RakNetGUIDeqERKS0_|
|ServerPlayer::disconnect|No|()|IDK|_ZN12ServerPlayer10disconnectEv|
|Level::getLevelStorage|No|()|IDK|_ZN5Level15getLevelStorageEv|
|ServerSideNetworkHandler::onReady_RequestedChunks|No|(RakNet::RakNetGUID const&)|IDK|_ZN24ServerSideNetworkHandler23onReady_RequestedChunksERKN6RakNet10RakNetGUIDE|
|RakNet::BitStream::BitStream|No|()|IDK|_ZN6RakNet9BitStreamC1Ev|
|RakNet::BitStream::~BitStream|No|()|IDK|_ZN6RakNet9BitStreamD1Ev|
|ServerSideNetworkHandler::allowIncomingConnections|No|(bool)|IDK|_ZN24ServerSideNetworkHandler24allowIncomingConnectionsEb|
|ServerSideNetworkHandler::onLevelGenerated|No|(Level*)|IDK|_ZN24ServerSideNetworkHandler16onLevelGeneratedEP5Level|
|Level::addListener|No|(LevelListener*)|IDK|_ZN5Level11addListenerEP13LevelListener|
|ServerSideNetworkHandler::ServerSideNetworkHandler|No|(Minecraft*, IRakNetInstance*)|IDK|_ZN24ServerSideNetworkHandlerC2EP9MinecraftP15IRakNetInstance|
|ServerSideNetworkHandler::ServerSideNetworkHandler|No|(Minecraft*, IRakNetInstance*)|IDK|_ZN24ServerSideNetworkHandlerC1EP9MinecraftP15IRakNetInstance|
|ServerSideNetworkHandler::getPlayer|No|(RakNet::RakNetGUID const&)|IDK|_ZN24ServerSideNetworkHandler9getPlayerERKN6RakNet10RakNetGUIDE|
|ServerSideNetworkHandler::allowIncomingPacketId|No|(RakNet::RakNetGUID const&, int)|IDK|_ZN24ServerSideNetworkHandler21allowIncomingPacketIdERKN6RakNet10RakNetGUIDEi|
|ServerSideNetworkHandler::handle|No|(RakNet::RakNetGUID const&, MovePlayerPacket*)|IDK|_ZN24ServerSideNetworkHandler6handleERKN6RakNet10RakNetGUIDEP16MovePlayerPacket|
|Entity::tick|No|(TileSource*)|IDK|_ZN6Entity4tickEP10TileSource|
|Entity::checkTileCollisions|No|()|IDK|_ZN6Entity19checkTileCollisionsEv|
|ServerSideNetworkHandler::handle|No|(RakNet::RakNetGUID const&, PlayerEquipmentPacket*)|IDK|_ZN24ServerSideNetworkHandler6handleERKN6RakNet10RakNetGUIDEP21PlayerEquipmentPacket|
|FillingContainer::unlinkSlot|No|(int)|IDK|_ZN16FillingContainer10unlinkSlotEi|
|FillingContainer::replaceSlot|No|(int, ItemInstance*)|IDK|_ZN16FillingContainer11replaceSlotEiP12ItemInstance|
|Inventory::moveToSelectedSlot|No|(int)|IDK|_ZN9Inventory18moveToSelectedSlotEi|
|Inventory::selectSlot|No|(int)|IDK|_ZN9Inventory10selectSlotEi|
|ServerSideNetworkHandler::handle|No|(RakNet::RakNetGUID const&, PlayerArmorEquipmentPacket*)|IDK|_ZN24ServerSideNetworkHandler6handleERKN6RakNet10RakNetGUIDEP26PlayerArmorEquipmentPacket|
|ServerSideNetworkHandler::handle|No|(RakNet::RakNetGUID const&, AnimatePacket*)|IDK|_ZN24ServerSideNetworkHandler6handleERKN6RakNet10RakNetGUIDEP13AnimatePacket|
|ServerSideNetworkHandler::handle|No|(RakNet::RakNetGUID const&, PlayerActionPacket*)|IDK|_ZN24ServerSideNetworkHandler6handleERKN6RakNet10RakNetGUIDEP18PlayerActionPacket|
|ServerSideNetworkHandler::handle|No|(RakNet::RakNetGUID const&, DropItemPacket*)|IDK|_ZN24ServerSideNetworkHandler6handleERKN6RakNet10RakNetGUIDEP14DropItemPacket|
|ServerSideNetworkHandler::handle|No|(RakNet::RakNetGUID const&, SetHealthPacket*)|IDK|_ZN24ServerSideNetworkHandler6handleERKN6RakNet10RakNetGUIDEP15SetHealthPacket|
|ServerSideNetworkHandler::handle|No|(RakNet::RakNetGUID const&, PlayerInputPacket*)|IDK|_ZN24ServerSideNetworkHandler6handleERKN6RakNet10RakNetGUIDEP17PlayerInputPacket|
|ServerPlayer::setPlayerInput|No|(float, float, bool, bool)|IDK|_ZN12ServerPlayer14setPlayerInputEffbb|
|ServerSideNetworkHandler::sendLoginMessageMCO|No|(int, RakNet::RakNetGUID const&, LoginPacket*)|IDK|_ZN24ServerSideNetworkHandler19sendLoginMessageMCOEiRKN6RakNet10RakNetGUIDEP11LoginPacket|
|ServerSideNetworkHandler::createNewPlayer|No|(RakNet::RakNetGUID const&, LoginPacket*)|IDK|_ZN24ServerSideNetworkHandler15createNewPlayerERKN6RakNet10RakNetGUIDEP11LoginPacket|
|ServerPlayer::ServerPlayer|No|(Minecraft*, Level*)|IDK|_ZN12ServerPlayerC1EP9MinecraftP5Level|
|LevelStorage::loadPlayerData|No|(Player const&)|IDK|_ZN12LevelStorage14loadPlayerDataERK6Player|
|Player::hasRespawnPosition|No|() const|IDK|_ZNK6Player18hasRespawnPositionEv|
|Level::getDefaultSpawn|No|() const|IDK|_ZNK5Level15getDefaultSpawnEv|
|Player::setRespawnPosition|No|(TilePos const&)|IDK|_ZN6Player18setRespawnPositionERK7TilePos|
|Player::getRespawnPosition|No|()|IDK|_ZN6Player18getRespawnPositionEv|
|ServerSideNetworkHandler::sendStartWorldPackets|No|(Player*, RakNet::RakNetGUID const&)|IDK|_ZN24ServerSideNetworkHandler21sendStartWorldPacketsEP6PlayerRKN6RakNet10RakNetGUIDE|
|Minecraft::isCreativeMode|No|()|IDK|_ZN9Minecraft14isCreativeModeEv|
|Level::getSeed|No|()|IDK|_ZN5Level7getSeedEv|
|Level::getLevelData|No|()|IDK|_ZN5Level12getLevelDataEv|
|LevelData::getGenerator|No|() const|IDK|_ZNK9LevelData12getGeneratorEv|
|Level::getTime|No|() const|IDK|_ZNK5Level7getTimeEv|
|vtable for StartGamePacket|No|(undefined|IDK|_ZTV15StartGamePacket|
|vtable for SetTimePacket|No|(undefined|IDK|_ZTV13SetTimePacket|
|ServerSideNetworkHandler::numberOfConnections|No|()|IDK|_ZN24ServerSideNetworkHandler19numberOfConnectionsEv|
|MainChunkSource::MainChunkSource|No|(ChunkSource*)|IDK|_ZN15MainChunkSourceC2EP11ChunkSource|
|MainChunkSource::MainChunkSource|No|(ChunkSource*)|IDK|_ZN15MainChunkSourceC1EP11ChunkSource|
|LightUpdate::LightUpdate|No|(TileSource*, LightLayer const&, TilePos const&, TilePos const&)|IDK|_ZN11LightUpdateC2EP10TileSourceRK10LightLayerRK7TilePosS7_|
|LightUpdate::LightUpdate|No|(TileSource*, LightLayer const&, TilePos const&, TilePos const&)|IDK|_ZN11LightUpdateC1EP10TileSourceRK10LightLayerRK7TilePosS7_|
|LightUpdate::operator=|No|(LightUpdate const*)|IDK|_ZN11LightUpdateaSEPKS_|
|LightUpdate::expandIfCloseEnough|No|(TilePos, TilePos)|IDK|_ZN11LightUpdate19expandIfCloseEnoughE7TilePosS0_|
|LightUpdate::expandToContain|No|(TilePos const&)|IDK|_ZN11LightUpdate15expandToContainERK7TilePos|
|LightUpdate::expandToContain|No|(TilePos const&, TilePos const&)|IDK|_ZN11LightUpdate15expandToContainERK7TilePosS2_|
|ImageButton::ImageButton|No|(int, std::string const&)|IDK|_ZN11ImageButtonC2EiRKSs|
|Button::Button|No|(int, std::string const&, bool)|IDK|_ZN6ButtonC2EiRKSsb|
|Color4::WHITE|No|(undefined|IDK|_ZN6Color45WHITEE|
|ImageButton::ImageButton|No|(int, std::string const&)|IDK|_ZN11ImageButtonC1EiRKSs|
|ImageButton::ImageButton|No|(int, std::string const&, ImageDef const&)|IDK|_ZN11ImageButtonC2EiRKSsRK8ImageDef|
|ImageButton::ImageButton|No|(int, std::string const&, ImageDef const&)|IDK|_ZN11ImageButtonC1EiRKSsRK8ImageDef|
|ImageButton::setImageDef|No|(ImageDef const&, bool)|IDK|_ZN11ImageButton11setImageDefERK8ImageDefb|
|OptionButton::OptionButton|No|(Options::Option const*)|IDK|_ZN12OptionButtonC2EPKN7Options6OptionE|
|vtable for OptionButton|No|(undefined|IDK|_ZTV12OptionButton|
|OptionButton::OptionButton|No|(Options::Option const*)|IDK|_ZN12OptionButtonC1EPKN7Options6OptionE|
|OptionButton::OptionButton|No|(Options::Option const*, float, float)|IDK|_ZN12OptionButtonC2EPKN7Options6OptionEff|
|OptionButton::OptionButton|No|(Options::Option const*, float, float)|IDK|_ZN12OptionButtonC1EPKN7Options6OptionEff|
|OptionButton::OptionButton|No|(bool)|IDK|_ZN12OptionButtonC2Eb|
|OptionButton::OptionButton|No|(bool)|IDK|_ZN12OptionButtonC1Eb|
|OptionButton::updateImage|No|(Options*)|IDK|_ZN12OptionButton11updateImageEP7Options|
|Options::getBooleanValue|No|(Options::Option const*)|IDK|_ZN7Options15getBooleanValueEPKNS_6OptionE|
|Options::getProgressValue|No|(Options::Option const*)|IDK|_ZN7Options16getProgressValueEPKNS_6OptionE|
|OptionButton::toggle|No|(Options*)|IDK|_ZN12OptionButton6toggleEP7Options|
|Options::set|No|(Options::Option const*, float)|IDK|_ZN7Options3setEPKNS_6OptionEf|
|Options::toggle|No|(Options::Option const*, int)|IDK|_ZN7Options6toggleEPKNS_6OptionEi|
|OptionButton::mouseClicked|No|(Minecraft*, int, int, int)|IDK|_ZN12OptionButton12mouseClickedEP9Minecraftiii|
|OptionButton::keyPressed|No|(Minecraft*, int)|IDK|_ZN12OptionButton10keyPressedEP9Minecrafti|
|Keyboard::_states|No|(undefined|IDK|_ZN8Keyboard7_statesE|
|OptionsGroup::createToggle|No|(Options::Option const*, Minecraft*)|IDK|_ZN12OptionsGroup12createToggleEPKN7Options6OptionEP9Minecraft|
|vtable for std::_Sp_counted_ptr<OptionButton*, |No|(__gnu_cxx::_Lock_policy)2>|IDK|_ZTVSt15_Sp_counted_ptrIP12OptionButtonLN9__gnu_cxx12_Lock_policyE2EE|
|OptionButton::isSet|No|(Options*)|IDK|_ZN12OptionButton5isSetEP7Options|
|OptionButton::tick|No|(Minecraft*)|IDK|_ZN12OptionButton4tickEP9Minecraft|
|Controller::isTouched|No|(int)|IDK|_ZN10Controller9isTouchedEi|
|Controller::getDirection|No|(int)|IDK|_ZN10Controller12getDirectionEi|
|FleeSunGoal::FleeSunGoal|No|(PathfinderMob*, float)|IDK|_ZN11FleeSunGoalC2EP13PathfinderMobf|
|vtable for FleeSunGoal|No|(undefined|IDK|_ZTV11FleeSunGoal|
|FleeSunGoal::FleeSunGoal|No|(PathfinderMob*, float)|IDK|_ZN11FleeSunGoalC1EP13PathfinderMobf|
|Tile::teardownTiles|No|()|IDK|_ZN4Tile13teardownTilesEv|
|Tile::transformToValidBlockId|No|(int, int, int, int)|IDK|_ZN4Tile23transformToValidBlockIdEiiii|
|Tile::info_updateGame1|No|(undefined|IDK|_ZN4Tile16info_updateGame1E|
|Tile::info_updateGame2|No|(undefined|IDK|_ZN4Tile16info_updateGame2E|
|Tile::transformToValidBlockId|No|(int)|IDK|_ZN4Tile23transformToValidBlockIdEi|
|Tile::getIDByName|No|(std::string const&, bool)|IDK|_ZN4Tile11getIDByNameERKSsb|
|Util::toLower|No|(std::string const&)|IDK|_ZN4Util7toLowerERKSs|
|Tile::Tile|No|(int, Material const*)|IDK|_ZN4TileC2EiPK8Material|
|Tile::SOUND_NORMAL|No|(undefined|IDK|_ZN4Tile12SOUND_NORMALE|
|Tile::Tile|No|(int, Material const*)|IDK|_ZN4TileC1EiPK8Material|
|Tile::Tile|No|(int, TextureUVCoordinateSet, Material const*)|IDK|_ZN4TileC2Ei22TextureUVCoordinateSetPK8Material|
|Tile::Tile|No|(int, TextureUVCoordinateSet, Material const*)|IDK|_ZN4TileC1Ei22TextureUVCoordinateSetPK8Material|
|Tile::popResource|No|(TileSource*, int, int, int, ItemInstance const&)|IDK|_ZN4Tile11popResourceEP10TileSourceiiiRK12ItemInstance|
|LevelData::getGameType|No|() const|IDK|_ZNK9LevelData11getGameTypeEv|
|StemTile::spawnResources|No|(TileSource*, int, int, int, int, float)|IDK|_ZN8StemTile14spawnResourcesEP10TileSourceiiiif|
|Tile::melon|No|(undefined|IDK|_ZN4Tile5melonE|
|Item::seeds_pumpkin|No|(undefined|IDK|_ZN4Item13seeds_pumpkinE|
|Item::seeds_melon|No|(undefined|IDK|_ZN4Item11seeds_melonE|
|LeafTile::playerDestroy|No|(Player*, int, int, int, int)|IDK|_ZN8LeafTile13playerDestroyEP6Playeriiii|
|Item::shears|No|(undefined|IDK|_ZN4Item6shearsE|
|LeafTile::spawnResources|No|(TileSource*, int, int, int, int, float)|IDK|_ZN8LeafTile14spawnResourcesEP10TileSourceiiiif|
|Tile::setCategory|No|(int)|IDK|_ZN4Tile11setCategoryEi|
|Tile::getTextureUVCoordinateSet|No|(std::string const&, int)|IDK|_ZN4Tile25getTextureUVCoordinateSetERKSsi|
|TextureAtlas::getTextureItem|No|(std::string const&)|IDK|_ZN12TextureAtlas14getTextureItemERKSs|
|Tile::_terrainTextureAtlas|No|(undefined|IDK|_ZN4Tile20_terrainTextureAtlasE|
|SandTile::SandTile|No|(int)|IDK|_ZN8SandTileC2Ei|
|HeavyTile::HeavyTile|No|(int, std::string const&, Material const*)|IDK|_ZN9HeavyTileC2EiRKSsPK8Material|
|Material::sand|No|(undefined|IDK|_ZN8Material4sandE|
|vtable for SandTile|No|(undefined|IDK|_ZTV8SandTile|
|SandTile::SandTile|No|(int)|IDK|_ZN8SandTileC1Ei|
|HayBlockTile::HayBlockTile|No|(int)|IDK|_ZN12HayBlockTileC2Ei|
|RotatedPillarTile::RotatedPillarTile|No|(int, Material const*)|IDK|_ZN17RotatedPillarTileC2EiPK8Material|
|Material::dirt|No|(undefined|IDK|_ZN8Material4dirtE|
|vtable for HayBlockTile|No|(undefined|IDK|_ZTV12HayBlockTile|
|HayBlockTile::HayBlockTile|No|(int)|IDK|_ZN12HayBlockTileC1Ei|
|CakeTile::CakeTile|No|(int)|IDK|_ZN8CakeTileC2Ei|
|Material::cake|No|(undefined|IDK|_ZN8Material4cakeE|
|vtable for CakeTile|No|(undefined|IDK|_ZTV8CakeTile|
|CakeTile::CakeTile|No|(int)|IDK|_ZN8CakeTileC1Ei|
|Tile::Tile|No|(int, std::string, Material const*)|IDK|_ZN4TileC2EiSsPK8Material|
|Tile::Tile|No|(int, std::string, Material const*)|IDK|_ZN4TileC1EiSsPK8Material|
|MonsterEggTile::MonsterEggTile|No|(int)|IDK|_ZN14MonsterEggTileC2Ei|
|Material::clay|No|(undefined|IDK|_ZN8Material4clayE|
|vtable for MonsterEggTile|No|(undefined|IDK|_ZTV14MonsterEggTile|
|MonsterEggTile::MonsterEggTile|No|(int)|IDK|_ZN14MonsterEggTileC1Ei|
|LiquidTile::LiquidTile|No|(int, Material const*)|IDK|_ZN10LiquidTileC2EiPK8Material|
|TextureAtlasTextureItem::TextureAtlasTextureItem|No|()|IDK|_ZN23TextureAtlasTextureItemC1Ev|
|LiquidTile::LiquidTile|No|(int, Material const*)|IDK|_ZN10LiquidTileC1EiPK8Material|
|LeafTile::LeafTile|No|(int, std::string const&)|IDK|_ZN8LeafTileC2EiRKSs|
|Material::leaves|No|(undefined|IDK|_ZN8Material6leavesE|
|LeafTile::LeafTile|No|(int, std::string const&)|IDK|_ZN8LeafTileC1EiRKSs|
|Tile::getTextureItem|No|(std::string const&)|IDK|_ZN4Tile14getTextureItemERKSs|
|StemTile::StemTile|No|(int, Tile*)|IDK|_ZN8StemTileC2EiP4Tile|
|Bush::Bush|No|(int, std::string const&, Material const*)|IDK|_ZN4BushC2EiRKSsPK8Material|
|Material::plant|No|(undefined|IDK|_ZN8Material5plantE|
|vtable for StemTile|No|(undefined|IDK|_ZTV8StemTile|
|StemTile::StemTile|No|(int, Tile*)|IDK|_ZN8StemTileC1EiP4Tile|
|NetherReactorTile::NetherReactorTile|No|(int, std::string const&, Material const*)|IDK|_ZN17NetherReactorTileC2EiRKSsPK8Material|
|EntityTile::EntityTile|No|(int, std::string const&, Material const*)|IDK|_ZN10EntityTileC2EiRKSsPK8Material|
|vtable for NetherReactorTile|No|(undefined|IDK|_ZTV17NetherReactorTile|
|NetherReactorTile::NetherReactorTile|No|(int, std::string const&, Material const*)|IDK|_ZN17NetherReactorTileC1EiRKSsPK8Material|
|CactusTile::CactusTile|No|(int)|IDK|_ZN10CactusTileC2Ei|
|Material::cactus|No|(undefined|IDK|_ZN8Material6cactusE|
|vtable for CactusTile|No|(undefined|IDK|_ZTV10CactusTile|
|CactusTile::CactusTile|No|(int)|IDK|_ZN10CactusTileC1Ei|
|WorkbenchTile::WorkbenchTile|No|(int)|IDK|_ZN13WorkbenchTileC2Ei|
|Material::wood|No|(undefined|IDK|_ZN8Material4woodE|
|vtable for WorkbenchTile|No|(undefined|IDK|_ZTV13WorkbenchTile|
|WorkbenchTile::WorkbenchTile|No|(int)|IDK|_ZN13WorkbenchTileC1Ei|
|StonecutterTile::StonecutterTile|No|(int)|IDK|_ZN15StonecutterTileC2Ei|
|Material::stone|No|(undefined|IDK|_ZN8Material5stoneE|
|vtable for StonecutterTile|No|(undefined|IDK|_ZTV15StonecutterTile|
|StonecutterTile::StonecutterTile|No|(int)|IDK|_ZN15StonecutterTileC1Ei|
|DirtTile::DirtTile|No|(int)|IDK|_ZN8DirtTileC2Ei|
|vtable for DirtTile|No|(undefined|IDK|_ZTV8DirtTile|
|DirtTile::DirtTile|No|(int)|IDK|_ZN8DirtTileC1Ei|
|ThinFenceTile::ThinFenceTile|No|(int, std::string const&, std::string const&, Material const*, bool)|IDK|_ZN13ThinFenceTileC2EiRKSsS1_PK8Materialb|
|vtable for ThinFenceTile|No|(undefined|IDK|_ZTV13ThinFenceTile|
|ThinFenceTile::ThinFenceTile|No|(int, std::string const&, std::string const&, Material const*, bool)|IDK|_ZN13ThinFenceTileC1EiRKSsS1_PK8Materialb|
|QuartzBlockTile::QuartzBlockTile|No|(int)|IDK|_ZN15QuartzBlockTileC2Ei|
|vtable for QuartzBlockTile|No|(undefined|IDK|_ZTV15QuartzBlockTile|
|QuartzBlockTile::QuartzBlockTile|No|(int)|IDK|_ZN15QuartzBlockTileC1Ei|
|Tile::isLiquidTile|No|() const|IDK|_ZNK4Tile12isLiquidTileEv|
|Tile::getTileMaterial|No|(int)|IDK|_ZN4Tile15getTileMaterialEi|
|Material::air|No|(undefined|IDK|_ZN8Material3airE|
|LevelChunk::getTopSolidBlock|No|(ChunkTilePos const&, bool)|IDK|_ZN10LevelChunk16getTopSolidBlockERK12ChunkTilePosb|
|LevelChunk::getTopRainTilePos|No|(ChunkTilePos const&)|IDK|_ZN10LevelChunk17getTopRainTilePosERK12ChunkTilePos|
|Tile::isObstructingChests|No|(TileSource*, TilePos const&)|IDK|_ZN4Tile19isObstructingChestsEP10TileSourceRK7TilePos|
|GroundBushFeature::GroundBushFeature|No|(int, int)|IDK|_ZN17GroundBushFeatureC2Eii|
|TreeFeature::TreeFeature|No|(bool, int, int, int, int, bool)|IDK|_ZN11TreeFeatureC2Ebiiiib|
|vtable for GroundBushFeature|No|(undefined|IDK|_ZTV17GroundBushFeature|
|GroundBushFeature::GroundBushFeature|No|(int, int)|IDK|_ZN17GroundBushFeatureC1Eii|
|BiomeDecorator::BiomeDecorator|No|()|IDK|_ZN14BiomeDecoratorC2Ev|
|Feature::Feature|No|(bool)|IDK|_ZN7FeatureC2Eb|
|BirchFeature::BirchFeature|No|(bool, bool)|IDK|_ZN12BirchFeatureC1Ebb|
|FancyTreeFeature::FancyTreeFeature|No|(bool)|IDK|_ZN16FancyTreeFeatureC1Eb|
|TileBlobFeature::TileBlobFeature|No|(unsigned char, int)|IDK|_ZN15TileBlobFeatureC1Ehi|
|vtable for ClayFeature|No|(undefined|IDK|_ZTV11ClayFeature|
|Tile::clay|No|(undefined|IDK|_ZN4Tile4clayE|
|Tile::sand|No|(undefined|IDK|_ZN4Tile4sandE|
|vtable for SandFeature|No|(undefined|IDK|_ZTV11SandFeature|
|Tile::gravel|No|(undefined|IDK|_ZN4Tile6gravelE|
|Tile::dirt|No|(undefined|IDK|_ZN4Tile4dirtE|
|vtable for OreFeature|No|(undefined|IDK|_ZTV10OreFeature|
|Tile::ironOre|No|(undefined|IDK|_ZN4Tile7ironOreE|
|Tile::goldOre|No|(undefined|IDK|_ZN4Tile7goldOreE|
|Tile::redStoneOre|No|(undefined|IDK|_ZN4Tile11redStoneOreE|
|vtable for FlowerFeature|No|(undefined|IDK|_ZTV13FlowerFeature|
|Tile::brownMushroom|No|(undefined|IDK|_ZN4Tile13brownMushroomE|
|Tile::redMushroom|No|(undefined|IDK|_ZN4Tile11redMushroomE|
|vtable for HugeMushroomFeature|No|(undefined|IDK|_ZTV19HugeMushroomFeature|
|vtable for ReedsFeature|No|(undefined|IDK|_ZTV12ReedsFeature|
|vtable for CactusFeature|No|(undefined|IDK|_ZTV13CactusFeature|
|vtable for WaterlilyFeature|No|(undefined|IDK|_ZTV16WaterlilyFeature|
|vtable for PumpkinFeature|No|(undefined|IDK|_ZTV14PumpkinFeature|
|Tile::water|No|(undefined|IDK|_ZN4Tile5waterE|
|vtable for SpringFeature|No|(undefined|IDK|_ZTV13SpringFeature|
|Tile::lava|No|(undefined|IDK|_ZN4Tile4lavaE|
|vtable for DeadBushFeature|No|(undefined|IDK|_ZTV15DeadBushFeature|
|vtable for DesertWellFeature|No|(undefined|IDK|_ZTV17DesertWellFeature|
|vtable for OakFeature|No|(undefined|IDK|_ZTV10OakFeature|
|vtable for SpruceFeature|No|(undefined|IDK|_ZTV13SpruceFeature|
|vtable for RoofTreeFeature|No|(undefined|IDK|_ZTV15RoofTreeFeature|
|vtable for PineFeature|No|(undefined|IDK|_ZTV11PineFeature|
|vtable for MegaPineTreeFeature|No|(undefined|IDK|_ZTV19MegaPineTreeFeature|
|Tile::tallgrass|No|(undefined|IDK|_ZN4Tile9tallgrassE|
|vtable for TallGrassFeature|No|(undefined|IDK|_ZTV16TallGrassFeature|
|Tile::mossStone|No|(undefined|IDK|_ZN4Tile9mossStoneE|
|vtable for SwampTreeFeature|No|(undefined|IDK|_ZTV16SwampTreeFeature|
|vtable for IceSpikeFeature|No|(undefined|IDK|_ZTV15IceSpikeFeature|
|vtable for IcePatchFeature|No|(undefined|IDK|_ZTV15IcePatchFeature|
|Tile::packedIce|No|(undefined|IDK|_ZN4Tile9packedIceE|
|vtable for JungleTreeFeature|No|(undefined|IDK|_ZTV17JungleTreeFeature|
|vtable for MegaJungleTreeFeature|No|(undefined|IDK|_ZTV21MegaJungleTreeFeature|
|vtable for MelonFeatrue|No|(undefined|IDK|_ZTV12MelonFeatrue|
|vtable for VinesFeature|No|(undefined|IDK|_ZTV12VinesFeature|
|vtable for SavannaTreeFeature|No|(undefined|IDK|_ZTV18SavannaTreeFeature|
|BiomeDecorator::BiomeDecorator|No|()|IDK|_ZN14BiomeDecoratorC1Ev|
|CreativeInventoryScreen::createInventoryTabButton|No|(int, int)|IDK|_ZN23CreativeInventoryScreen24createInventoryTabButtonEii|
|Button::setOverrideScreenRendering|No|(bool)|IDK|_ZN6Button26setOverrideScreenRenderingEb|
|vtable for CategoryButton|No|(undefined|IDK|_ZTV14CategoryButton|
|vtable for std::_Sp_counted_ptr<CategoryButton*, |No|(__gnu_cxx::_Lock_policy)2>|IDK|_ZTVSt15_Sp_counted_ptrIP14CategoryButtonLN9__gnu_cxx12_Lock_policyE2EE|
|CreativeInventoryScreen::getItemFromType|No|(int)|IDK|_ZN23CreativeInventoryScreen15getItemFromTypeEi|
|ItemInstance::ItemInstance|No|(Tile const*)|IDK|_ZN12ItemInstanceC1EPK4Tile|
|Tile::redBrick|No|(undefined|IDK|_ZN4Tile8redBrickE|
|Item::sword_iron|No|(undefined|IDK|_ZN4Item10sword_ironE|
|Tile::bookshelf|No|(undefined|IDK|_ZN4Tile9bookshelfE|
|CreativeInventoryScreen::drawIcon|No|(int, std::shared_ptr<ImageButton>, bool, bool)|IDK|_ZN23CreativeInventoryScreen8drawIconEiSt10shared_ptrI11ImageButtonEbb|
|CreativeInventoryScreen::_putItemInToolbar|No|(ItemInstance const*)|IDK|_ZN23CreativeInventoryScreen17_putItemInToolbarEPK12ItemInstance|
|CreativeInventoryScreen::getCategoryFromPanel|No|(Touch::InventoryPane const*)|IDK|_ZN23CreativeInventoryScreen20getCategoryFromPanelEPKN5Touch13InventoryPaneE|
|CreativeInventoryScreen::addItem|No|(Touch::InventoryPane const*, int)|IDK|_ZN23CreativeInventoryScreen7addItemEPKN5Touch13InventoryPaneEi|
|Inventory::getLinkedSlotForItemIdAndAux|No|(int, int)|IDK|_ZN9Inventory28getLinkedSlotForItemIdAndAuxEii|
|ItemInstance::ItemInstance|No|(ItemInstance const&)|IDK|_ZN12ItemInstanceC1ERKS_|
|FillingContainer::linkSlot|No|(int, int)|IDK|_ZN16FillingContainer8linkSlotEii|
|non-virtual thunk to CreativeInventoryScreen::addItem|No|(Touch::InventoryPane const*, int)|IDK|_ZThn132_N23CreativeInventoryScreen7addItemEPKN5Touch13InventoryPaneEi|
|CreativeInventoryScreen::getItems|No|(Touch::InventoryPane const*)|IDK|_ZN23CreativeInventoryScreen8getItemsEPKN5Touch13InventoryPaneE|
|non-virtual thunk to CreativeInventoryScreen::getItems|No|(Touch::InventoryPane const*)|IDK|_ZThn132_N23CreativeInventoryScreen8getItemsEPKN5Touch13InventoryPaneE|
|CreativeInventoryScreen::closeWindow|No|()|IDK|_ZN23CreativeInventoryScreen11closeWindowEv|
|CreativeInventoryScreen::handleBackEvent|No|(bool)|IDK|_ZN23CreativeInventoryScreen15handleBackEventEb|
|CreativeInventoryScreen::buttonClicked|No|(Button*)|IDK|_ZN23CreativeInventoryScreen13buttonClickedEP6Button|
|BedTile::BedTile|No|(int)|IDK|_ZN7BedTileC2Ei|
|Material::bed|No|(undefined|IDK|_ZN8Material3bedE|
|vtable for BedTile|No|(undefined|IDK|_ZTV7BedTile|
|BedTile::BedTile|No|(int)|IDK|_ZN7BedTileC1Ei|
|BedTile::isHeadPiece|No|(int)|IDK|_ZN7BedTile11isHeadPieceEi|
|BedTile::getTexture|No|(signed char, int)|IDK|_ZN7BedTile10getTextureEai|
|Direction::RELATIVE_DIRECTION_FACING|No|(undefined|IDK|_ZN9Direction25RELATIVE_DIRECTION_FACINGE|
|BedTile::getResource|No|(int, Random*)|IDK|_ZN7BedTile11getResourceEiP6Random|
|Item::bed|No|(undefined|IDK|_ZN4Item3bedE|
|BedTile::spawnResources|No|(TileSource*, int, int, int, int, float)|IDK|_ZN7BedTile14spawnResourcesEP10TileSourceiiiif|
|BedTile::isOccupied|No|(int)|IDK|_ZN7BedTile10isOccupiedEi|
|gluPerspective|No|(float, float, float, float)|IDK|_Z14gluPerspectiveffff|
|anGenBuffers|No|(int, unsigned int*)|IDK|_Z12anGenBuffersiPj|
|MultiplyMatrices4by4OpenGL_FLOAT|No|(float*, float*, float*)|IDK|_Z32MultiplyMatrices4by4OpenGL_FLOATPfS_S_|
|MultiplyMatrixByVector4by4OpenGL_FLOAT|No|(float*, float const*, float const*)|IDK|_Z38MultiplyMatrixByVector4by4OpenGL_FLOATPfPKfS1_|
|glhInvertMatrixf2|No|(float*, float*)|IDK|_Z17glhInvertMatrixf2PfS_|
|glhUnProjectf|No|(float, float, float, float*, float*, int*, float*)|IDK|_Z13glhUnProjectffffPfS_PiS_|
|SmoothLayer::SmoothLayer|No|(long, std::shared_ptr<Layer>&)|IDK|_ZN11SmoothLayerC2ElRSt10shared_ptrI5LayerE|
|vtable for SmoothLayer|No|(undefined|IDK|_ZTV11SmoothLayer|
|SmoothLayer::SmoothLayer|No|(long, std::shared_ptr<Layer>&)|IDK|_ZN11SmoothLayerC1ElRSt10shared_ptrI5LayerE|
|StoneBeachBiome::StoneBeachBiome|No|(int)|IDK|_ZN15StoneBeachBiomeC2Ei|
|StoneBeachBiome::StoneBeachBiome|No|(int)|IDK|_ZN15StoneBeachBiomeC1Ei|
|TilePos::TilePos|No|(ChunkPos const&, int)|IDK|_ZN7TilePosC2ERK8ChunkPosi|
|TilePos::TilePos|No|(ChunkPos const&, int)|IDK|_ZN7TilePosC1ERK8ChunkPosi|
|LevelChunk::LevelChunk|No|(Level&, ChunkPos const&, bool)|IDK|_ZN10LevelChunkC2ER5LevelRK8ChunkPosb|
|LevelChunk::LevelChunk|No|(Level&, ChunkPos const&, bool)|IDK|_ZN10LevelChunkC1ER5LevelRK8ChunkPosb|
|TilePos::TilePos|No|(float, float, float)|IDK|_ZN7TilePosC2Efff|
|TilePos::TilePos|No|(float, float, float)|IDK|_ZN7TilePosC1Efff|
|TerrainParticle::init|No|(float, float, float, float, float, float, int)|IDK|_ZN15TerrainParticle4initEffffffi|
|Tile::grass|No|(undefined|IDK|_ZN4Tile5grassE|
|TilePos::TilePos|No|(Vec3 const&)|IDK|_ZN7TilePosC2ERK4Vec3|
|TilePos::TilePos|No|(Vec3 const&)|IDK|_ZN7TilePosC1ERK4Vec3|
|ServerSideNetworkHandler::getAddPacketFromEntity|No|(Entity*)|IDK|_ZN24ServerSideNetworkHandler22getAddPacketFromEntityEP6Entity|
|vtable for AddEntityPacket|No|(undefined|IDK|_ZTV15AddEntityPacket|
|vtable for AddItemEntityPacket|No|(undefined|IDK|_ZTV19AddItemEntityPacket|
|TilePos::neighbor|No|(int)|IDK|_ZN7TilePos8neighborEi|
|Facing::DIRECTION|No|(undefined|IDK|_ZN6Facing9DIRECTIONE|
|TilePos::relative|No|(signed char, int) const|IDK|_ZNK7TilePos8relativeEai|
|TileSource::getTickQueue|No|() const|IDK|_ZNK10TileSource12getTickQueueEv|
|TileSource::setTickingQueue|No|(TileTickingQueue&)|IDK|_ZN10TileSource15setTickingQueueER16TileTickingQueue|
|TileSource::getChunk|No|(ChunkPos const&)|IDK|_ZN10TileSource8getChunkERK8ChunkPos|
|ChunkSource::getGeneratedChunk|No|(ChunkPos const&)|IDK|_ZN11ChunkSource17getGeneratedChunkERK8ChunkPos|
|ChunkSource::getAvailableChunk|No|(ChunkPos const&)|IDK|_ZN11ChunkSource17getAvailableChunkERK8ChunkPos|
|TileSource::getChunk|No|(int, int)|IDK|_ZN10TileSource8getChunkEii|
|TileSource::getWritableChunk|No|(ChunkPos const&)|IDK|_ZN10TileSource16getWritableChunkERK8ChunkPos|
|TileSource::_shouldFireEvent|No|(LevelChunk&) const|IDK|_ZNK10TileSource16_shouldFireEventER10LevelChunk|
|TileSource::hasChunksAt|No|(Bounds const&)|IDK|_ZN10TileSource11hasChunksAtERK6Bounds|
|TileSource::hasChunksAt|No|(AABB const&)|IDK|_ZN10TileSource11hasChunksAtERK4AABB|
|TileSource::hasChunksAt|No|(int, int, int, int)|IDK|_ZN10TileSource11hasChunksAtEiiii|
|TileSource::hasChunksAt|No|(TilePos const&, int)|IDK|_ZN10TileSource11hasChunksAtERK7TilePosi|
|TileSource::hasChunksAt|No|(TilePos const&, TilePos const&)|IDK|_ZN10TileSource11hasChunksAtERK7TilePosS2_|
|TileSource::getTile|No|(TilePos const&)|IDK|_ZN10TileSource7getTileERK7TilePos|
|ChunkPos::ChunkPos|No|(TilePos const&)|IDK|_ZN8ChunkPosC1ERK7TilePos|
|ChunkTilePos::ChunkTilePos|No|(TilePos const&)|IDK|_ZN12ChunkTilePosC1ERK7TilePos|
|_istransparent|No|(TileSource&, TilePos const&)|IDK|_Z14_istransparentR10TileSourceRK7TilePos|
|Tile::leaves|No|(undefined|IDK|_ZN4Tile6leavesE|
|Tile::leaves2|No|(undefined|IDK|_ZN4Tile7leaves2E|
|LeafTile::isDeepLeafTile|No|(TileSource&, TilePos const&)|IDK|_ZN8LeafTile14isDeepLeafTileER10TileSourceRK7TilePos|
|Tile::topSnow|No|(undefined|IDK|_ZN4Tile7topSnowE|
|TileSource::getTilePtr|No|(TilePos const&)|IDK|_ZN10TileSource10getTilePtrERK7TilePos|
|TileSource::getData|No|(TilePos const&)|IDK|_ZN10TileSource7getDataERK7TilePos|
|TileSource::getTileAndData|No|(TilePos const&)|IDK|_ZN10TileSource14getTileAndDataERK7TilePos|
|MegaTreeFeature::placeDoubleTrunkLeaves|No|(TileSource*, TilePos const&, int) const|IDK|_ZNK15MegaTreeFeature22placeDoubleTrunkLeavesEP10TileSourceRK7TilePosi|
|Feature::setTileAndData|No|(TileSource*, TilePos const&, unsigned char, unsigned char) const|IDK|_ZNK7Feature14setTileAndDataEP10TileSourceRK7TilePoshh|
|Tile::shouldRenderFace|No|(TileSource*, int, int, int, signed char, AABB const&)|IDK|_ZN4Tile16shouldRenderFaceEP10TileSourceiiiaRK4AABB|
|Tile::invisible_bedrock|No|(undefined|IDK|_ZN4Tile17invisible_bedrockE|
|Tile::woolCarpet|No|(undefined|IDK|_ZN4Tile10woolCarpetE|
|TileSource::getBrightness|No|(LightLayer const&, TilePos const&)|IDK|_ZN10TileSource13getBrightnessERK10LightLayerRK7TilePos|
|TileSource::getRawBrightness|No|(TilePos const&, bool)|IDK|_ZN10TileSource16getRawBrightnessERK7TilePosb|
|Tile::woodSlabHalf|No|(undefined|IDK|_ZN4Tile12woodSlabHalfE|
|LeafTile::getMobToSpawn|No|(TileSource&, TilePos const&) const|IDK|_ZNK8LeafTile13getMobToSpawnER10TileSourceRK7TilePos|
|TileSource::getBrightness|No|(TilePos const&)|IDK|_ZN10TileSource13getBrightnessERK7TilePos|
|TileSource::canSeeSky|No|(TilePos const&)|IDK|_ZN10TileSource9canSeeSkyERK7TilePos|
|FleeSunGoal::getHidePos|No|(Vec3*)|IDK|_ZN11FleeSunGoal10getHidePosEP4Vec3|
|Goal::getRegion|No|()|IDK|_ZN4Goal9getRegionEv|
|TileSource::getMaterial|No|(TilePos const&)|IDK|_ZN10TileSource11getMaterialERK7TilePos|
|GroundBushFeature::place|No|(TileSource*, int, int, int, Random&) const|IDK|_ZNK17GroundBushFeature5placeEP10TileSourceiiiR6Random|
|TileSource::_neighborChanged|No|(TilePos const&, TilePos const&, unsigned char)|IDK|_ZN10TileSource16_neighborChangedERK7TilePosS2_h|
|TileSource::updateNeighborsAt|No|(TilePos const&, unsigned char)|IDK|_ZN10TileSource17updateNeighborsAtERK7TilePosh|
|TileSource::hasNeighborSignal|No|(int, int, int)|IDK|_ZN10TileSource17hasNeighborSignalEiii|
|TileSource::runLightUpdates|No|(LightLayer const&, TilePos const&, TilePos const&)|IDK|_ZN10TileSource15runLightUpdatesERK10LightLayerRK7TilePosS5_|
|TileSource::updateLightIfOtherThan|No|(LightLayer const&, TilePos const&, unsigned char)|IDK|_ZN10TileSource22updateLightIfOtherThanERK10LightLayerRK7TilePosh|
|TileSource::isTopSolidBlocking|No|(Tile*, unsigned char)|IDK|_ZN10TileSource18isTopSolidBlockingEP4Tileh|
|TileSource::isTopSolidBlocking|No|(TilePos const&)|IDK|_ZN10TileSource18isTopSolidBlockingERK7TilePos|
|TileSource::onChunkDiscarded|No|(LevelChunk&)|IDK|_ZN10TileSource16onChunkDiscardedER10LevelChunk|
|TileSource::fireAreaChanged|No|(TilePos const&, TilePos const&)|IDK|_ZN10TileSource15fireAreaChangedERK7TilePosS2_|
|TileSource::fireTilesDirty|No|(int, int, int, int, int, int)|IDK|_ZN10TileSource14fireTilesDirtyEiiiiii|
|LevelChunk::_recalcHeight|No|(ChunkTilePos const&, TileSource*)|IDK|_ZN10LevelChunk13_recalcHeightERK12ChunkTilePosP10TileSource|
|TileSource::fireTileChanged|No|(TilePos const&, FullTile, FullTile, int)|IDK|_ZN10TileSource15fireTileChangedERK7TilePos8FullTileS3_i|
|TileSource::_tileChanged|No|(TilePos const&, FullTile, FullTile, int)|IDK|_ZN10TileSource12_tileChangedERK7TilePos8FullTileS3_i|
|TileSource::fireBrightnessChanged|No|(TilePos const&)|IDK|_ZN10TileSource21fireBrightnessChangedERK7TilePos|
|TileSource::setBrightness|No|(LightLayer const&, TilePos const&, unsigned char)|IDK|_ZN10TileSource13setBrightnessERK10LightLayerRK7TilePosh|
|LightUpdate::update|No|()|IDK|_ZN11LightUpdate6updateEv|
|LevelChunk::updateLightsAndHeights|No|(TileSource&)|IDK|_ZN10LevelChunk22updateLightsAndHeightsER10TileSource|
|TileSource::fireTileEntityChanged|No|(TileEntity&)|IDK|_ZN10TileSource21fireTileEntityChangedER10TileEntity|
|TileSource::fireTileEntityRemoved|No|(std::unique_ptr<TileEntity, std::default_delete<TileEntity> >&)|IDK|_ZN10TileSource21fireTileEntityRemovedERSt10unique_ptrI10TileEntitySt14default_deleteIS1_EE|
|TileSource::fireTileEvent|No|(int, int, int, int, int)|IDK|_ZN10TileSource13fireTileEventEiiiii|
|TileSource::isEmptyTile|No|(TilePos const&)|IDK|_ZN10TileSource11isEmptyTileERK7TilePos|
|TileSource::isEmptyTile|No|(int, int, int)|IDK|_ZN10TileSource11isEmptyTileEiii|
|RoofTreeFeature::placeVine|No|(TileSource*, Random&, TilePos const&, int) const|IDK|_ZNK15RoofTreeFeature9placeVineEP10TileSourceR6RandomRK7TilePosi|
|Tile::vine|No|(undefined|IDK|_ZN4Tile4vineE|
|TileSource::getChunkAt|No|(TilePos const&)|IDK|_ZN10TileSource10getChunkAtERK7TilePos|
|TileSource::hasTile|No|(TilePos const&)|IDK|_ZN10TileSource7hasTileERK7TilePos|
|TileSource::getTopSolidBlock|No|(TilePos const&, bool)|IDK|_ZN10TileSource16getTopSolidBlockERK7TilePosb|
|BiomeDecorator::_getRandomSolidPosition|No|(TileSource*, TilePos const&, Random&)|IDK|_ZN14BiomeDecorator23_getRandomSolidPositionEP10TileSourceRK7TilePosR6Random|
|TileSource::getHeightmap|No|(TilePos const&)|IDK|_ZN10TileSource12getHeightmapERK7TilePos|
|BiomeDecorator::_getRandomSurfacePosition|No|(TileSource*, TilePos const&, Random&)|IDK|_ZN14BiomeDecorator25_getRandomSurfacePositionEP10TileSourceRK7TilePosR6Random|
|BiomeDecorator::_getRandomTreePosition|No|(TileSource*, TilePos const&, Random&)|IDK|_ZN14BiomeDecorator22_getRandomTreePositionEP10TileSourceRK7TilePosR6Random|
|TileSource::getHeightmapPos|No|(TilePos const&)|IDK|_ZN10TileSource15getHeightmapPosERK7TilePos|
|LevelChunk::_lightGap|No|(TileSource&, TilePos const&)|IDK|_ZN10LevelChunk9_lightGapER10TileSourceRK7TilePos|
|LevelChunk::_lightGaps|No|(TileSource&, ChunkTilePos const&)|IDK|_ZN10LevelChunk10_lightGapsER10TileSourceRK12ChunkTilePos|
|ChunkTilePos::operator+|No|(TilePos const&) const|IDK|_ZNK12ChunkTilePosplERK7TilePos|
|TileSource::findHighestNonEmptyTileAt|No|(TilePos const&)|IDK|_ZN10TileSource25findHighestNonEmptyTileAtERK7TilePos|
|TileSource::tileEntityChanged|No|(TileEntity&)|IDK|_ZN10TileSource17tileEntityChangedER10TileEntity|
|TileSource::getTileEntity|No|(TilePos const&)|IDK|_ZN10TileSource13getTileEntityERK7TilePos|
|ServerSideNetworkHandler::onTileChanged|No|(TileSource*, TilePos const&, FullTile, FullTile, int)|IDK|_ZN24ServerSideNetworkHandler13onTileChangedEP10TileSourceRK7TilePos8FullTileS5_i|
|vtable for UpdateBlockPacket|No|(undefined|IDK|_ZTV17UpdateBlockPacket|
|non-virtual thunk to ServerSideNetworkHandler::onTileChanged|No|(TileSource*, TilePos const&, FullTile, FullTile, int)|IDK|_ZThn4_N24ServerSideNetworkHandler13onTileChangedEP10TileSourceRK7TilePos8FullTileS5_i|
|ServerSideNetworkHandler::handle|No|(RakNet::RakNetGUID const&, EntityDataPacket*)|IDK|_ZN24ServerSideNetworkHandler6handleERKN6RakNet10RakNetGUIDEP16EntityDataPacket|
|TileEntity::isType|No|(TileEntity*, TileEntityType)|IDK|_ZN10TileEntity6isTypeEPS_14TileEntityType|
|TileSource::getChunkAt|No|(int, int, int)|IDK|_ZN10TileSource10getChunkAtEiii|
|TileSource::getBiome|No|(TilePos const&)|IDK|_ZN10TileSource8getBiomeERK7TilePos|
|Biome::ocean|No|(undefined|IDK|_ZN5Biome5oceanE|
|LiquidTile::getColor|No|(TileSource*, int, int, int)|IDK|_ZN10LiquidTile8getColorEP10TileSourceiii|
|LeafTile::getColor|No|(TileSource*, int, int, int)|IDK|_ZN8LeafTile8getColorEP10TileSourceiii|
|Tile::_getTypeToSpawn|No|(TileSource&, int, TilePos const&) const|IDK|_ZNK4Tile15_getTypeToSpawnER10TileSourceiRK7TilePos|
|Tile::getMobToSpawn|No|(TileSource&, TilePos const&) const|IDK|_ZNK4Tile13getMobToSpawnER10TileSourceRK7TilePos|
|TileSource::setGrassColor|No|(int, TilePos const&, int)|IDK|_ZN10TileSource13setGrassColorEiRK7TilePosi|
|TileSource::getGrassColor|No|(TilePos const&)|IDK|_ZN10TileSource13getGrassColorERK7TilePos|
|ReedTile::getColor|No|(TileSource*, int, int, int)|IDK|_ZN8ReedTile8getColorEP10TileSourceiii|
|TileSource::findNextTopSolidTileUnder|No|(TilePos&)|IDK|_ZN10TileSource25findNextTopSolidTileUnderER7TilePos|
|TileSource::getTopRainTilePos|No|(TilePos const&)|IDK|_ZN10TileSource17getTopRainTilePosERK7TilePos|
|TileSource::isWaterAt|No|(TilePos const&)|IDK|_ZN10TileSource9isWaterAtERK7TilePos|
|TileSource::shouldFreeze|No|(TilePos const&, bool)|IDK|_ZN10TileSource12shouldFreezeERK7TilePosb|
|Tile::calmWater|No|(undefined|IDK|_ZN4Tile9calmWaterE|
|TileSource::shouldFreezeIgnoreNeighbors|No|(TilePos const&)|IDK|_ZN10TileSource27shouldFreezeIgnoreNeighborsERK7TilePos|
|TileSource::shouldSnow|No|(TilePos const&, bool)|IDK|_ZN10TileSource10shouldSnowERK7TilePosb|
|TileSource::isHumidAt|No|(TilePos const&)|IDK|_ZN10TileSource9isHumidAtERK7TilePos|
|TileSource::hasTile|No|(int, int, int)|IDK|_ZN10TileSource7hasTileEiii|
|TileSource::getTile|No|(int, int, int)|IDK|_ZN10TileSource7getTileEiii|
|PineFeature::place|No|(TileSource*, int, int, int, Random&) const|IDK|_ZNK11PineFeature5placeEP10TileSourceiiiR6Random|
|Feature::placeTile|No|(TileSource*, int, int, int, unsigned char, unsigned char) const|IDK|_ZNK7Feature9placeTileEP10TileSourceiiihh|
|ThinFenceTile::getShape|No|(TileSource*, int, int, int, AABB&, bool)|IDK|_ZN13ThinFenceTile8getShapeEP10TileSourceiiiR4AABBb|
|Tile::glass|No|(undefined|IDK|_ZN4Tile5glassE|
|Tile::mayPlace|No|(TileSource*, int, int, int)|IDK|_ZN4Tile8mayPlaceEP10TileSourceiii|
|CactusTile::mayPlace|No|(TileSource*, int, int, int)|IDK|_ZN10CactusTile8mayPlaceEP10TileSourceiii|
|TileSource::isSolidBlockingTile|No|(int, int, int)|IDK|_ZN10TileSource19isSolidBlockingTileEiii|
|HugeMushroomFeature::place|No|(TileSource*, int, int, int, Random&) const|IDK|_ZNK19HugeMushroomFeature5placeEP10TileSourceiiiR6Random|
|Tile::mycelium|No|(undefined|IDK|_ZN4Tile8myceliumE|
|Tile::brownMushroomBlock|No|(undefined|IDK|_ZN4Tile18brownMushroomBlockE|
|ObsidianTile::poofParticles|No|(TileSource*, int, int, int)|IDK|_ZN12ObsidianTile13poofParticlesEP10TileSourceiii|
|ObsidianTile::animateTick|No|(TileSource*, int, int, int, Random*)|IDK|_ZN12ObsidianTile11animateTickEP10TileSourceiiiP6Random|
|RedStoneOreTile::poofParticles|No|(TileSource*, int, int, int)|IDK|_ZN15RedStoneOreTile13poofParticlesEP10TileSourceiii|
|RedStoneOreTile::animateTick|No|(TileSource*, int, int, int, Random*)|IDK|_ZN15RedStoneOreTile11animateTickEP10TileSourceiiiP6Random|
|TileSource::isSolidBlockingTile|No|(TilePos const&)|IDK|_ZN10TileSource19isSolidBlockingTileERK7TilePos|
|FlowerTile::_randomWalk|No|(TileSource*, int&, int&, int&, int)|IDK|_ZN10FlowerTile11_randomWalkEP10TileSourceRiS2_S2_i|
|TileSource::isSolidRenderTile|No|(int, int, int)|IDK|_ZN10TileSource17isSolidRenderTileEiii|
|Tile::isFaceVisible|No|(TileSource*, int, int, int, signed char)|IDK|_ZN4Tile13isFaceVisibleEP10TileSourceiiia|
|TileSource::containsAnyLiquid|No|(AABB const&)|IDK|_ZN10TileSource17containsAnyLiquidERK4AABB|
|AABB::flooredCeiledCopy|No|() const|IDK|_ZNK4AABB17flooredCeiledCopyEv|
|TileSource::containsFireTile|No|(AABB const&)|IDK|_ZN10TileSource16containsFireTileERK4AABB|
|Tile::fire|No|(undefined|IDK|_ZN4Tile4fireE|
|Tile::calmLava|No|(undefined|IDK|_ZN4Tile8calmLavaE|
|TileSource::containsMaterial|No|(AABB const&, Material const*)|IDK|_ZN10TileSource16containsMaterialERK4AABBPK8Material|
|Village::canSpawnAt|No|(int, int, int, int, int, int)|IDK|_ZN7Village10canSpawnAtEiiiiii|
|Village::findRandomSpawnPos|No|(Vec3&, int, int, int, int, int, int)|IDK|_ZN7Village18findRandomSpawnPosER4Vec3iiiiii|
|Village::isDoor|No|(int, int, int)|IDK|_ZN7Village6isDoorEiii|
|Tile::door_wood|No|(undefined|IDK|_ZN4Tile9door_woodE|
|Village::updateDoors|No|()|IDK|_ZN7Village11updateDoorsEv|
|TransparentTile::shouldRenderFace|No|(TileSource*, int, int, int, signed char, AABB const&)|IDK|_ZN15TransparentTile16shouldRenderFaceEP10TileSourceiiiaRK4AABB|
|HalfTransparentTile::shouldRenderFace|No|(TileSource*, int, int, int, signed char, AABB const&)|IDK|_ZN19HalfTransparentTile16shouldRenderFaceEP10TileSourceiiiaRK4AABB|
|ThinFenceTile::shouldRenderFace|No|(TileSource*, int, int, int, signed char, AABB const&)|IDK|_ZN13ThinFenceTile16shouldRenderFaceEP10TileSourceiiiaRK4AABB|
|ServerSideNetworkHandler::handle|No|(RakNet::RakNetGUID const&, UseItemPacket*)|IDK|_ZN24ServerSideNetworkHandler6handleERKN6RakNet10RakNetGUIDEP13UseItemPacket|
|TileSource::tileEvent|No|(int, int, int, int, int)|IDK|_ZN10TileSource9tileEventEiiiii|
|TileSource::tileEvent|No|(TilePos const&, int, int)|IDK|_ZN10TileSource9tileEventERK7TilePosii|
|TileSource::getData|No|(int, int, int)|IDK|_ZN10TileSource7getDataEiii|
|StemTile::getGrowthSpeed|No|(TileSource*, int, int, int)|IDK|_ZN8StemTile14getGrowthSpeedEP10TileSourceiii|
|StemTile::getColor|No|(TileSource*, int, int, int)|IDK|_ZN8StemTile8getColorEP10TileSourceiii|
|StemTile::getConnectDir|No|(TileSource*, int, int, int)|IDK|_ZN8StemTile13getConnectDirEP10TileSourceiii|
|CropTile::getGrowthSpeed|No|(TileSource*, int, int, int)|IDK|_ZN8CropTile14getGrowthSpeedEP10TileSourceiii|
|CropTile::getTexture|No|(TileSource*, int, int, int, signed char)|IDK|_ZN8CropTile10getTextureEP10TileSourceiiia|
|Tile::getTexture|No|(TileSource*, int, int, int, signed char)|IDK|_ZN4Tile10getTextureEP10TileSourceiiia|
|Tile::getShape|No|(TileSource*, int, int, int, AABB&, bool)|IDK|_ZN4Tile8getShapeEP10TileSourceiiiR4AABBb|
|BedTile::findStandUpPosition|No|(TileSource*, int, int, int, int, TilePos&)|IDK|_ZN7BedTile19findStandUpPositionEP10TileSourceiiiiR7TilePos|
|BedTile::HEAD_DIRECTION_OFFSETS|No|(undefined|IDK|_ZN7BedTile22HEAD_DIRECTION_OFFSETSE|
|BedTile::getSecondPart|No|(TileSource*, int, int, int, TilePos&)|IDK|_ZN7BedTile13getSecondPartEP10TileSourceiiiR7TilePos|
|TileSource::containsLiquid|No|(AABB const&, Material const*)|IDK|_ZN10TileSource14containsLiquidERK4AABBPK8Material|
|TileSource::getTileAndData|No|(int, int, int)|IDK|_ZN10TileSource14getTileAndDataEiii|
|EatTileGoal::canUse|No|()|IDK|_ZN11EatTileGoal6canUseEv|
|Minecart::getPos|No|(Vec3&, float, float, float)|IDK|_ZN8Minecart6getPosER4Vec3fff|
|BaseRailTile::isRail|No|(TileSource*, int, int, int)|IDK|_ZN12BaseRailTile6isRailEP10TileSourceiii|
|BaseRailTile::isRail|No|(int)|IDK|_ZN12BaseRailTile6isRailEi|
|BaseRailTile::isUsesDataBit|No|()|IDK|_ZN12BaseRailTile13isUsesDataBitEv|
|Minecart::EXITS|No|(undefined|IDK|_ZN8Minecart5EXITSE|
|Minecart::getPosOffs|No|(Vec3&, float, float, float, float)|IDK|_ZN8Minecart10getPosOffsER4Vec3ffff|
|Minecart::moveAlongTrack|No|(int, int, int, float, float, int, int)|IDK|_ZN8Minecart14moveAlongTrackEiiiffii|
|Tile::goldenRail|No|(undefined|IDK|_ZN4Tile10goldenRailE|
|ParticleEngine::crack|No|(Entity*, int, int, int, signed char)|IDK|_ZN14ParticleEngine5crackEP6Entityiiia|
|AABB::boundsX|No|() const|IDK|_ZNK4AABB7boundsXEv|
|AABB::boundsY|No|() const|IDK|_ZNK4AABB7boundsYEv|
|AABB::boundsZ|No|() const|IDK|_ZNK4AABB7boundsZEv|
|Particle::setPower|No|(float)|IDK|_ZN8Particle8setPowerEf|
|Particle::scale|No|(float)|IDK|_ZN8Particle5scaleEf|
|TileSource::clip|No|(HitResult&, Vec3 const&, Vec3 const&, bool, bool)|IDK|_ZN10TileSource4clipER9HitResultRK4Vec3S4_bb|
|AABB::isEmpty|No|() const|IDK|_ZNK4AABB7isEmptyEv|
|TileSource::getSeenPercent|No|(Vec3 const&, AABB const&)|IDK|_ZN10TileSource14getSeenPercentERK4Vec3RK4AABB|
|TileSource::getBrightness|No|(LightLayer const&, int, int, int)|IDK|_ZN10TileSource13getBrightnessERK10LightLayeriii|
|TileSource::getBrightness|No|(int, int, int)|IDK|_ZN10TileSource13getBrightnessEiii|
|HangingEntity::getBrightness|No|(float)|IDK|_ZN13HangingEntity13getBrightnessEf|
|LiquidTile::getBrightness|No|(TileSource*, int, int, int)|IDK|_ZN10LiquidTile13getBrightnessEP10TileSourceiii|
|TileSource::getRawBrightness|No|(int, int, int, bool)|IDK|_ZN10TileSource16getRawBrightnessEiiib|
|TileSource::getTopSolidBlock|No|(int, int, bool)|IDK|_ZN10TileSource16getTopSolidBlockEiib|
|TileSource::canSeeSky|No|(int, int, int)|IDK|_ZN10TileSource9canSeeSkyEiii|
|FleeSunGoal::canUse|No|()|IDK|_ZN11FleeSunGoal6canUseEv|
|Level::isDay|No|()|IDK|_ZN5Level5isDayEv|
|TileSource::getHeightmap|No|(int, int)|IDK|_ZN10TileSource12getHeightmapEii|
|BiomeDecorator::_getRandomHeight|No|(int, int, TileSource*, Random&, TilePos const&)|IDK|_ZN14BiomeDecorator16_getRandomHeightEiiP10TileSourceR6RandomRK7TilePos|
|PlainsBiome::decorate|No|(TileSource*, Random&, TilePos const&, bool)|IDK|_ZN11PlainsBiome8decorateEP10TileSourceR6RandomRK7TilePosb|
|DoublePlantFeature::place|No|(TileSource*, int, int, int, Random&, int)|IDK|_ZN18DoublePlantFeature5placeEP10TileSourceiiiR6Randomi|
|Biome::decorate|No|(TileSource*, Random&, TilePos const&, bool)|IDK|_ZN5Biome8decorateEP10TileSourceR6RandomRK7TilePosb|
|TileSource::setBrightness|No|(LightLayer const&, int, int, int, unsigned char)|IDK|_ZN10TileSource13setBrightnessERK10LightLayeriiih|
|TileSource::getTileEntity|No|(int, int, int)|IDK|_ZN10TileSource13getTileEntityEiii|
|NetherReactorTile::use|No|(Player*, int, int, int)|IDK|_ZN17NetherReactorTile3useEP6Playeriii|
|NetherReactorPattern::NetherReactorPattern|No|()|IDK|_ZN20NetherReactorPatternC1Ev|
|NetherReactorPattern::getTileAt|No|(int, int, int)|IDK|_ZN20NetherReactorPattern9getTileAtEiii|
|NetherReactorTileEntity::lightItUp|No|(int, int, int)|IDK|_ZN23NetherReactorTileEntity9lightItUpEiii|
|TileSource::getTilePtr|No|(int, int, int)|IDK|_ZN10TileSource10getTilePtrEiii|
|TileSource::getMaterial|No|(int, int, int)|IDK|_ZN10TileSource11getMaterialEiii|
|CactusTile::canSurvive|No|(TileSource*, int, int, int)|IDK|_ZN10CactusTile10canSurviveEP10TileSourceiii|
|Tile::cactus|No|(undefined|IDK|_ZN4Tile6cactusE|
|RoofTreeFeature::placeLeafAt|No|(TileSource*, int, int, int) const|IDK|_ZNK15RoofTreeFeature11placeLeafAtEP10TileSourceiii|
|Material::vegetable|No|(undefined|IDK|_ZN8Material9vegetableE|
|SavannaTreeFeature::placeLeafAt|No|(TileSource*, TilePos const&) const|IDK|_ZNK18SavannaTreeFeature11placeLeafAtEP10TileSourceRK7TilePos|
|BubbleParticle::normalTick|No|()|IDK|_ZN14BubbleParticle10normalTickEv|
|CakeTile::canSurvive|No|(TileSource*, int, int, int)|IDK|_ZN8CakeTile10canSurviveEP10TileSourceiii|
|ReedTile::mayPlace|No|(TileSource*, int, int, int)|IDK|_ZN8ReedTile8mayPlaceEP10TileSourceiii|
|TopSnowTile::mayPlace|No|(TileSource*, int, int, int)|IDK|_ZN11TopSnowTile8mayPlaceEP10TileSourceiii|
|LiquidTile::getDepth|No|(TileSource*, int, int, int)|IDK|_ZN10LiquidTile8getDepthEP10TileSourceiii|
|LiquidTile::getRenderedDepth|No|(TileSource*, int, int, int)|IDK|_ZN10LiquidTile16getRenderedDepthEP10TileSourceiii|
|LiquidTile::getFlow|No|(TileSource*, int, int, int)|IDK|_ZN10LiquidTile7getFlowEP10TileSourceiii|
|LiquidTile::handleEntityInside|No|(TileSource*, int, int, int, Entity*, Vec3&)|IDK|_ZN10LiquidTile18handleEntityInsideEP10TileSourceiiiP6EntityR4Vec3|
|LiquidTile::getSlopeAngle|No|(TileSource*, int, int, int, Material const*)|IDK|_ZN10LiquidTile13getSlopeAngleEP10TileSourceiiiPK8Material|
|LiquidTile::shouldRenderFace|No|(TileSource*, int, int, int, signed char, AABB const&)|IDK|_ZN10LiquidTile16shouldRenderFaceEP10TileSourceiiiaRK4AABB|
|Material::ice|No|(undefined|IDK|_ZN8Material3iceE|
|TopSnowTile::shouldRenderFace|No|(TileSource*, int, int, int, signed char, AABB const&)|IDK|_ZN11TopSnowTile16shouldRenderFaceEP10TileSourceiiiaRK4AABB|
|SwampTreeFeature::place|No|(TileSource*, int, int, int, Random&) const|IDK|_ZNK16SwampTreeFeature5placeEP10TileSourceiiiR6Random|
|Feature::setTile|No|(TileSource*, TilePos const&, int) const|IDK|_ZNK7Feature7setTileEP10TileSourceRK7TilePosi|
|VineTile::VINE_NORTH|No|(undefined|IDK|_ZN8VineTile10VINE_NORTHE|
|VineTile::VINE_EAST|No|(undefined|IDK|_ZN8VineTile9VINE_EASTE|
|VineTile::VINE_WEST|No|(undefined|IDK|_ZN8VineTile9VINE_WESTE|
|VineTile::VINE_SOUTH|No|(undefined|IDK|_ZN8VineTile10VINE_SOUTHE|
|SavannaTreeFeature::place|No|(TileSource*, int, int, int, Random&) const|IDK|_ZNK18SavannaTreeFeature5placeEP10TileSourceiiiR6Random|
|TreeFeature::isFree|No|(int) const|IDK|_ZNK11TreeFeature6isFreeEi|
|Direction::STEP_X|No|(undefined|IDK|_ZN9Direction6STEP_XE|
(null)
|RoofTreeFeature::place|No|(TileSource*, int, int, int, Random&) const|IDK|_ZNK15RoofTreeFeature5placeEP10TileSourceiiiR6Random|
|TileSource::isTopSolidBlocking|No|(int, int, int)|IDK|_ZN10TileSource18isTopSolidBlockingEiii|
|LiquidTile::animateTick|No|(TileSource*, int, int, int, Random*)|IDK|_ZN10LiquidTile11animateTickEP10TileSourceiiiP6Random|
|bool RakNet::BitStream::Read<unsigned int>|No|(unsigned int&)|IDK|_ZN6RakNet9BitStream4ReadIjEEbRT_|
|bool RakNet::BitStream::Read<int>|No|(int&)|IDK|_ZN6RakNet9BitStream4ReadIiEEbRT_|
|TileEventPacket::read|No|(RakNet::BitStream*)|IDK|_ZN15TileEventPacket4readEPN6RakNet9BitStreamE|
|LevelEventPacket::read|No|(RakNet::BitStream*)|IDK|_ZN16LevelEventPacket4readEPN6RakNet9BitStreamE|
|AddPaintingPacket::read|No|(RakNet::BitStream*)|IDK|_ZN17AddPaintingPacket4readEPN6RakNet9BitStreamE|
|AddMobPacket::read|No|(RakNet::BitStream*)|IDK|_ZN12AddMobPacket4readEPN6RakNet9BitStreamE|
|PacketUtil::Rot_charToDegrees|No|(signed char)|IDK|_ZN10PacketUtil17Rot_charToDegreesEa|
|std::vector<TextureUVCoordinateSet, std::allocator<TextureUVCoordinateSet> >::operator=|No|(std::vector<TextureUVCoordinateSet, std::allocator<TextureUVCoordinateSet> > const&)|IDK|_ZNSt6vectorI22TextureUVCoordinateSetSaIS0_EEaSERKS2_|
|LiquidTile::LiquidTile|No|(int, Material const*, std::string const&, std::string const&)|IDK|_ZN10LiquidTileC2EiPK8MaterialRKSsS4_|
|LiquidTile::LiquidTile|No|(int, Material const*, std::string const&, std::string const&)|IDK|_ZN10LiquidTileC1EiPK8MaterialRKSsS4_|
|ClothTile::ClothTile|No|(int)|IDK|_ZN9ClothTileC2Ei|
|Material::cloth|No|(undefined|IDK|_ZN8Material5clothE|
|ClothTile::ClothTile|No|(int)|IDK|_ZN9ClothTileC1Ei|
|CropTile::CropTile|No|(int, std::string const&)|IDK|_ZN8CropTileC2EiRKSs|
|CropTile::CropTile|No|(int, std::string const&)|IDK|_ZN8CropTileC1EiRKSs|
|FlowerTile::FlowerTile|No|(int, int)|IDK|_ZN10FlowerTileC2Eii|
|FlowerTile::FlowerTile|No|(int, int)|IDK|_ZN10FlowerTileC1Eii|
|SandStoneTile::SandStoneTile|No|(int, std::string const&)|IDK|_ZN13SandStoneTileC2EiRKSs|
|vtable for SandStoneTile|No|(undefined|IDK|_ZTV13SandStoneTile|
|SandStoneTile::SandStoneTile|No|(int, std::string const&)|IDK|_ZN13SandStoneTileC1EiRKSs|
|bool RakNet::BitStream::Read<short>|No|(short&)|IDK|_ZN6RakNet9BitStream4ReadIsEEbRT_|
|bool RakNet::BitStream::Read<float>|No|(float&)|IDK|_ZN6RakNet9BitStream4ReadIfEEbRT_|
|AddEntityPacket::read|No|(RakNet::BitStream*)|IDK|_ZN15AddEntityPacket4readEPN6RakNet9BitStreamE|
|AddItemEntityPacket::read|No|(RakNet::BitStream*)|IDK|_ZN19AddItemEntityPacket4readEPN6RakNet9BitStreamE|
|StartGamePacket::read|No|(RakNet::BitStream*)|IDK|_ZN15StartGamePacket4readEPN6RakNet9BitStreamE|
|AddPlayerPacket::read|No|(RakNet::BitStream*)|IDK|_ZN15AddPlayerPacket4readEPN6RakNet9BitStreamE|
|std::vector<ItemInstance, std::allocator<ItemInstance> >::operator=|No|(std::vector<ItemInstance, std::allocator<ItemInstance> > const&)|IDK|_ZNSt6vectorI12ItemInstanceSaIS0_EEaSERKS2_|
|BaseContainerMenu::broadcastChanges|No|()|IDK|_ZN17BaseContainerMenu16broadcastChangesEv|
|ItemInstance::matches|No|(ItemInstance const*, ItemInstance const*)|IDK|_ZN12ItemInstance7matchesEPKS_S1_|
|FurnaceMenu::broadcastChanges|No|()|IDK|_ZN11FurnaceMenu16broadcastChangesEv|
|CreativeInventoryScreen::render|No|(int, int, float)|IDK|_ZN23CreativeInventoryScreen6renderEiif|
|ControllerButtonRenderer::renderControllerButtons|No|(int, int, ControllerButtonRenderer::ButtonIcon, std::string const&)|IDK|_ZN24ControllerButtonRenderer23renderControllerButtonsEiiNS_10ButtonIconERKSs|
|ControllerButtonRenderer::renderDPadIcon|No|(int, int, std::string const&)|IDK|_ZN24ControllerButtonRenderer14renderDPadIconEiiRKSs|
|std::_Rb_tree<std::string, std::pair<std::string const, Stopwatch*>, std::_Select1st<std::pair<std::string const, Stopwatch*> >, std::less<std::string>, std::allocator<std::pair<std::string const, Stopwatch*> > >::_M_erase|No|(std::_Rb_tree_node<std::pair<std::string const, Stopwatch*> >*)|IDK|_ZNSt8_Rb_treeISsSt4pairIKSsP9StopwatchESt10_Select1stIS4_ESt4lessISsESaIS4_EE8_M_eraseEPSt13_Rb_tree_nodeIS4_E|
|StopwatchHandler::clearAll|No|()|IDK|_ZN16StopwatchHandler8clearAllEv|
(null)
(null)
|Minecart::setDamage|No|(float)|IDK|_ZN8Minecart9setDamageEf|
|Minecart::setHurtTime|No|(int)|IDK|_ZN8Minecart11setHurtTimeEi|
|Minecart::setHurtDir|No|(int)|IDK|_ZN8Minecart10setHurtDirEi|
|Minecart::hurt|No|(Entity*, int)|IDK|_ZN8Minecart4hurtEP6Entityi|
|Minecart::animateHurt|No|()|IDK|_ZN8Minecart11animateHurtEv|
|Minecart::setCustomDisplay|No|(bool)|IDK|_ZN8Minecart16setCustomDisplayEb|
|Minecart::setDisplayOffset|No|(int)|IDK|_ZN8Minecart16setDisplayOffsetEi|
|Minecart::setDisplayTile|No|(int)|IDK|_ZN8Minecart14setDisplayTileEi|
|Minecart::setDisplayData|No|(int)|IDK|_ZN8Minecart14setDisplayDataEi|
|Villager::setProfession|No|(int)|IDK|_ZN8Villager13setProfessionEi|
|Villager::finalizeMobSpawn|No|()|IDK|_ZN8Villager16finalizeMobSpawnEv|
|Pig::setSaddle|No|(bool)|IDK|_ZN3Pig9setSaddleEb|
|Spider::setClimbing|No|(bool)|IDK|_ZN6Spider11setClimbingEb|
|Spider::normalTick|No|()|IDK|_ZN6Spider10normalTickEv|
|Monster::normalTick|No|()|IDK|_ZN7Monster10normalTickEv|
(null)
(null)
|ListTag::copy|No|() const|IDK|_ZNK7ListTag4copyEv|
|ListTag::load|No|(IDataInput*)|IDK|_ZN7ListTag4loadEP10IDataInput|
|Tag::newTag|No|(char, std::string const&)|IDK|_ZN3Tag6newTagEcRKSs|
|Tag::NullString|No|(undefined|IDK|_ZN3Tag10NullStringE|
|std::_Rb_tree<std::string, std::pair<std::string const, Tag*>, std::_Select1st<std::pair<std::string const, Tag*> >, std::less<std::string>, std::allocator<std::pair<std::string const, Tag*> > >::_M_erase|No|(std::_Rb_tree_node<std::pair<std::string const, Tag*> >*)|IDK|_ZNSt8_Rb_treeISsSt4pairIKSsP3TagESt10_Select1stIS4_ESt4lessISsESaIS4_EE8_M_eraseEPSt13_Rb_tree_nodeIS4_E|
|CompoundTag::~CompoundTag|No|()|IDK|_ZN11CompoundTagD2Ev|
|vtable for CompoundTag|No|(undefined|IDK|_ZTV11CompoundTag|
|CompoundTag::~CompoundTag|No|()|IDK|_ZN11CompoundTagD1Ev|
|CompoundTag::~CompoundTag|No|()|IDK|_ZN11CompoundTagD0Ev|
|LevelChunk::serializeTileEntities|No|(IDataOutput&) const|IDK|_ZNK10LevelChunk21serializeTileEntitiesER11IDataOutput|
|std::_Rb_tree<std::string, std::pair<std::string const, Tag*>, std::_Select1st<std::pair<std::string const, Tag*> >, std::less<std::string>, std::allocator<std::pair<std::string const, Tag*> > >::find|No|(std::string const&) const|IDK|_ZNKSt8_Rb_treeISsSt4pairIKSsP3TagESt10_Select1stIS4_ESt4lessISsESaIS4_EE4findERS1_|
|CompoundTag::getString|No|(std::string const&) const|IDK|_ZNK11CompoundTag9getStringERKSs|
|LevelChunk::_deserializeEntity|No|(TileSource&, IDataInput&)|IDK|_ZN10LevelChunk18_deserializeEntityER10TileSourceR10IDataInput|
|Tag::readNamedTag|No|(IDataInput*)|IDK|_ZN3Tag12readNamedTagEP10IDataInput|
|EntityFactory::loadEntity|No|(CompoundTag*, TileSource&)|IDK|_ZN13EntityFactory10loadEntityEP11CompoundTagR10TileSource|
|Entity::RIDING_TAG|No|(undefined|IDK|_ZN6Entity10RIDING_TAGE|
|LevelChunk::tick|No|(Player*, Tick const&)|IDK|_ZN10LevelChunk4tickEP6PlayerRK4Tick|
|Util::freeStringMemory|No|(std::string&)|IDK|_ZN4Util16freeStringMemoryERSs|
|AABB::AABB|No|(Vec3 const&, Vec3 const&)|IDK|_ZN4AABBC1ERK4Vec3S2_|
|Level::getMobSpawner|No|() const|IDK|_ZNK5Level13getMobSpawnerEv|
|MobFactory::postProcessSpawnMobs|No|(TileSource*, int, int, Random*)|IDK|_ZN10MobFactory20postProcessSpawnMobsEP10TileSourceiiP6Random|
|Level::getChunkSource|No|() const|IDK|_ZNK5Level14getChunkSourceEv|
|vtable for StringByteInput|No|(undefined|IDK|_ZTV15StringByteInput|
|FallingTile::readAdditionalSaveData|No|(CompoundTag*)|IDK|_ZN11FallingTile22readAdditionalSaveDataEP11CompoundTag|
|Villager::readAdditionalSaveData|No|(CompoundTag*)|IDK|_ZN8Villager22readAdditionalSaveDataEP11CompoundTag|
|AgableMob::readAdditionalSaveData|No|(CompoundTag*)|IDK|_ZN9AgableMob22readAdditionalSaveDataEP11CompoundTag|
|HangingEntity::readAdditionalSaveData|No|(CompoundTag*)|IDK|_ZN13HangingEntity22readAdditionalSaveDataEP11CompoundTag|
|Minecart::readAdditionalSaveData|No|(CompoundTag*)|IDK|_ZN8Minecart22readAdditionalSaveDataEP11CompoundTag|
(null)
(null)
|TouchscreenInput::onConfigChanged|No|(Config const&)|IDK|_ZN16TouchscreenInput15onConfigChangedERK6Config|
|vtable for RectangleArea|No|(undefined|IDK|_ZTV13RectangleArea|
|TouchscreenInput::TouchscreenInput|No|(Minecraft*, Options*)|IDK|_ZN16TouchscreenInputC2EP9MinecraftP7Options|
|MeshBuffer::MeshBuffer|No|()|IDK|_ZN10MeshBufferC1Ev|
|createConfig|No|(Minecraft*)|IDK|_Z12createConfigP9Minecraft|
|TouchscreenInput::TouchscreenInput|No|(Minecraft*, Options*)|IDK|_ZN16TouchscreenInputC1EP9MinecraftP7Options|
(null)
(null)
(null)
(null)
|DBChunkStorage::acquireDiscarded|No|(std::unique_ptr<LevelChunk, std::default_delete<LevelChunk> >&)|IDK|_ZN14DBChunkStorage16acquireDiscardedERSt10unique_ptrI10LevelChunkSt14default_deleteIS1_EE|
|std::_Hashtable<ChunkPos, ChunkPos, std::allocator<ChunkPos>, std::__detail::_Identity, std::equal_to<ChunkPos>, std::hash<ChunkPos>, std::__detail::_Mod_range_hashing, std::__detail::_Default_ranged_hash, std::__detail::_Prime_rehash_policy, std::__detail::_Hashtable_traits<true, true, true> >::count|No|(ChunkPos const&) const|IDK|_ZNKSt10_HashtableI8ChunkPosS0_SaIS0_ENSt8__detail9_IdentityESt8equal_toIS0_ESt4hashIS0_ENS2_18_Mod_range_hashingENS2_20_Default_ranged_hashENS2_20_Prime_rehash_policyENS2_17_Hashtable_traitsILb1ELb1ELb1EEEE5countERKS0_|
(null)
(null)
(null)
|Sensing::canSee|No|(Entity*)|IDK|_ZN7Sensing6canSeeEP6Entity|
|TargetGoal::canContinueToUse|No|()|IDK|_ZN10TargetGoal16canContinueToUseEv|
|Mob::getSensing|No|()|IDK|_ZN3Mob10getSensingEv|
(null)
(null)
|FurnaceMenu::getItems|No|()|IDK|_ZN11FurnaceMenu8getItemsEv|
(null)
(null)
|LevelChunk::deferLightEmitter|No|(TilePos const&)|IDK|_ZN10LevelChunk17deferLightEmitterERK7TilePos|
|std::_Hashtable<ChunkTilePos, std::pair<ChunkTilePos const, std::unique_ptr<TileEntity, std::default_delete<TileEntity> > >, std::allocator<std::pair<ChunkTilePos const, std::unique_ptr<TileEntity, std::default_delete<TileEntity> > > >, std::__detail::_Select1st, std::equal_to<ChunkTilePos>, std::hash<ChunkTilePos>, std::__detail::_Mod_range_hashing, std::__detail::_Default_ranged_hash, std::__detail::_Prime_rehash_policy, std::__detail::_Hashtable_traits<true, false, true> >::find|No|(ChunkTilePos const&)|IDK|_ZNSt10_HashtableI12ChunkTilePosSt4pairIKS0_St10unique_ptrI10TileEntitySt14default_deleteIS4_EEESaIS8_ENSt8__detail10_Select1stESt8equal_toIS0_ESt4hashIS0_ENSA_18_Mod_range_hashingENSA_20_Default_ranged_hashENSA_20_Prime_rehash_policyENSA_17_Hashtable_traitsILb1ELb0ELb1EEEE4findERS2_|
|std::_Rb_tree<std::string, std::pair<std::string const, Stopwatch*>, std::_Select1st<std::pair<std::string const, Stopwatch*> >, std::less<std::string>, std::allocator<std::pair<std::string const, Stopwatch*> > >::find|No|(std::string const&)|IDK|_ZNSt8_Rb_treeISsSt4pairIKSsP9StopwatchESt10_Select1stIS4_ESt4lessISsESaIS4_EE4findERS1_|
(null)
|StopwatchHandler::get|No|(std::string const&)|IDK|_ZN16StopwatchHandler3getERKSs|
(null)
(null)
|OldLogTile::OldLogTile|No|(int)|IDK|_ZN10OldLogTileC2Ei|
|LogTile::LogTile|No|(int)|IDK|_ZN7LogTileC2Ei|
|vtable for OldLogTile|No|(undefined|IDK|_ZTV10OldLogTile|
|OldLogTile::OldLogTile|No|(int)|IDK|_ZN10OldLogTileC1Ei|
(null)
(null)
(null)
(null)
|MoveEntityPacket::read|No|(RakNet::BitStream*)|IDK|_ZN16MoveEntityPacket4readEPN6RakNet9BitStreamE|
(null)
(null)
|ServerSideNetworkHandler::addSetEntityMotionPacket|No|(Entity const*)|IDK|_ZN24ServerSideNetworkHandler24addSetEntityMotionPacketEPK6Entity|
(null)
(null)
|SetEntityMotionPacket::read|No|(RakNet::BitStream*)|IDK|_ZN21SetEntityMotionPacket4readEPN6RakNet9BitStreamE|
(null)
(null)
|GuiElementContainer::addChild|No|(std::shared_ptr<GuiElement>)|IDK|_ZN19GuiElementContainer8addChildESt10shared_ptrI10GuiElementE|
(null)
(null)
(null)
(null)
|Village::readAdditionalSaveData|No|(CompoundTag*)|IDK|_ZN7Village22readAdditionalSaveDataEP11CompoundTag|
|Village::addDoorInfo|No|(DoorInfo const&)|IDK|_ZN7Village11addDoorInfoERK8DoorInfo|
(null)
(null)
|ServerSideNetworkHandler::addRotateHeadPacket|No|(Mob const*)|IDK|_ZN24ServerSideNetworkHandler19addRotateHeadPacketEPK3Mob|
(null)
(null)
|RotateHeadPacket::read|No|(RakNet::BitStream*)|IDK|_ZN16RotateHeadPacket4readEPN6RakNet9BitStreamE|
(null)
(null)
|TileSource::getCubes|No|(AABB const&, float*, bool)|IDK|_ZN10TileSource8getCubesERK4AABBPfb|
|Tile::addAABB|No|(AABB const&, AABB const*, std::vector<AABB, std::allocator<AABB> >&)|IDK|_ZN4Tile7addAABBERK4AABBPS1_RSt6vectorIS0_SaIS0_EE|
|AABB::intersects|No|(AABB const&) const|IDK|_ZNK4AABB10intersectsERKS_|
|ThinFenceTile::addAABBs|No|(TileSource*, int, int, int, AABB const*, std::vector<AABB, std::allocator<AABB> >&)|IDK|_ZN13ThinFenceTile8addAABBsEP10TileSourceiiiPK4AABBRSt6vectorIS2_SaIS2_EE|
|Tile::addAABBs|No|(TileSource*, int, int, int, AABB const*, std::vector<AABB, std::allocator<AABB> >&)|IDK|_ZN4Tile8addAABBsEP10TileSourceiiiPK4AABBRSt6vectorIS2_SaIS2_EE|
(null)
(null)
|std::_Rb_tree<std::string, std::pair<std::string const, Tag*>, std::_Select1st<std::pair<std::string const, Tag*> >, std::less<std::string>, std::allocator<std::pair<std::string const, Tag*> > >::_M_get_insert_unique_pos|No|(std::string const&)|IDK|_ZNSt8_Rb_treeISsSt4pairIKSsP3TagESt10_Select1stIS4_ESt4lessISsESaIS4_EE24_M_get_insert_unique_posERS1_|
|CompoundTag::copy|No|() const|IDK|_ZNK11CompoundTag4copyEv|
|CompoundTag::putByte|No|(std::string const&, char)|IDK|_ZN11CompoundTag7putByteERKSsc|
|FallingTile::addAdditionalSaveData|No|(CompoundTag*)|IDK|_ZN11FallingTile21addAdditionalSaveDataEP11CompoundTag|
|CompoundTag::putInt|No|(std::string const&, int)|IDK|_ZN11CompoundTag6putIntERKSsi|
|HangingEntity::addAdditionalSaveData|No|(CompoundTag*)|IDK|_ZN13HangingEntity21addAdditionalSaveDataEP11CompoundTag|
|Villager::addAdditionalSaveData|No|(CompoundTag*)|IDK|_ZN8Villager21addAdditionalSaveDataEP11CompoundTag|
|AgableMob::addAdditionalSaveData|No|(CompoundTag*)|IDK|_ZN9AgableMob21addAdditionalSaveDataEP11CompoundTag|
(null)
|Minecart::addAdditionalSaveData|No|(CompoundTag*)|IDK|_ZN8Minecart21addAdditionalSaveDataEP11CompoundTag|
|CompoundTag::put|No|(std::string const&, Tag*)|IDK|_ZN11CompoundTag3putERKSsP3Tag|
|CompoundTag::load|No|(IDataInput*)|IDK|_ZN11CompoundTag4loadEP10IDataInput|
(null)
(null)
|LevelChunk::addEntity|No|(Entity&)|IDK|_ZN10LevelChunk9addEntityER6Entity|
(null)
(null)
|LevelChunk::moveEntity|No|(std::unique_ptr<Entity, std::default_delete<Entity> >&)|IDK|_ZN10LevelChunk10moveEntityERSt10unique_ptrI6EntitySt14default_deleteIS1_EE|
(null)
(null)
|LevelChunk::getEntities|No|(Entity*, AABB const&, std::vector<Entity*, std::allocator<Entity*> >&)|IDK|_ZN10LevelChunk11getEntitiesEP6EntityRK4AABBRSt6vectorIS1_SaIS1_EE|
|TileSource::getEntities|No|(int, AABB const&, Entity*)|IDK|_ZN10TileSource11getEntitiesEiRK4AABBP6Entity|
|Entity::isInstanceOf|No|(int) const|IDK|_ZNK6Entity12isInstanceOfEi|
|Level::getEntityIdMap|No|() const|IDK|_ZNK5Level14getEntityIdMapEv|
|Village::countPopulation|No|()|IDK|_ZN7Village15countPopulationEv|
|AABB::AABB|No|(float, float, float, float, float, float)|IDK|_ZN4AABBC1Effffff|
|Village::tick|No|(int)|IDK|_ZN7Village4tickEi|
|TileSource::getNearestEntityOfType|No|(Entity*, float, float, float, float, int)|IDK|_ZN10TileSource22getNearestEntityOfTypeEP6Entityffffi|
|AABB::grow|No|(Vec3 const&) const|IDK|_ZNK4AABB4growERK4Vec3|
|NearestAttackableTargetGoal::canUse|No|()|IDK|_ZN27NearestAttackableTargetGoal6canUseEv|
|SpiderTargetGoal::canUse|No|()|IDK|_ZN16SpiderTargetGoal6canUseEv|
|TileSource::getEntities|No|(Entity*, AABB const&)|IDK|_ZN10TileSource11getEntitiesEP6EntityRK4AABB|
|HangingEntity::survives|No|()|IDK|_ZN13HangingEntity8survivesEv|
|Minecart::normalTick|No|()|IDK|_ZN8Minecart10normalTickEv|
|Tile::activatorRail|No|(undefined|IDK|_ZN4Tile13activatorRailE|
|vtable for SetEntityLinkPacket|No|(undefined|IDK|_ZTV19SetEntityLinkPacket|
|TileSource::isUnobstructedByEntities|No|(AABB const&, Entity*)|IDK|_ZN10TileSource24isUnobstructedByEntitiesERK4AABBP6Entity|
|TileSource::mayPlace|No|(unsigned char, TilePos const&, signed char, Mob*, bool, Entity*)|IDK|_ZN10TileSource8mayPlaceEhRK7TilePosaP3MobbP6Entity|
|std::_Rb_tree<std::string, std::pair<std::string const, Stopwatch*>, std::_Select1st<std::pair<std::string const, Stopwatch*> >, std::less<std::string>, std::allocator<std::pair<std::string const, Stopwatch*> > >::equal_range|No|(std::string const&)|IDK|_ZNSt8_Rb_treeISsSt4pairIKSsP9StopwatchESt10_Select1stIS4_ESt4lessISsESaIS4_EE11equal_rangeERS1_|
|StopwatchHandler::clear|No|(std::string const&)|IDK|_ZN16StopwatchHandler5clearERKSs|
(null)
(null)
|NewLogTile::NewLogTile|No|(int)|IDK|_ZN10NewLogTileC2Ei|
|vtable for NewLogTile|No|(undefined|IDK|_ZTV10NewLogTile|
|NewLogTile::NewLogTile|No|(int)|IDK|_ZN10NewLogTileC1Ei|
|Tile::initTiles|No|(std::shared_ptr<TextureAtlas>)|IDK|_ZN4Tile9initTilesESt10shared_ptrI12TextureAtlasE|
|GrassTile::GrassTile|No|(int)|IDK|_ZN9GrassTileC1Ei|
|WoodTile::WoodTile|No|(int)|IDK|_ZN8WoodTileC1Ei|
|Sapling::Sapling|No|(int, std::string const&)|IDK|_ZN7SaplingC1EiRKSs|
|LiquidTileDynamic::LiquidTileDynamic|No|(int, Material const*, std::string const&, std::string const&)|IDK|_ZN17LiquidTileDynamicC1EiPK8MaterialRKSsS4_|
|LiquidTileStatic::LiquidTileStatic|No|(int, Material const*, std::string const&, std::string const&)|IDK|_ZN16LiquidTileStaticC1EiPK8MaterialRKSsS4_|
|OldLeafTile::OldLeafTile|No|(int, std::string const&)|IDK|_ZN11OldLeafTileC1EiRKSs|
|Tile::SOUND_STONE|No|(undefined|IDK|_ZN4Tile11SOUND_STONEE|
|Tile::SOUND_GRASS|No|(undefined|IDK|_ZN4Tile11SOUND_GRASSE|
|Tile::SOUND_GRAVEL|No|(undefined|IDK|_ZN4Tile12SOUND_GRAVELE|
|Tile::SOUND_WOOD|No|(undefined|IDK|_ZN4Tile10SOUND_WOODE|
|Tile::wood|No|(undefined|IDK|_ZN4Tile4woodE|
|Tile::unbreakable|No|(undefined|IDK|_ZN4Tile11unbreakableE|
|Tile::SOUND_SAND|No|(undefined|IDK|_ZN4Tile10SOUND_SANDE|
|vtable for GravelTile|No|(undefined|IDK|_ZTV10GravelTile|
|vtable for OreTile|No|(undefined|IDK|_ZTV7OreTile|
|PoweredRailTile::PoweredRailTile|No|(int)|IDK|_ZN15PoweredRailTileC1Ei|
|TallGrass::TallGrass|No|(int, std::string const&)|IDK|_ZN9TallGrassC1EiRKSs|
|DeadBush::DeadBush|No|(int, std::string const&)|IDK|_ZN8DeadBushC1EiRKSs|
|Mushroom::Mushroom|No|(int, std::string const&)|IDK|_ZN8MushroomC1EiRKSs|
|StoneSlabTile::StoneSlabTile|No|(int, bool)|IDK|_ZN13StoneSlabTileC1Eib|
|TntTile::TntTile|No|(int, std::string const&)|IDK|_ZN7TntTileC1EiRKSs|
|Tile::sponge|No|(undefined|IDK|_ZN4Tile6spongeE|
|Material::glass|No|(undefined|IDK|_ZN8Material5glassE|
|vtable for GlassTile|No|(undefined|IDK|_ZTV9GlassTile|
|Tile::SOUND_GLASS|No|(undefined|IDK|_ZN4Tile11SOUND_GLASSE|
|Tile::lapisBlock|No|(undefined|IDK|_ZN4Tile10lapisBlockE|
|Tile::sandStone|No|(undefined|IDK|_ZN4Tile9sandStoneE|
|Tile::bed|No|(undefined|IDK|_ZN4Tile3bedE|
|Tile::SOUND_METAL|No|(undefined|IDK|_ZN4Tile11SOUND_METALE|
|Material::web|No|(undefined|IDK|_ZN8Material3webE|
|vtable for WebTile|No|(undefined|IDK|_ZTV7WebTile|
|Tile::web|No|(undefined|IDK|_ZN4Tile3webE|
|Tile::deadBush|No|(undefined|IDK|_ZN4Tile8deadBushE|
|Tile::SOUND_CLOTH|No|(undefined|IDK|_ZN4Tile11SOUND_CLOTHE|
|Tile::cloth|No|(undefined|IDK|_ZN4Tile5clothE|
|Material::metal|No|(undefined|IDK|_ZN8Material5metalE|
|vtable for MetalTile|No|(undefined|IDK|_ZTV9MetalTile|
|Tile::goldBlock|No|(undefined|IDK|_ZN4Tile9goldBlockE|
|Tile::ironBlock|No|(undefined|IDK|_ZN4Tile9ironBlockE|
|Tile::stoneSlab|No|(undefined|IDK|_ZN4Tile9stoneSlabE|
|Tile::tnt|No|(undefined|IDK|_ZN4Tile3tntE|
|TorchTile::TorchTile|No|(int, std::string const&)|IDK|_ZN9TorchTileC1EiRKSs|
|StairTile::StairTile|No|(int, Tile*, int)|IDK|_ZN9StairTileC1EiP4Tilei|
|ChestTile::ChestTile|No|(int)|IDK|_ZN9ChestTileC1Ei|
|FarmTile::FarmTile|No|(int)|IDK|_ZN8FarmTileC1Ei|
|FurnaceTile::FurnaceTile|No|(int, bool)|IDK|_ZN11FurnaceTileC1Eib|
|SignTile::SignTile|No|(int, bool)|IDK|_ZN8SignTileC1Eib|
|DoorTile::DoorTile|No|(int, Material const*)|IDK|_ZN8DoorTileC1EiPK8Material|
|LadderTile::LadderTile|No|(int, std::string const&)|IDK|_ZN10LadderTileC1EiRKSs|
|RailTile::RailTile|No|(int)|IDK|_ZN8RailTileC1Ei|
|vtable for BookshelfTile|No|(undefined|IDK|_ZTV13BookshelfTile|
|vtable for ObsidianTile|No|(undefined|IDK|_ZTV12ObsidianTile|
|Tile::torch|No|(undefined|IDK|_ZN4Tile5torchE|
|vtable for MobSpawnerTile|No|(undefined|IDK|_ZTV14MobSpawnerTile|
|Tile::mobSpawner|No|(undefined|IDK|_ZN4Tile10mobSpawnerE|
|Tile::stairs_wood|No|(undefined|IDK|_ZN4Tile11stairs_woodE|
|Tile::chest|No|(undefined|IDK|_ZN4Tile5chestE|
|Tile::diamondBlock|No|(undefined|IDK|_ZN4Tile12diamondBlockE|
|Tile::workBench|No|(undefined|IDK|_ZN4Tile9workBenchE|
|Tile::crops|No|(undefined|IDK|_ZN4Tile5cropsE|
|Tile::furnace|No|(undefined|IDK|_ZN4Tile7furnaceE|
|Tile::furnace_lit|No|(undefined|IDK|_ZN4Tile11furnace_litE|
|Tile::sign|No|(undefined|IDK|_ZN4Tile4signE|
|Tile::ladder|No|(undefined|IDK|_ZN4Tile6ladderE|
|Tile::rail|No|(undefined|IDK|_ZN4Tile4railE|
|Tile::stairs_stone|No|(undefined|IDK|_ZN4Tile12stairs_stoneE|
|Tile::wallSign|No|(undefined|IDK|_ZN4Tile8wallSignE|
|Tile::door_iron|No|(undefined|IDK|_ZN4Tile9door_ironE|
|vtable for RedStoneOreTile|No|(undefined|IDK|_ZTV15RedStoneOreTile|
|FenceTile::FenceTile|No|(int, std::string const&, Material const*)|IDK|_ZN9FenceTileC1EiRKSsPK8Material|
|PumpkinTile::PumpkinTile|No|(int, bool)|IDK|_ZN11PumpkinTileC1Eib|
|LightGemTile::LightGemTile|No|(int, std::string const&, Material const*)|IDK|_ZN12LightGemTileC1EiRKSsPK8Material|
|TrapDoorTile::TrapDoorTile|No|(int, Material const*)|IDK|_ZN12TrapDoorTileC1EiPK8Material|
|HugeMushroomTile::HugeMushroomTile|No|(int, Material const*, int)|IDK|_ZN16HugeMushroomTileC1EiPK8Materiali|
|Tile::redStoneOre_lit|No|(undefined|IDK|_ZN4Tile15redStoneOre_litE|
|Material::topSnow|No|(undefined|IDK|_ZN8Material7topSnowE|
|vtable for TopSnowTile|No|(undefined|IDK|_ZTV11TopSnowTile|
|vtable for IceTile|No|(undefined|IDK|_ZTV7IceTile|
|Tile::ice|No|(undefined|IDK|_ZN4Tile3iceE|
|Material::snow|No|(undefined|IDK|_ZN8Material4snowE|
|vtable for SnowTile|No|(undefined|IDK|_ZTV8SnowTile|
|vtable for ClayTile|No|(undefined|IDK|_ZTV8ClayTile|
|vtable for ReedTile|No|(undefined|IDK|_ZTV8ReedTile|
|Tile::reeds|No|(undefined|IDK|_ZN4Tile5reedsE|
|Tile::fence|No|(undefined|IDK|_ZN4Tile5fenceE|
|Tile::pumpkin|No|(undefined|IDK|_ZN4Tile7pumpkinE|
|Tile::netherrack|No|(undefined|IDK|_ZN4Tile10netherrackE|
|Tile::lightGem|No|(undefined|IDK|_ZN4Tile8lightGemE|
|Tile::litPumpkin|No|(undefined|IDK|_ZN4Tile10litPumpkinE|
|Tile::cake|No|(undefined|IDK|_ZN4Tile4cakeE|
|vtable for InvisibleTile|No|(undefined|IDK|_ZTV13InvisibleTile|
|Tile::trapdoor|No|(undefined|IDK|_ZN4Tile8trapdoorE|
|Tile::monsterStoneEgg|No|(undefined|IDK|_ZN4Tile15monsterStoneEggE|
|Tile::redMushroomBlock|No|(undefined|IDK|_ZN4Tile16redMushroomBlockE|
|Tile::ironFence|No|(undefined|IDK|_ZN4Tile9ironFenceE|
|MelonTile::MelonTile|No|(int)|IDK|_ZN9MelonTileC1Ei|
|VineTile::VineTile|No|(int)|IDK|_ZN8VineTileC1Ei|
|FenceGateTile::FenceGateTile|No|(int, std::string const&)|IDK|_ZN13FenceGateTileC1EiRKSs|
|MyceliumTile::MyceliumTile|No|(int)|IDK|_ZN12MyceliumTileC1Ei|
|WaterlilyTile::WaterlilyTile|No|(int)|IDK|_ZN13WaterlilyTileC1Ei|
|EndPortalFrameTile::EndPortalFrameTile|No|(int)|IDK|_ZN18EndPortalFrameTileC1Ei|
|CocoaTile::CocoaTile|No|(int)|IDK|_ZN9CocoaTileC1Ei|
|WallTile::WallTile|No|(int, Tile*)|IDK|_ZN8WallTileC1EiP4Tile|
|CarrotTile::CarrotTile|No|(int)|IDK|_ZN10CarrotTileC1Ei|
|PotatoTile::PotatoTile|No|(int)|IDK|_ZN10PotatoTileC1Ei|
|WoodSlabTile::WoodSlabTile|No|(int, bool)|IDK|_ZN12WoodSlabTileC1Eib|
|Tile::thinGlass|No|(undefined|IDK|_ZN4Tile9thinGlassE|
|Tile::pumpkinStem|No|(undefined|IDK|_ZN4Tile11pumpkinStemE|
|Tile::melonStem|No|(undefined|IDK|_ZN4Tile9melonStemE|
|Tile::fenceGate|No|(undefined|IDK|_ZN4Tile9fenceGateE|
|Tile::stairs_brick|No|(undefined|IDK|_ZN4Tile12stairs_brickE|
|Tile::waterlily|No|(undefined|IDK|_ZN4Tile9waterlilyE|
|Tile::endPortalFrame|No|(undefined|IDK|_ZN4Tile14endPortalFrameE|
|Tile::endStone|No|(undefined|IDK|_ZN4Tile8endStoneE|
|Tile::cocoa|No|(undefined|IDK|_ZN4Tile5cocoaE|
|Tile::emeraldBlock|No|(undefined|IDK|_ZN4Tile12emeraldBlockE|
|Tile::woodStairsDark|No|(undefined|IDK|_ZN4Tile14woodStairsDarkE|
|Tile::woodStairsBirch|No|(undefined|IDK|_ZN4Tile15woodStairsBirchE|
|Tile::woodStairsJungle|No|(undefined|IDK|_ZN4Tile16woodStairsJungleE|
|Tile::stairs_stoneBrickSmooth|No|(undefined|IDK|_ZN4Tile23stairs_stoneBrickSmoothE|
|Tile::netherBrick|No|(undefined|IDK|_ZN4Tile11netherBrickE|
|Tile::stairs_netherBricks|No|(undefined|IDK|_ZN4Tile19stairs_netherBricksE|
|Tile::stairs_sandStone|No|(undefined|IDK|_ZN4Tile16stairs_sandStoneE|
|Tile::cobbleWall|No|(undefined|IDK|_ZN4Tile10cobbleWallE|
|Tile::carrots|No|(undefined|IDK|_ZN4Tile7carrotsE|
|Tile::potatoes|No|(undefined|IDK|_ZN4Tile8potatoesE|
|Tile::quartzBlock|No|(undefined|IDK|_ZN4Tile11quartzBlockE|
|Tile::stairs_quartz|No|(undefined|IDK|_ZN4Tile13stairs_quartzE|
|NewLeafTile::NewLeafTile|No|(int, std::string const&)|IDK|_ZN11NewLeafTileC1EiRKSs|
|WoolCarpetTile::WoolCarpetTile|No|(int)|IDK|_ZN14WoolCarpetTileC1Ei|
|DoublePlantTile::DoublePlantTile|No|(int)|IDK|_ZN15DoublePlantTileC1Ei|
|PodzolTile::PodzolTile|No|(int)|IDK|_ZN10PodzolTileC1Ei|
|BeetrootTile::BeetrootTile|No|(int)|IDK|_ZN12BeetrootTileC1Ei|
|FireTile::FireTile|No|(int, std::string const&)|IDK|_ZN8FireTileC1EiRKSs|
|AuxDataTileItem::AuxDataTileItem|No|(int, Tile*)|IDK|_ZN15AuxDataTileItemC1EiP4Tile|
|Item::setCategory|No|(int)|IDK|_ZN4Item11setCategoryEi|
|Tile::woodSlab|No|(undefined|IDK|_ZN4Tile8woodSlabE|
|Tile::stainedClay|No|(undefined|IDK|_ZN4Tile11stainedClayE|
|Tile::hayBlock|No|(undefined|IDK|_ZN4Tile8hayBlockE|
|Tile::coalBlock|No|(undefined|IDK|_ZN4Tile9coalBlockE|
|Tile::woodStairsAcacia|No|(undefined|IDK|_ZN4Tile16woodStairsAcaciaE|
|Tile::woodStairsBigOak|No|(undefined|IDK|_ZN4Tile16woodStairsBigOakE|
|Tile::hardenedClay|No|(undefined|IDK|_ZN4Tile12hardenedClayE|
|Tile::doublePlant|No|(undefined|IDK|_ZN4Tile11doublePlantE|
|Tile::podzol|No|(undefined|IDK|_ZN4Tile6podzolE|
|Tile::beetroot|No|(undefined|IDK|_ZN4Tile8beetrootE|
|Tile::stonecutterBench|No|(undefined|IDK|_ZN4Tile16stonecutterBenchE|
|Tile::glowingObsidian|No|(undefined|IDK|_ZN4Tile15glowingObsidianE|
|Tile::netherReactor|No|(undefined|IDK|_ZN4Tile13netherReactorE|
|Tile::info_reserved6|No|(undefined|IDK|_ZN4Tile14info_reserved6E|
|TileItem::TileItem|No|(int)|IDK|_ZN8TileItemC2Ei|
|Item::setMaxDamage|No|(int)|IDK|_ZN4Item12setMaxDamageEi|
|Item::setStackedByData|No|(bool)|IDK|_ZN4Item16setStackedByDataEb|
|WoodSlabTile::Item::Item|No|(int)|IDK|_ZN12WoodSlabTile4ItemC1Ei|
|TileItem::TileItem|No|(int)|IDK|_ZN8TileItemC1Ei|
|vtable for ClothTileItem|No|(undefined|IDK|_ZTV13ClothTileItem|
|vtable for StoneSlabTileItem|No|(undefined|IDK|_ZTV17StoneSlabTileItem|
|vtable for SaplingTileItem|No|(undefined|IDK|_ZTV15SaplingTileItem|
|vtable for LeafTileItem|No|(undefined|IDK|_ZTV12LeafTileItem|
|vtable for WaterLilyTileItem|No|(undefined|IDK|_ZTV17WaterLilyTileItem|
(null)
(null)
|CreativeInventoryScreen::populateItem|No|(Tile*, int, int)|IDK|_ZN23CreativeInventoryScreen12populateItemEP4Tileii|
|ItemInstance::ItemInstance|No|(Tile const*, int, int)|IDK|_ZN12ItemInstanceC1EPK4Tileii|
|CreativeInventoryScreen::items|No|(undefined|IDK|_ZN23CreativeInventoryScreen5itemsE|
|CreativeInventoryScreen::populateItem|No|(Item*, int, int)|IDK|_ZN23CreativeInventoryScreen12populateItemEP4Itemii|
|ItemInstance::ItemInstance|No|(Item const*, int, int)|IDK|_ZN12ItemInstanceC1EPK4Itemii|
|ContainerSetContentPacket::read|No|(RakNet::BitStream*)|IDK|_ZN25ContainerSetContentPacket4readEPN6RakNet9BitStreamE|
|PacketUtil::readItemInstance|No|(RakNet::BitStream*)|IDK|_ZN10PacketUtil16readItemInstanceEPN6RakNet9BitStreamE|
(null)
(null)
|Touch::IngameBlockSelectionScreen::init|No|()|IDK|_ZN5Touch26IngameBlockSelectionScreen4initEv|
|Touch::TButton::init|No|(Minecraft*)|IDK|_ZN5Touch7TButton4initEP9Minecraft|
(null)
(null)
|CreativeInventoryScreen::populateFilteredItems|No|()|IDK|_ZN23CreativeInventoryScreen21populateFilteredItemsEv|
|CreativeInventoryScreen::populateItems|No|()|IDK|_ZN23CreativeInventoryScreen13populateItemsEv|
|Item::bucket|No|(undefined|IDK|_ZN4Item6bucketE|
|Item::door_wood|No|(undefined|IDK|_ZN4Item9door_woodE|
|Item::painting|No|(undefined|IDK|_ZN4Item8paintingE|
|Item::seeds_beetroot|No|(undefined|IDK|_ZN4Item14seeds_beetrootE|
|Item::hoe_iron|No|(undefined|IDK|_ZN4Item8hoe_ironE|
|Item::cake|No|(undefined|IDK|_ZN4Item4cakeE|
|Item::egg|No|(undefined|IDK|_ZN4Item3eggE|
|Item::flintAndSteel|No|(undefined|IDK|_ZN4Item13flintAndSteelE|
|Item::sign|No|(undefined|IDK|_ZN4Item4signE|
|Item::clock|No|(undefined|IDK|_ZN4Item5clockE|
|Item::compass|No|(undefined|IDK|_ZN4Item7compassE|
|Item::bone|No|(undefined|IDK|_ZN4Item4boneE|
|Item::beef_raw|No|(undefined|IDK|_ZN4Item8beef_rawE|
|Item::bowl|No|(undefined|IDK|_ZN4Item4bowlE|
|Item::mobPlacer|No|(undefined|IDK|_ZN4Item9mobPlacerE|
|CreativeInventoryScreen::CreativeInventoryScreen|No|()|IDK|_ZN23CreativeInventoryScreenC2Ev|
|CreativeInventoryScreen::CreativeInventoryScreen|No|()|IDK|_ZN23CreativeInventoryScreenC1Ev|
|Touch::IngameBlockSelectionScreen::getItems|No|(Touch::InventoryPane const*)|IDK|_ZN5Touch26IngameBlockSelectionScreen8getItemsEPKNS_13InventoryPaneE|
|non-virtual thunk to Touch::IngameBlockSelectionScreen::getItems|No|(Touch::InventoryPane const*)|IDK|_ZThn132_N5Touch26IngameBlockSelectionScreen8getItemsEPKNS_13InventoryPaneE|
(null)
|void SynchedEntityData::define<signed char>|No|(int, signed char const&)|IDK|_ZN17SynchedEntityData6defineIaEEviRKT_|
|vtable for DataItem2<signed char>|No|(undefined|IDK|_ZTV9DataItem2IaE|
|Villager::init|No|(int)|IDK|_ZN8Villager4initEi|
|PathNavigation::setCanOpenDoors|No|(bool)|IDK|_ZN14PathNavigation15setCanOpenDoorsEb|
|PathNavigation::setAvoidWater|No|(bool)|IDK|_ZN14PathNavigation13setAvoidWaterEb|
|FloatGoal::FloatGoal|No|(Mob*)|IDK|_ZN9FloatGoalC1EP3Mob|
|GoalSelector::addGoal|No|(int, Goal*, bool)|IDK|_ZN12GoalSelector7addGoalEiP4Goalb|
|InteractGoal::InteractGoal|No|(Mob*, float, int, float)|IDK|_ZN12InteractGoalC1EP3Mobfif|
|RandomStrollGoal::RandomStrollGoal|No|(PathfinderMob*, float)|IDK|_ZN16RandomStrollGoalC1EP13PathfinderMobf|
|LookAtPlayerGoal::LookAtPlayerGoal|No|(Mob*, float, float)|IDK|_ZN16LookAtPlayerGoalC1EP3Mobff|
|Villager::Villager|No|(TileSource*)|IDK|_ZN8VillagerC2EP10TileSource|
|AgableMob::AgableMob|No|(TileSource*)|IDK|_ZN9AgableMobC2EP10TileSource|
|vtable for Villager|No|(undefined|IDK|_ZTV8Villager|
|Villager::Villager|No|(TileSource*)|IDK|_ZN8VillagerC1EP10TileSource|
|Villager::Villager|No|(TileSource*, int)|IDK|_ZN8VillagerC2EP10TileSourcei|
|Villager::Villager|No|(TileSource*, int)|IDK|_ZN8VillagerC1EP10TileSourcei|
|Pig::Pig|No|(TileSource*)|IDK|_ZN3PigC2EP10TileSource|
|Animal::Animal|No|(TileSource*)|IDK|_ZN6AnimalC2EP10TileSource|
|PanicGoal::PanicGoal|No|(PathfinderMob*, float)|IDK|_ZN9PanicGoalC1EP13PathfinderMobf|
|BreedGoal::BreedGoal|No|(Animal*, float)|IDK|_ZN9BreedGoalC1EP6Animalf|
|TemptGoal::TemptGoal|No|(PathfinderMob*, float, std::initializer_list<int>, bool)|IDK|_ZN9TemptGoalC1EP13PathfinderMobfSt16initializer_listIiEb|
|FollowParentGoal::FollowParentGoal|No|(Animal*, float)|IDK|_ZN16FollowParentGoalC1EP6Animalf|
|LookAtPlayerGoal::LookAtPlayerGoal|No|(Mob*, float)|IDK|_ZN16LookAtPlayerGoalC1EP3Mobf|
|RandomLookAroundGoal::RandomLookAroundGoal|No|(Mob*)|IDK|_ZN20RandomLookAroundGoalC1EP3Mob|
|vtable for Pig|No|(undefined|IDK|_ZTV3Pig|
|Pig::Pig|No|(TileSource*)|IDK|_ZN3PigC1EP10TileSource|
|Pig::getBreedOffspring|No|(Animal*)|IDK|_ZN3Pig17getBreedOffspringEP6Animal|
|Spider::Spider|No|(TileSource*)|IDK|_ZN6SpiderC2EP10TileSource|
|Monster::Monster|No|(TileSource*)|IDK|_ZN7MonsterC2EP10TileSource|
|PathNavigation::PathNavigation|No|(Mob*, Level*, float)|IDK|_ZN14PathNavigationC2EP3MobP5Levelf|
|LeapAtTargetGoal::LeapAtTargetGoal|No|(Mob*, float)|IDK|_ZN16LeapAtTargetGoalC1EP3Mobf|
|MeleeAttackGoal::MeleeAttackGoal|No|(Mob*, float, bool)|IDK|_ZN15MeleeAttackGoalC2EP3Mobfb|
|HurtByTargetGoal::HurtByTargetGoal|No|(Mob*, bool)|IDK|_ZN16HurtByTargetGoalC1EP3Mobb|
|vtable for Spider|No|(undefined|IDK|_ZTV6Spider|
|vtable for WallClimberPathNavigation|No|(undefined|IDK|_ZTV25WallClimberPathNavigation|
|vtable for NearestAttackableTargetGoal|No|(undefined|IDK|_ZTV27NearestAttackableTargetGoal|
|vtable for SpiderTargetGoal|No|(undefined|IDK|_ZTV16SpiderTargetGoal|
|Spider::Spider|No|(TileSource*)|IDK|_ZN6SpiderC1EP10TileSource|
|Minecart::Minecart|No|(TileSource*)|IDK|_ZN8MinecartC2EP10TileSource|
|vtable for DataItem2<int>|No|(undefined|IDK|_ZTV9DataItem2IiE|
|vtable for DataItem2<float>|No|(undefined|IDK|_ZTV9DataItem2IfE|
|Minecart::Minecart|No|(TileSource*)|IDK|_ZN8MinecartC1EP10TileSource|
|Minecart::Minecart|No|(TileSource*, float, float, float)|IDK|_ZN8MinecartC2EP10TileSourcefff|
|Minecart::Minecart|No|(TileSource*, float, float, float)|IDK|_ZN8MinecartC1EP10TileSourcefff|
(null)
(null)
|WorldLimitChunkSource::WorldLimitChunkSource|No|(ChunkSource*, TilePos const&)|IDK|_ZN21WorldLimitChunkSourceC2EP11ChunkSourceRK7TilePos|
|ChunkPos::INVALID|No|(undefined|IDK|_ZN8ChunkPos7INVALIDE|
|WorldLimitChunkSource::WorldLimitChunkSource|No|(ChunkSource*, TilePos const&)|IDK|_ZN21WorldLimitChunkSourceC1EP11ChunkSourceRK7TilePos|
|std::_Hashtable<std::string const*, std::pair<std::string const* const, std::vector<Particle*, std::allocator<Particle*> > >, std::allocator<std::pair<std::string const* const, std::vector<Particle*, std::allocator<Particle*> > > >, std::__detail::_Select1st, std::equal_to<std::string const*>, std::hash<std::string const*>, std::__detail::_Mod_range_hashing, std::__detail::_Default_ranged_hash, std::__detail::_Prime_rehash_policy, std::__detail::_Hashtable_traits<false, false, true> >::_M_insert_unique_node|No|(unsigned int, unsigned int, std::__detail::_Hash_node<std::pair<std::string const* const, std::vector<Particle*, std::allocator<Particle*> > >, false>*)|IDK|_ZNSt10_HashtableIPKSsSt4pairIKS1_St6vectorIP8ParticleSaIS6_EEESaIS9_ENSt8__detail10_Select1stESt8equal_toIS1_ESt4hashIS1_ENSB_18_Mod_range_hashingENSB_20_Default_ranged_hashENSB_20_Prime_rehash_policyENSB_17_Hashtable_traitsILb0ELb0ELb1EEEE21_M_insert_unique_nodeEjjPNSB_10_Hash_nodeIS9_Lb0EEE|
(null)
|ParticleEngine::instance|No|(ParticleType, float, float, float, float, float, float, int)|IDK|_ZN14ParticleEngine8instanceE12ParticleTypeffffffi|
|Particle::_init|No|(float, float, float, float, float, float, int)|IDK|_ZN8Particle5_initEffffffi|
|ParticleEngine::_destroyEffect|No|(TilePos const&, FullTile, Vec3 const&)|IDK|_ZN14ParticleEngine14_destroyEffectERK7TilePos8FullTileRK4Vec3|
|ParticleEngine::destroyEffect|No|(TileSource&, int, int, int, Vec3 const&)|IDK|_ZN14ParticleEngine13destroyEffectER10TileSourceiiiRK4Vec3|
|Tile::destroyEffect|No|(TileSource&, TilePos const&, Vec3 const&)|IDK|_ZN4Tile13destroyEffectER10TileSourceRK7TilePosRK4Vec3|
|Level::getParticleEngine|No|() const|IDK|_ZNK5Level17getParticleEngineEv|
(null)
(null)
|FlowerTile::getTesselatedUVs|No|()|IDK|_ZN10FlowerTile16getTesselatedUVsEv|
|BedTile::getTesselatedUVs|No|()|IDK|_ZN7BedTile16getTesselatedUVsEv|
(null)
(null)
|ServerSideNetworkHandler::onReady_ClientGeneration|No|(Player*, RakNet::RakNetGUID const&)|IDK|_ZN24ServerSideNetworkHandler24onReady_ClientGenerationEP6PlayerRKN6RakNet10RakNetGUIDE|
|Player::prepareRegion|No|(Level*)|IDK|_ZN6Player13prepareRegionEP5Level|
|Player::getArmorTypeHash|No|()|IDK|_ZN6Player16getArmorTypeHashEv|
|FillingContainer::getLinkedSlot|No|(int)|IDK|_ZN16FillingContainer13getLinkedSlotEi|
|ItemInstance::ItemInstance|No|()|IDK|_ZN12ItemInstanceC1Ev|
|vtable for SetSpawnPositionPacket|No|(undefined|IDK|_ZTV22SetSpawnPositionPacket|
|ServerSideNetworkHandler::sendLoginMessageLocal|No|(int, RakNet::RakNetGUID const&, LoginPacket*)|IDK|_ZN24ServerSideNetworkHandler21sendLoginMessageLocalEiRKN6RakNet10RakNetGUIDEP11LoginPacket|
|ServerSideNetworkHandler::handle|No|(RakNet::RakNetGUID const&, LoginPacket*)|IDK|_ZN24ServerSideNetworkHandler6handleERKN6RakNet10RakNetGUIDEP11LoginPacket|
|std::_Hashtable<ChunkPos, std::pair<ChunkPos const, ChunkRefCount>, std::allocator<std::pair<ChunkPos const, ChunkRefCount> >, std::__detail::_Select1st, std::equal_to<ChunkPos>, std::hash<ChunkPos>, std::__detail::_Mod_range_hashing, std::__detail::_Default_ranged_hash, std::__detail::_Prime_rehash_policy, std::__detail::_Hashtable_traits<true, false, true> >::_M_insert_unique_node|No|(unsigned int, unsigned int, std::__detail::_Hash_node<std::pair<ChunkPos const, ChunkRefCount>, true>*)|IDK|_ZNSt10_HashtableI8ChunkPosSt4pairIKS0_13ChunkRefCountESaIS4_ENSt8__detail10_Select1stESt8equal_toIS0_ESt4hashIS0_ENS6_18_Mod_range_hashingENS6_20_Default_ranged_hashENS6_20_Prime_rehash_policyENS6_17_Hashtable_traitsILb1ELb0ELb1EEEE21_M_insert_unique_nodeEjjPNS6_10_Hash_nodeIS4_Lb1EEE|
|std::__detail::_Map_base<ChunkPos, std::pair<ChunkPos const, ChunkRefCount>, std::allocator<std::pair<ChunkPos const, ChunkRefCount> >, std::__detail::_Select1st, std::equal_to<ChunkPos>, std::hash<ChunkPos>, std::__detail::_Mod_range_hashing, std::__detail::_Default_ranged_hash, std::__detail::_Prime_rehash_policy, std::__detail::_Hashtable_traits<true, false, true>, true>::operator[]|No|(ChunkPos const&)|IDK|_ZNSt8__detail9_Map_baseI8ChunkPosSt4pairIKS1_13ChunkRefCountESaIS5_ENS_10_Select1stESt8equal_toIS1_ESt4hashIS1_ENS_18_Mod_range_hashingENS_20_Default_ranged_hashENS_20_Prime_rehash_policyENS_17_Hashtable_traitsILb1ELb0ELb1EEELb1EEixERS3_|
|ChunkRefCount::ChunkRefCount|No|()|IDK|_ZN13ChunkRefCountC1Ev|
|MainChunkSource::requestChunk|No|(ChunkPos const&, ChunkSource::LoadMode)|IDK|_ZN15MainChunkSource12requestChunkERK8ChunkPosN11ChunkSource8LoadModeE|
|ChunkRefCount::ChunkRefCount|No|(LevelChunk&, int)|IDK|_ZN13ChunkRefCountC1ER10LevelChunki|
(null)
|ChunkRefCount::grab|No|()|IDK|_ZN13ChunkRefCount4grabEv|
|MainChunkSource::acquireDiscarded|No|(std::unique_ptr<LevelChunk, std::default_delete<LevelChunk> >&)|IDK|_ZN15MainChunkSource16acquireDiscardedERSt10unique_ptrI10LevelChunkSt14default_deleteIS1_EE|
|ChunkRefCount::ChunkRefCount|No|(std::unique_ptr<LevelChunk, std::default_delete<LevelChunk> >&, int)|IDK|_ZN13ChunkRefCountC1ERSt10unique_ptrI10LevelChunkSt14default_deleteIS1_EEi|
(null)
(null)
|CreativeInventoryScreen::init|No|()|IDK|_ZN23CreativeInventoryScreen4initEv|
|Screen::setPassGuiEvents|No|(bool)|IDK|_ZN6Screen16setPassGuiEventsEb|
|ImageWithBackground::ImageWithBackground|No|(int)|IDK|_ZN19ImageWithBackgroundC1Ei|
|ImageWithBackground::init|No|(Textures*, int, int, IntRectangle, IntRectangle, int, int, std::string const&)|IDK|_ZN19ImageWithBackground4initEP8Texturesii12IntRectangleS2_iiRKSs|
|vtable for std::_Sp_counted_ptr<NinePatchLayer*, |No|(__gnu_cxx::_Lock_policy)2>|IDK|_ZTVSt15_Sp_counted_ptrIP14NinePatchLayerLN9__gnu_cxx12_Lock_policyE2EE|
|vtable for std::_Sp_counted_ptr<ImageWithBackground*, |No|(__gnu_cxx::_Lock_policy)2>|IDK|_ZTVSt15_Sp_counted_ptrIP19ImageWithBackgroundLN9__gnu_cxx12_Lock_policyE2EE|
|std::_Hashtable<_TickPtr*, _TickPtr*, std::allocator<_TickPtr*>, std::__detail::_Identity, std::equal_to<_TickPtr*>, std::hash<_TickPtr*>, std::__detail::_Mod_range_hashing, std::__detail::_Default_ranged_hash, std::__detail::_Prime_rehash_policy, std::__detail::_Hashtable_traits<false, true, true> >::_M_insert_unique_node|No|(unsigned int, unsigned int, std::__detail::_Hash_node<_TickPtr*, false>*)|IDK|_ZNSt10_HashtableIP8_TickPtrS1_SaIS1_ENSt8__detail9_IdentityESt8equal_toIS1_ESt4hashIS1_ENS3_18_Mod_range_hashingENS3_20_Default_ranged_hashENS3_20_Prime_rehash_policyENS3_17_Hashtable_traitsILb0ELb1ELb1EEEE21_M_insert_unique_nodeEjjPNS3_10_Hash_nodeIS1_Lb0EEE|
(null)
|AvoidMobTypeGoal::stop|No|()|IDK|_ZN16AvoidMobTypeGoal4stopEv|
|AvoidMobTypeGoal::canUse|No|()|IDK|_ZN16AvoidMobTypeGoal6canUseEv|
|Entity::distanceToSqr|No|(float, float, float)|IDK|_ZN6Entity13distanceToSqrEfff|
|std::_Hashtable<TileSourceListener*, TileSourceListener*, std::allocator<TileSourceListener*>, std::__detail::_Identity, std::equal_to<TileSourceListener*>, std::hash<TileSourceListener*>, std::__detail::_Mod_range_hashing, std::__detail::_Default_ranged_hash, std::__detail::_Prime_rehash_policy, std::__detail::_Hashtable_traits<false, true, true> >::_M_insert_unique_node|No|(unsigned int, unsigned int, std::__detail::_Hash_node<TileSourceListener*, false>*)|IDK|_ZNSt10_HashtableIP18TileSourceListenerS1_SaIS1_ENSt8__detail9_IdentityESt8equal_toIS1_ESt4hashIS1_ENS3_18_Mod_range_hashingENS3_20_Default_ranged_hashENS3_20_Prime_rehash_policyENS3_17_Hashtable_traitsILb0ELb1ELb1EEEE21_M_insert_unique_nodeEjjPNS3_10_Hash_nodeIS1_Lb0EEE|
(null)
|TileSource::TileSource|No|(Level&, ChunkSource*, bool, bool)|IDK|_ZN10TileSourceC2ER5LevelP11ChunkSourcebb|
|Level::getTickQueue|No|() const|IDK|_ZNK5Level12getTickQueueEv|
|TileSource::TileSource|No|(Level&, ChunkSource*, bool, bool)|IDK|_ZN10TileSourceC1ER5LevelP11ChunkSourcebb|
|DBChunkStorage::postProcess|No|(ChunkViewSource&)|IDK|_ZN14DBChunkStorage11postProcessER15ChunkViewSource|
|FoliageColor::buildGrassColor|No|(TilePos const&, TilePos const&, TileSource&, Random&)|IDK|_ZN12FoliageColor15buildGrassColorERK7TilePosS2_R10TileSourceR6Random|
|Biome::plains|No|(undefined|IDK|_ZN5Biome6plainsE|
|TileSource::TileSource|No|(Player&)|IDK|_ZN10TileSourceC2ER6Player|
|TileSource::TileSource|No|(Player&)|IDK|_ZN10TileSourceC1ER6Player|
|std::_Hashtable<ChunkPos, ChunkPos, std::allocator<ChunkPos>, std::__detail::_Identity, std::equal_to<ChunkPos>, std::hash<ChunkPos>, std::__detail::_Mod_range_hashing, std::__detail::_Default_ranged_hash, std::__detail::_Prime_rehash_policy, std::__detail::_Hashtable_traits<true, true, true> >::_M_insert_unique_node|No|(unsigned int, unsigned int, std::__detail::_Hash_node<ChunkPos, true>*)|IDK|_ZNSt10_HashtableI8ChunkPosS0_SaIS0_ENSt8__detail9_IdentityESt8equal_toIS0_ESt4hashIS0_ENS2_18_Mod_range_hashingENS2_20_Default_ranged_hashENS2_20_Prime_rehash_policyENS2_17_Hashtable_traitsILb1ELb1ELb1EEEE21_M_insert_unique_nodeEjjPNS2_10_Hash_nodeIS0_Lb1EEE|
(null)
|PostprocessingManager::tryLock|No|(ChunkPos const&)|IDK|_ZN21PostprocessingManager7tryLockERK8ChunkPos|
|std::_Hashtable<ChunkTilePos, std::pair<ChunkTilePos const, std::unique_ptr<TileEntity, std::default_delete<TileEntity> > >, std::allocator<std::pair<ChunkTilePos const, std::unique_ptr<TileEntity, std::default_delete<TileEntity> > > >, std::__detail::_Select1st, std::equal_to<ChunkTilePos>, std::hash<ChunkTilePos>, std::__detail::_Mod_range_hashing, std::__detail::_Default_ranged_hash, std::__detail::_Prime_rehash_policy, std::__detail::_Hashtable_traits<true, false, true> >::_M_insert_unique_node|No|(unsigned int, unsigned int, std::__detail::_Hash_node<std::pair<ChunkTilePos const, std::unique_ptr<TileEntity, std::default_delete<TileEntity> > >, true>*)|IDK|_ZNSt10_HashtableI12ChunkTilePosSt4pairIKS0_St10unique_ptrI10TileEntitySt14default_deleteIS4_EEESaIS8_ENSt8__detail10_Select1stESt8equal_toIS0_ESt4hashIS0_ENSA_18_Mod_range_hashingENSA_20_Default_ranged_hashENSA_20_Prime_rehash_policyENSA_17_Hashtable_traitsILb1ELb0ELb1EEEE21_M_insert_unique_nodeEjjPNSA_10_Hash_nodeIS8_Lb1EEE|
|LevelChunk::_placeTileEntity|No|(TileEntity&)|IDK|_ZN10LevelChunk16_placeTileEntityER10TileEntity|
|LevelChunk::_createTileEntity|No|(TilePos const&, TileSource*, unsigned char, unsigned char)|IDK|_ZN10LevelChunk17_createTileEntityERK7TilePosP10TileSourcehh|
|TileEntity::setRegion|No|(TileSource*)|IDK|_ZN10TileEntity9setRegionEP10TileSource|
|LevelChunk::_placeCallbacks|No|(ChunkTilePos const&, unsigned char, unsigned char, TileSource*)|IDK|_ZN10LevelChunk15_placeCallbacksERK12ChunkTilePoshhP10TileSource|
|LevelChunk::deserializeTileEntities|No|(IDataInput&)|IDK|_ZN10LevelChunk23deserializeTileEntitiesER10IDataInput|
|TileEntity::loadStatic|No|(CompoundTag*)|IDK|_ZN10TileEntity10loadStaticEP11CompoundTag|
|LevelChunk::deserialize|No|(KeyValueInput&)|IDK|_ZN10LevelChunk11deserializeER13KeyValueInput|
|LevelChunk::TERRAIN_TAG|No|(undefined|IDK|_ZN10LevelChunk11TERRAIN_TAGE|
|LevelChunk::TILEENTITY_TAG|No|(undefined|IDK|_ZN10LevelChunk14TILEENTITY_TAGE|
|LevelChunk::ENTITY_TAG|No|(undefined|IDK|_ZN10LevelChunk10ENTITY_TAGE|
|LevelChunk::VERSION_TAG|No|(undefined|IDK|_ZN10LevelChunk11VERSION_TAGE|
|DBChunkStorage::loadChunk|No|(LevelChunk&)|IDK|_ZN14DBChunkStorage9loadChunkER10LevelChunk|
|DBStorage::_read|No|(leveldb::Slice const&, KeyValueInput&) const|IDK|_ZNK9DBStorage5_readERKN7leveldb5SliceER13KeyValueInput|
|DBStorage::deleteAllWithPrefix|No|(leveldb::Slice const&)|IDK|_ZN9DBStorage19deleteAllWithPrefixERKN7leveldb5SliceE|
|ChunkSource::loadChunk|No|(LevelChunk&)|IDK|_ZN11ChunkSource9loadChunkER10LevelChunk|
|std::_Hashtable<ChunkTilePos, std::pair<ChunkTilePos const, std::unique_ptr<TileEntity, std::default_delete<TileEntity> > >, std::allocator<std::pair<ChunkTilePos const, std::unique_ptr<TileEntity, std::default_delete<TileEntity> > > >, std::__detail::_Select1st, std::equal_to<ChunkTilePos>, std::hash<ChunkTilePos>, std::__detail::_Mod_range_hashing, std::__detail::_Default_ranged_hash, std::__detail::_Prime_rehash_policy, std::__detail::_Hashtable_traits<true, false, true> >::_M_erase|No|(unsigned int, std::__detail::_Hash_node_base*, std::__detail::_Hash_node<std::pair<ChunkTilePos const, std::unique_ptr<TileEntity, std::default_delete<TileEntity> > >, true>*)|IDK|_ZNSt10_HashtableI12ChunkTilePosSt4pairIKS0_St10unique_ptrI10TileEntitySt14default_deleteIS4_EEESaIS8_ENSt8__detail10_Select1stESt8equal_toIS0_ESt4hashIS0_ENSA_18_Mod_range_hashingENSA_20_Default_ranged_hashENSA_20_Prime_rehash_policyENSA_17_Hashtable_traitsILb1ELb0ELb1EEEE8_M_eraseEjPNSA_15_Hash_node_baseEPNSA_10_Hash_nodeIS8_Lb1EEE|
|LevelChunk::_removeCallbacks|No|(ChunkTilePos const&, unsigned char, unsigned char, TileSource*)|IDK|_ZN10LevelChunk16_removeCallbacksERK12ChunkTilePoshhP10TileSource|
|Player::tileEntityDestroyed|No|(int)|IDK|_ZN6Player19tileEntityDestroyedEi|
|LevelChunk::setTileAndData|No|(ChunkTilePos const&, FullTile, TileSource*)|IDK|_ZN10LevelChunk14setTileAndDataERK12ChunkTilePos8FullTileP10TileSource|
|TileSource::setTileAndData|No|(TilePos const&, FullTile, int)|IDK|_ZN10TileSource14setTileAndDataERK7TilePos8FullTilei|
|NetherReactorTile::setPhase|No|(TileSource*, TilePos const&, int)|IDK|_ZN17NetherReactorTile8setPhaseEP10TileSourceRK7TilePosi|
|PumpkinFeature::place|No|(TileSource*, int, int, int, Random&) const|IDK|_ZNK14PumpkinFeature5placeEP10TileSourceiiiR6Random|
|ClayFeature::place|No|(TileSource*, int, int, int, Random&) const|IDK|_ZNK11ClayFeature5placeEP10TileSourceiiiR6Random|
|SandFeature::place|No|(TileSource*, int, int, int, Random&) const|IDK|_ZNK11SandFeature5placeEP10TileSourceiiiR6Random|
|WaterlilyFeature::place|No|(TileSource*, int, int, int, Random&) const|IDK|_ZNK16WaterlilyFeature5placeEP10TileSourceiiiR6Random|
|DeadBushFeature::place|No|(TileSource*, int, int, int, Random&) const|IDK|_ZNK15DeadBushFeature5placeEP10TileSourceiiiR6Random|
|DesertWellFeature::place|No|(TileSource*, int, int, int, Random&) const|IDK|_ZNK17DesertWellFeature5placeEP10TileSourceiiiR6Random|
|MegaTreeFeature::makeDirtFloor|No|(TilePos const&, TileSource*) const|IDK|_ZNK15MegaTreeFeature13makeDirtFloorERK7TilePosP10TileSource|
|MegaJungleTreeFeature::place|No|(TileSource*, int, int, int, Random&) const|IDK|_ZNK21MegaJungleTreeFeature5placeEP10TileSourceiiiR6Random|
|MegaPineTreeFeature::place|No|(TileSource*, int, int, int, Random&) const|IDK|_ZNK19MegaPineTreeFeature5placeEP10TileSourceiiiR6Random|
|IcePatchFeature::place|No|(TileSource*, int, int, int, Random&) const|IDK|_ZNK15IcePatchFeature5placeEP10TileSourceiiiR6Random|
|LiquidTile::_solidify|No|(TileSource&, TilePos const&, TilePos const&)|IDK|_ZN10LiquidTile9_solidifyER10TileSourceRK7TilePosS4_|
|LiquidTile::neighborChanged|No|(TileSource*, int, int, int, int, int, int)|IDK|_ZN10LiquidTile15neighborChangedEP10TileSourceiiiiii|
|LiquidTile::onPlace|No|(TileSource*, int, int, int)|IDK|_ZN10LiquidTile7onPlaceEP10TileSourceiii|
|LeafTile::runDecay|No|(TileSource&, TilePos const&)|IDK|_ZN8LeafTile8runDecayER10TileSourceRK7TilePos|
|LeafTile::onRemove|No|(TileSource*, int, int, int)|IDK|_ZN8LeafTile8onRemoveEP10TileSourceiii|
|WaterLilyTileItem::useOn|No|(ItemInstance*, Player*, int, int, int, signed char, float, float, float)|IDK|_ZN17WaterLilyTileItem5useOnEP12ItemInstanceP6Playeriiiafff|
|Level::mayInteract|No|(Player*, int, int, int)|IDK|_ZN5Level11mayInteractEP6Playeriii|
|TileSource::setTile|No|(int, int, int, unsigned char, int)|IDK|_ZN10TileSource7setTileEiiihi|
|EatTileGoal::tick|No|()|IDK|_ZN11EatTileGoal4tickEv|
|Level::levelEvent|No|(Mob*, int, int, int, int, int)|IDK|_ZN5Level10levelEventEP3Mobiiiii|
|CactusTile::neighborChanged|No|(TileSource*, int, int, int, int, int, int)|IDK|_ZN10CactusTile15neighborChangedEP10TileSourceiiiiii|
|SpringFeature::place|No|(TileSource*, int, int, int, Random&) const|IDK|_ZNK13SpringFeature5placeEP10TileSourceiiiR6Random|
|IceSpikeFeature::place|No|(TileSource*, int, int, int, Random&) const|IDK|_ZNK15IceSpikeFeature5placeEP10TileSourceiiiR6Random|
|LiquidTile::_trySpreadFire|No|(TileSource*, int, int, int, Random*)|IDK|_ZN10LiquidTile14_trySpreadFireEP10TileSourceiiiP6Random|
|LeafTile::die|No|(TileSource*, int, int, int)|IDK|_ZN8LeafTile3dieEP10TileSourceiii|
|ServerSideNetworkHandler::handle|No|(RakNet::RakNetGUID const&, RemoveBlockPacket*)|IDK|_ZN24ServerSideNetworkHandler6handleERKN6RakNet10RakNetGUIDEP17RemoveBlockPacket|
|IceTile::playerDestroy|No|(Player*, int, int, int, int)|IDK|_ZN7IceTile13playerDestroyEP6Playeriiii|
|IceTile::tick|No|(TileSource*, int, int, int, Random*)|IDK|_ZN7IceTile4tickEP10TileSourceiiiP6Random|
|RedStoneOreTile::use|No|(Player*, int, int, int)|IDK|_ZN15RedStoneOreTile3useEP6Playeriii|
|RedStoneOreTile::tick|No|(TileSource*, int, int, int, Random*)|IDK|_ZN15RedStoneOreTile4tickEP10TileSourceiiiP6Random|
|ReedTile::neighborChanged|No|(TileSource*, int, int, int, int, int, int)|IDK|_ZN8ReedTile15neighborChangedEP10TileSourceiiiiii|
|SnowTile::tick|No|(TileSource*, int, int, int, Random*)|IDK|_ZN8SnowTile4tickEP10TileSourceiiiP6Random|
|TopSnowTile::playerDestroy|No|(Player*, int, int, int, int)|IDK|_ZN11TopSnowTile13playerDestroyEP6Playeriiii|
|TopSnowTile::tick|No|(TileSource*, int, int, int, Random*)|IDK|_ZN11TopSnowTile4tickEP10TileSourceiiiP6Random|
|BedTile::neighborChanged|No|(TileSource*, int, int, int, int, int, int)|IDK|_ZN7BedTile15neighborChangedEP10TileSourceiiiiii|
|RedStoneOreTile::stepOn|No|(Entity*, int, int, int)|IDK|_ZN15RedStoneOreTile6stepOnEP6Entityiii|
|RedStoneOreTile::attack|No|(Player*, int, int, int)|IDK|_ZN15RedStoneOreTile6attackEP6Playeriii|
|TileSource::setTileNoUpdate|No|(int, int, int, unsigned char)|IDK|_ZN10TileSource15setTileNoUpdateEiiih|
|ReedsFeature::place|No|(TileSource*, int, int, int, Random&) const|IDK|_ZNK12ReedsFeature5placeEP10TileSourceiiiR6Random|
|CactusFeature::place|No|(TileSource*, int, int, int, Random&) const|IDK|_ZNK13CactusFeature5placeEP10TileSourceiiiR6Random|
|TileSource::setTileAndDataNoUpdate|No|(int, int, int, FullTile)|IDK|_ZN10TileSource22setTileAndDataNoUpdateEiii8FullTile|
|OreFeature::place|No|(TileSource*, int, int, int, Random&) const|IDK|_ZNK10OreFeature5placeEP10TileSourceiiiR6Random|
|TallGrassFeature::place|No|(TileSource*, int, int, int, Random&) const|IDK|_ZNK16TallGrassFeature5placeEP10TileSourceiiiR6Random|
|TileSource::removeTile|No|(int, int, int)|IDK|_ZN10TileSource10removeTileEiii|
|CakeTile::neighborChanged|No|(TileSource*, int, int, int, int, int, int)|IDK|_ZN8CakeTile15neighborChangedEP10TileSourceiiiiii|
|TileSource::setTileAndData|No|(int, int, int, FullTile, int)|IDK|_ZN10TileSource14setTileAndDataEiii8FullTilei|
|StemTile::tick|No|(TileSource*, int, int, int, Random*)|IDK|_ZN8StemTile4tickEP10TileSourceiiiP6Random|
|Bush::tick|No|(TileSource*, int, int, int, Random*)|IDK|_ZN4Bush4tickEP10TileSourceiiiP6Random|
|CactusTile::tick|No|(TileSource*, int, int, int, Random*)|IDK|_ZN10CactusTile4tickEP10TileSourceiiiP6Random|
|VinesFeature::place|No|(TileSource*, int, int, int, Random&) const|IDK|_ZNK12VinesFeature5placeEP10TileSourceiiiR6Random|
|Facing::OPPOSITE_FACING|No|(undefined|IDK|_ZN6Facing15OPPOSITE_FACINGE|
|Direction::FACING_DIRECTION|No|(undefined|IDK|_ZN9Direction16FACING_DIRECTIONE|
|CropTile::tick|No|(TileSource*, int, int, int, Random*)|IDK|_ZN8CropTile4tickEP10TileSourceiiiP6Random|
|LeafTile::tick|No|(TileSource*, int, int, int, Random*)|IDK|_ZN8LeafTile4tickEP10TileSourceiiiP6Random|
|FlowerFeature::placeFlower|No|(TileSource*, int, int, int, FullTile, Random&) const|IDK|_ZNK13FlowerFeature11placeFlowerEP10TileSourceiii8FullTileR6Random|
|FlowerFeature::place|No|(TileSource*, int, int, int, Random&) const|IDK|_ZNK13FlowerFeature5placeEP10TileSourceiiiR6Random|
|BiomeDecorator::decorate|No|(TileSource*, Random&, Biome*, TilePos const&, bool)|IDK|_ZN14BiomeDecorator8decorateEP10TileSourceR6RandomP5BiomeRK7TilePosb|
|MelonFeatrue::place|No|(TileSource*, int, int, int, Random&) const|IDK|_ZNK12MelonFeatrue5placeEP10TileSourceiiiR6Random|
|FlowerTile::onFertilized|No|(TileSource*, int, int, int)|IDK|_ZN10FlowerTile12onFertilizedEP10TileSourceiii|
|CakeTile::use|No|(Player*, int, int, int)|IDK|_ZN8CakeTile3useEP6Playeriii|
|Player::isHurt|No|()|IDK|_ZN6Player6isHurtEv|
|SimpleFoodData::eat|No|(int)|IDK|_ZN14SimpleFoodData3eatEi|
|ReedTile::tick|No|(TileSource*, int, int, int, Random*)|IDK|_ZN8ReedTile4tickEP10TileSourceiiiP6Random|
|ReedTile::onFertilized|No|(TileSource*, int, int, int)|IDK|_ZN8ReedTile12onFertilizedEP10TileSourceiii|
|BedTile::setOccupied|No|(TileSource*, int, int, int, bool)|IDK|_ZN7BedTile11setOccupiedEP10TileSourceiiib|
|BedTile::use|No|(Player*, int, int, int)|IDK|_ZN7BedTile3useEP6Playeriii|
|StoneSlabTileItem::useOn|No|(ItemInstance*, Player*, int, int, int, signed char, float, float, float)|IDK|_ZN17StoneSlabTileItem5useOnEP12ItemInstanceP6Playeriiiafff|
|TileItem::useOn|No|(ItemInstance*, Player*, int, int, int, signed char, float, float, float)|IDK|_ZN8TileItem5useOnEP12ItemInstanceP6Playeriiiafff|
|TopSnowTile::neighborChanged|No|(TileSource*, int, int, int, int, int, int)|IDK|_ZN11TopSnowTile15neighborChangedEP10TileSourceiiiiii|
|FallingTile::normalTick|No|()|IDK|_ZN11FallingTile10normalTickEv|
(null)
(null)
(null)
(null)
|std::vector<Recipes::Type, std::allocator<Recipes::Type> > definition<ItemInstance, ItemInstance, ItemInstance>|No|(char, ItemInstance, char, ItemInstance, char, ItemInstance)|IDK|_Z10definitionI12ItemInstanceS0_S0_ESt6vectorIN7Recipes4TypeESaIS3_EEcT_cT0_cT1_|
|ClothDyeRecipes::addRecipes|No|(Recipes*)|IDK|_ZN15ClothDyeRecipes10addRecipesEP7Recipes|
|Recipes::addShapedRecipe|No|(ItemInstance const&, std::string const&, std::vector<Recipes::Type, std::allocator<Recipes::Type> > const&)|IDK|_ZN7Recipes15addShapedRecipeERK12ItemInstanceRKSsRKSt6vectorINS_4TypeESaIS6_EE|
|Recipes::addShapedRecipe|No|(ItemInstance const&, std::string const&, std::string const&, std::vector<Recipes::Type, std::allocator<Recipes::Type> > const&)|IDK|_ZN7Recipes15addShapedRecipeERK12ItemInstanceRKSsS4_RKSt6vectorINS_4TypeESaIS6_EE|
|Recipes::addSingleIngredientRecipeItem|No|(ItemInstance const&, ItemInstance const&)|IDK|_ZN7Recipes29addSingleIngredientRecipeItemERK12ItemInstanceS2_|
|ToolRecipes::addRecipes|No|(Recipes*)|IDK|_ZN11ToolRecipes10addRecipesEP7Recipes|
|Recipes::Shape|No|(std::string const&, std::string const&, std::string const&)|IDK|_ZN7Recipes5ShapeERKSsS1_S1_|
|Recipes::addShapedRecipe|No|(ItemInstance const&, std::vector<std::string, std::allocator<std::string> > const&, std::vector<Recipes::Type, std::allocator<Recipes::Type> > const&)|IDK|_ZN7Recipes15addShapedRecipeERK12ItemInstanceRKSt6vectorISsSaISsEERKS3_INS_4TypeESaIS8_EE|
|Item::ironIngot|No|(undefined|IDK|_ZN4Item9ironIngotE|
|Item::goldIngot|No|(undefined|IDK|_ZN4Item9goldIngotE|
|Item::pickAxe_wood|No|(undefined|IDK|_ZN4Item12pickAxe_woodE|
|Item::pickAxe_stone|No|(undefined|IDK|_ZN4Item13pickAxe_stoneE|
|Item::pickAxe_iron|No|(undefined|IDK|_ZN4Item12pickAxe_ironE|
|Item::pickAxe_diamond|No|(undefined|IDK|_ZN4Item15pickAxe_diamondE|
|Item::pickAxe_gold|No|(undefined|IDK|_ZN4Item12pickAxe_goldE|
|Item::shovel_wood|No|(undefined|IDK|_ZN4Item11shovel_woodE|
|Item::shovel_stone|No|(undefined|IDK|_ZN4Item12shovel_stoneE|
|Item::shovel_iron|No|(undefined|IDK|_ZN4Item11shovel_ironE|
|Item::shovel_diamond|No|(undefined|IDK|_ZN4Item14shovel_diamondE|
|Item::shovel_gold|No|(undefined|IDK|_ZN4Item11shovel_goldE|
|Item::hatchet_wood|No|(undefined|IDK|_ZN4Item12hatchet_woodE|
|Item::hatchet_stone|No|(undefined|IDK|_ZN4Item13hatchet_stoneE|
|Item::hatchet_iron|No|(undefined|IDK|_ZN4Item12hatchet_ironE|
|Item::hatchet_diamond|No|(undefined|IDK|_ZN4Item15hatchet_diamondE|
|Item::hatchet_gold|No|(undefined|IDK|_ZN4Item12hatchet_goldE|
|Item::hoe_wood|No|(undefined|IDK|_ZN4Item8hoe_woodE|
|Item::hoe_stone|No|(undefined|IDK|_ZN4Item9hoe_stoneE|
|Item::hoe_diamond|No|(undefined|IDK|_ZN4Item11hoe_diamondE|
|Item::hoe_gold|No|(undefined|IDK|_ZN4Item8hoe_goldE|
|Item::stick|No|(undefined|IDK|_ZN4Item5stickE|
|std::_Hashtable<std::string*, std::string*, std::allocator<std::string*>, std::__detail::_Identity, std::equal_to<std::string*>, std::hash<std::string*>, std::__detail::_Mod_range_hashing, std::__detail::_Default_ranged_hash, std::__detail::_Prime_rehash_policy, std::__detail::_Hashtable_traits<false, true, true> >::_M_insert_unique_node|No|(unsigned int, unsigned int, std::__detail::_Hash_node<std::string*, false>*)|IDK|_ZNSt10_HashtableIPSsS0_SaIS0_ENSt8__detail9_IdentityESt8equal_toIS0_ESt4hashIS0_ENS2_18_Mod_range_hashingENS2_20_Default_ranged_hashENS2_20_Prime_rehash_policyENS2_17_Hashtable_traitsILb0ELb1ELb1EEEE21_M_insert_unique_nodeEjjPNS2_10_Hash_nodeIS0_Lb0EEE|
|DBChunkStorage::_serializeChunk|No|(LevelChunk&, leveldb::WriteBatch&, int)|IDK|_ZN14DBChunkStorage15_serializeChunkER10LevelChunkRN7leveldb10WriteBatchEi|
|leveldb::WriteBatch::Put|No|(leveldb::Slice const&, leveldb::Slice const&)|IDK|_ZN7leveldb10WriteBatch3PutERKNS_5SliceES3_|
|leveldb::WriteBatch::Delete|No|(leveldb::Slice const&)|IDK|_ZN7leveldb10WriteBatch6DeleteERKNS_5SliceE|
|DBStorage::hasKey|No|(std::string const&)|IDK|_ZN9DBStorage6hasKeyERKSs|
|vtable for StringByteOutput|No|(undefined|IDK|_ZTV16StringByteOutput|
|DBChunkStorage::saveLiveChunk|No|(LevelChunk&)|IDK|_ZN14DBChunkStorage13saveLiveChunkER10LevelChunk|
|std::_Hashtable<leveldb::WriteBatch*, leveldb::WriteBatch*, std::allocator<leveldb::WriteBatch*>, std::__detail::_Identity, std::equal_to<leveldb::WriteBatch*>, std::hash<leveldb::WriteBatch*>, std::__detail::_Mod_range_hashing, std::__detail::_Default_ranged_hash, std::__detail::_Prime_rehash_policy, std::__detail::_Hashtable_traits<false, true, true> >::_M_insert_unique_node|No|(unsigned int, unsigned int, std::__detail::_Hash_node<leveldb::WriteBatch*, false>*)|IDK|_ZNSt10_HashtableIPN7leveldb10WriteBatchES2_SaIS2_ENSt8__detail9_IdentityESt8equal_toIS2_ESt4hashIS2_ENS4_18_Mod_range_hashingENS4_20_Default_ranged_hashENS4_20_Prime_rehash_policyENS4_17_Hashtable_traitsILb0ELb1ELb1EEEE21_M_insert_unique_nodeEjjPNS4_10_Hash_nodeIS2_Lb0EEE|
|Tag** std::__copy_move<true, true, std::random_access_iterator_tag>::__copy_m<Tag*>|No|(Tag* const*, Tag* const*, Tag**)|IDK|_ZNSt11__copy_moveILb1ELb1ESt26random_access_iterator_tagE8__copy_mIP3TagEEPT_PKS5_S8_S6_|
|std::vector<Tag*, std::allocator<Tag*> >::insert|No|(__gnu_cxx::__normal_iterator<Tag**, std::vector<Tag*, std::allocator<Tag*> > >, Tag* const&)|IDK|_ZNSt6vectorIP3TagSaIS1_EE6insertEN9__gnu_cxx17__normal_iteratorIPS1_S3_EERKS1_|
|Village::addAdditionalSaveData|No|(CompoundTag*)|IDK|_ZN7Village21addAdditionalSaveDataEP11CompoundTag|
|TileRenderer::TileRenderer|No|(Tesselator&, TileSource*)|IDK|_ZN12TileRendererC1ER10TesselatorP10TileSource|
|PoolAllocator::PoolAllocator|No|(int)|IDK|_ZN13PoolAllocatorC1Ei|
|ChestTileEntity::ChestTileEntity|No|(TilePos const&)|IDK|_ZN15ChestTileEntityC1ERK7TilePos|
|PoolAllocator::~PoolAllocator|No|()|IDK|_ZN13PoolAllocatorD1Ev|
|Vec3::NEG_UNIT_X|No|(undefined|IDK|_ZN4Vec310NEG_UNIT_XE|
|Vec3::UNIT_X|No|(undefined|IDK|_ZN4Vec36UNIT_XE|
|Vec3::UNIT_Y|No|(undefined|IDK|_ZN4Vec36UNIT_YE|
|Vec3::NEG_UNIT_Y|No|(undefined|IDK|_ZN4Vec310NEG_UNIT_YE|
(null)
|EntityTileRenderer::instance|No|(undefined|IDK|_ZN18EntityTileRenderer8instanceE|
|PostprocessingManager::instance|No|(undefined|IDK|_ZN21PostprocessingManager8instanceE|
|Tile::SOUND_SILENT|No|(undefined|IDK|_ZN4Tile12SOUND_SILENTE|
|TilePos::ONE|No|(undefined|IDK|_ZN7TilePos3ONEE|
|TilePos::MAX|No|(undefined|IDK|_ZN7TilePos3MAXE|
|TilePos::MIN|No|(undefined|IDK|_ZN7TilePos3MINE|
|Touch::IngameBlockSelectionScreen::~IngameBlockSelectionScreen|No|()|IDK|_ZN5Touch26IngameBlockSelectionScreenD2Ev|
|Touch::TButton::~TButton|No|()|IDK|_ZN5Touch7TButtonD1Ev|
|Touch::IngameBlockSelectionScreen::~IngameBlockSelectionScreen|No|()|IDK|_ZN5Touch26IngameBlockSelectionScreenD1Ev|
|non-virtual thunk to Touch::IngameBlockSelectionScreen::~IngameBlockSelectionScreen|No|()|IDK|_ZThn132_N5Touch26IngameBlockSelectionScreenD1Ev|
|Touch::IngameBlockSelectionScreen::~IngameBlockSelectionScreen|No|()|IDK|_ZN5Touch26IngameBlockSelectionScreenD0Ev|
|non-virtual thunk to Touch::IngameBlockSelectionScreen::~IngameBlockSelectionScreen|No|()|IDK|_ZThn132_N5Touch26IngameBlockSelectionScreenD0Ev|
|SpiderAttackGoal::canContinueToUse|No|()|IDK|_ZN16SpiderAttackGoal16canContinueToUseEv|
|MeleeAttackGoal::canContinueToUse|No|()|IDK|_ZN15MeleeAttackGoal16canContinueToUseEv|
|PathfinderMob::canSpawn|No|()|IDK|_ZN13PathfinderMob8canSpawnEv|
|Mob::canSpawn|No|()|IDK|_ZN3Mob8canSpawnEv|
|PathfinderMob::updateAi|No|()|IDK|_ZN13PathfinderMob8updateAiEv|
|Level::findPath|No|(Entity*, Entity*, float, bool, bool, bool, bool)|IDK|_ZN5Level8findPathEP6EntityS1_fbbbb|
|Mob::getSpeed|No|()|IDK|_ZN3Mob8getSpeedEv|
|Mob::updateAi|No|()|IDK|_ZN3Mob8updateAiEv|
|Entity::distanceTo|No|(Entity*)|IDK|_ZN6Entity10distanceToEPS_|
|PathfinderMob::getWalkingSpeedModifier|No|()|IDK|_ZN13PathfinderMob23getWalkingSpeedModifierEv|
|Mob::getWalkingSpeedModifier|No|()|IDK|_ZN3Mob23getWalkingSpeedModifierEv|
|FullChunkDataPacket::FullChunkDataPacket|No|(LevelChunk&)|IDK|_ZN19FullChunkDataPacketC1ER10LevelChunk|
|FullChunkDataPacket::~FullChunkDataPacket|No|()|IDK|_ZN19FullChunkDataPacketD1Ev|
|Tag::print|No|(PrintStream&) const|IDK|_ZNK3Tag5printER11PrintStream|
|Tag::setName|No|(std::string const&)|IDK|_ZN3Tag7setNameERKSs|
|Tag::getName|No|() const|IDK|_ZNK3Tag7getNameEv|
|BytesDataInput::readString|No|()|IDK|_ZN14BytesDataInput10readStringEv|
|BytesDataOutput::writeString|No|(std::string const&)|IDK|_ZN15BytesDataOutput11writeStringERKSs|
|vtable for TargetGoal|No|(undefined|IDK|_ZTV10TargetGoal|
|Goal::canInterrupt|No|()|IDK|_ZN4Goal12canInterruptEv|
|Goal::start|No|()|IDK|_ZN4Goal5startEv|
|Goal::tick|No|()|IDK|_ZN4Goal4tickEv|
|Goal::getRequiredControlFlags|No|()|IDK|_ZN4Goal23getRequiredControlFlagsEv|
|Feature::place|No|(TileSource*, TilePos const&, Random&)|IDK|_ZN7Feature5placeEP10TileSourceRK7TilePosR6Random|
|vtable for TransparentTile|No|(undefined|IDK|_ZTV15TransparentTile|
|RotatedPillarTile::getTexture|No|(signed char, int)|IDK|_ZN17RotatedPillarTile10getTextureEai|
|LogTile::onRemove|No|(TileSource*, int, int, int)|IDK|_ZN7LogTile8onRemoveEP10TileSourceiii|
|LogTile::getResourceCount|No|(Random*)|IDK|_ZN7LogTile16getResourceCountEP6Random|
|RotatedPillarTile::getPlacementDataValue|No|(Mob*, int, int, int, signed char, float, float, float, int)|IDK|_ZN17RotatedPillarTile21getPlacementDataValueEP3Mobiiiafffi|
|LogTile::getSpawnResourcesAuxValue|No|(int)|IDK|_ZN7LogTile25getSpawnResourcesAuxValueEi|
|LogTile::getDirTexture|No|(signed char, int)|IDK|_ZN7LogTile13getDirTextureEai|
|vtable for MegaTreeFeature|No|(undefined|IDK|_ZTV15MegaTreeFeature|
|Entity::reset|No|()|IDK|_ZN6Entity5resetEv|
|Entity::setPos|No|(float, float, float)|IDK|_ZN6Entity6setPosEfff|
|Entity::setPos|No|(Vec3 const&)|IDK|_ZN6Entity6setPosERK4Vec3|
|Entity::move|No|(float, float, float)|IDK|_ZN6Entity4moveEfff|
|Entity::moveTo|No|(float, float, float, float, float)|IDK|_ZN6Entity6moveToEfffff|
|Entity::moveRelative|No|(float, float, float)|IDK|_ZN6Entity12moveRelativeEfff|
|Entity::lerpTo|No|(float, float, float, float, float, int)|IDK|_ZN6Entity6lerpToEfffffi|
|Entity::lerpMotion|No|(float, float, float)|IDK|_ZN6Entity10lerpMotionEfff|
|Entity::turn|No|(float, float)|IDK|_ZN6Entity4turnEff|
|Entity::interpolateTurn|No|(float, float)|IDK|_ZN6Entity15interpolateTurnEff|
|Particle::normalTick|No|()|IDK|_ZN8Particle10normalTickEv|
|Entity::baseTick|No|()|IDK|_ZN6Entity8baseTickEv|
|Entity::rideTick|No|()|IDK|_ZN6Entity8rideTickEv|
|Entity::positionRider|No|(bool)|IDK|_ZN6Entity13positionRiderEb|
|Entity::getRidingHeight|No|()|IDK|_ZN6Entity15getRidingHeightEv|
|Entity::getRideHeight|No|()|IDK|_ZN6Entity13getRideHeightEv|
|Entity::ride|No|(Entity*)|IDK|_ZN6Entity4rideEPS_|
|Entity::intersects|No|(float, float, float, float, float, float)|IDK|_ZN6Entity10intersectsEffffff|
|Entity::isFree|No|(float, float, float, float)|IDK|_ZN6Entity6isFreeEffff|
|Entity::isFree|No|(float, float, float)|IDK|_ZN6Entity6isFreeEfff|
|Entity::isInWall|No|()|IDK|_ZN6Entity8isInWallEv|
|Entity::isInWater|No|() const|IDK|_ZNK6Entity9isInWaterEv|
|Entity::isInWaterOrRain|No|()|IDK|_ZN6Entity15isInWaterOrRainEv|
|Entity::isInLava|No|()|IDK|_ZN6Entity8isInLavaEv|
|Entity::isUnderLiquid|No|(Material const*)|IDK|_ZN6Entity13isUnderLiquidEPK8Material|
|Entity::makeStuckInWeb|No|()|IDK|_ZN6Entity14makeStuckInWebEv|
|Entity::getHeadHeight|No|()|IDK|_ZN6Entity13getHeadHeightEv|
|Entity::getShadowHeightOffs|No|()|IDK|_ZN6Entity19getShadowHeightOffsEv|
|Entity::isSkyLit|No|(float)|IDK|_ZN6Entity8isSkyLitEf|
|Entity::getBrightness|No|(float)|IDK|_ZN6Entity13getBrightnessEf|
|Entity::interactPreventDefault|No|()|IDK|_ZN6Entity22interactPreventDefaultEv|
|Entity::canInteractWith|No|(Player*)|IDK|_ZN6Entity15canInteractWithEP6Player|
|Entity::getInteractText|No|(Player*)|IDK|_ZN6Entity15getInteractTextEP6Player|
|Entity::playerTouch|No|(Player*)|IDK|_ZN6Entity11playerTouchEP6Player|
|Entity::push|No|(Entity*)|IDK|_ZN6Entity4pushEPS_|
|Entity::isPickable|No|()|IDK|_ZN6Entity10isPickableEv|
|Entity::isPushable|No|()|IDK|_ZN6Entity10isPushableEv|
|Entity::isShootable|No|()|IDK|_ZN6Entity11isShootableEv|
|Entity::isSneaking|No|()|IDK|_ZN6Entity10isSneakingEv|
|Entity::isAlive|No|()|IDK|_ZN6Entity7isAliveEv|
|Entity::isOnFire|No|()|IDK|_ZN6Entity8isOnFireEv|
|Entity::isCreativeModeAllowed|No|()|IDK|_ZN6Entity21isCreativeModeAllowedEv|
|Entity::shouldRenderAtSqrDistance|No|(float)|IDK|_ZN6Entity25shouldRenderAtSqrDistanceEf|
|Entity::hurt|No|(Entity*, int)|IDK|_ZN6Entity4hurtEPS_i|
|Entity::animateHurt|No|()|IDK|_ZN6Entity11animateHurtEv|
|Entity::getPickRadius|No|()|IDK|_ZN6Entity13getPickRadiusEv|
|Entity::spawnAtLocation|No|(int, int)|IDK|_ZN6Entity15spawnAtLocationEii|
|Entity::spawnAtLocation|No|(int, int, float)|IDK|_ZN6Entity15spawnAtLocationEiif|
|Entity::spawnAtLocation|No|(ItemInstance const&, float)|IDK|_ZN6Entity15spawnAtLocationERK12ItemInstancef|
|Entity::awardKillScore|No|(Entity*, int)|IDK|_ZN6Entity14awardKillScoreEPS_i|
|Entity::setEquippedSlot|No|(int, int, int)|IDK|_ZN6Entity15setEquippedSlotEiii|
|Entity::save|No|(CompoundTag&)|IDK|_ZN6Entity4saveER11CompoundTag|
|Entity::saveWithoutId|No|(CompoundTag&)|IDK|_ZN6Entity13saveWithoutIdER11CompoundTag|
|Entity::load|No|(CompoundTag&)|IDK|_ZN6Entity4loadER11CompoundTag|
|Entity::getEntityData|No|()|IDK|_ZN6Entity13getEntityDataEv|
|Entity::getEntityData|No|() const|IDK|_ZNK6Entity13getEntityDataEv|
|Entity::isItemEntity|No|()|IDK|_ZN6Entity12isItemEntityEv|
|Entity::isHangingEntity|No|()|IDK|_ZN6Entity15isHangingEntityEv|
|Entity::getAuxData|No|()|IDK|_ZN6Entity10getAuxDataEv|
|Entity::setRot|No|(float, float)|IDK|_ZN6Entity6setRotEff|
|Entity::setPos|No|(EntityPos*)|IDK|_ZN6Entity6setPosEP9EntityPos|
|Entity::resetPos|No|(bool, bool)|IDK|_ZN6Entity8resetPosEbb|
|Entity::outOfWorld|No|()|IDK|_ZN6Entity10outOfWorldEv|
|Entity::checkFallDamage|No|(float, bool)|IDK|_ZN6Entity15checkFallDamageEfb|
|Entity::causeFallDamage|No|(float)|IDK|_ZN6Entity15causeFallDamageEf|
|Entity::markHurt|No|()|IDK|_ZN6Entity8markHurtEv|
|Entity::burn|No|(int)|IDK|_ZN6Entity4burnEi|
|Entity::lavaHurt|No|()|IDK|_ZN6Entity8lavaHurtEv|
|Entity::playStepSound|No|(int, int, int, int)|IDK|_ZN6Entity13playStepSoundEiiii|
|Entity::checkInsideTiles|No|()|IDK|_ZN6Entity16checkInsideTilesEv|
|Entity::playSound|No|(std::string const&, float, float)|IDK|_ZN6Entity9playSoundERKSsff|
|Bush::getAABB|No|(TileSource*, int, int, int, AABB&, int, bool, int)|IDK|_ZN4Bush7getAABBEP10TileSourceiiiR4AABBibi|
|Bush::mayPlace|No|(TileSource*, int, int, int, signed char)|IDK|_ZN4Bush8mayPlaceEP10TileSourceiiia|
|Bush::mayPlace|No|(TileSource*, int, int, int)|IDK|_ZN4Bush8mayPlaceEP10TileSourceiii|
|Bush::neighborChanged|No|(TileSource*, int, int, int, int, int, int)|IDK|_ZN4Bush15neighborChangedEP10TileSourceiiiiii|
|Bush::canSurvive|No|(TileSource*, int, int, int)|IDK|_ZN4Bush10canSurviveEP10TileSourceiii|
|Bush::mayPlaceOn|No|(int)|IDK|_ZN4Bush10mayPlaceOnEi|
|Bush::checkAlive|No|(TileSource*, int, int, int)|IDK|_ZN4Bush10checkAliveEP10TileSourceiii|
|MeleeAttackGoal::canUse|No|()|IDK|_ZN15MeleeAttackGoal6canUseEv|
|MeleeAttackGoal::start|No|()|IDK|_ZN15MeleeAttackGoal5startEv|
|MeleeAttackGoal::stop|No|()|IDK|_ZN15MeleeAttackGoal4stopEv|
|MeleeAttackGoal::tick|No|()|IDK|_ZN15MeleeAttackGoal4tickEv|
|vtable for LevelListener|No|(undefined|IDK|_ZTV13LevelListener|
|Item::getMaxStackSize|No|(ItemInstance const*)|IDK|_ZN4Item15getMaxStackSizeEPK12ItemInstance|
|Item::setMaxStackSize|No|(int)|IDK|_ZN4Item15setMaxStackSizeEi|
|Item::canBeDepleted|No|()|IDK|_ZN4Item13canBeDepletedEv|
|TileItem::getIconYOffset|No|() const|IDK|_ZNK8TileItem14getIconYOffsetEv|
|Item::setIcon|No|(std::string const&, int)|IDK|_ZN4Item7setIconERKSsi|
|Item::setIcon|No|(TextureUVCoordinateSet)|IDK|_ZN4Item7setIconE22TextureUVCoordinateSet|
|Item::isMirroredArt|No|() const|IDK|_ZNK4Item13isMirroredArtEv|
|Item::use|No|(ItemInstance*, Level*, Player*)|IDK|_ZN4Item3useEP12ItemInstanceP5LevelP6Player|
|Item::getMaxUseDuration|No|() const|IDK|_ZNK4Item17getMaxUseDurationEv|
|Item::useTimeDepleted|No|(ItemInstance*, Level*, Player*)|IDK|_ZN4Item15useTimeDepletedEP12ItemInstanceP5LevelP6Player|
|Item::getUseAnimation|No|() const|IDK|_ZNK4Item15getUseAnimationEv|
|Item::releaseUsing|No|(ItemInstance*, Player*, int)|IDK|_ZN4Item12releaseUsingEP12ItemInstanceP6Playeri|
|Item::getDestroySpeed|No|(ItemInstance*, Tile*)|IDK|_ZN4Item15getDestroySpeedEP12ItemInstanceP4Tile|
|Item::canDestroySpecial|No|(Tile const*) const|IDK|_ZNK4Item17canDestroySpecialEPK4Tile|
|Item::isStackedByData|No|() const|IDK|_ZNK4Item15isStackedByDataEv|
|Item::getMaxDamage|No|()|IDK|_ZN4Item12getMaxDamageEv|
|Item::getAttackDamage|No|(Entity*)|IDK|_ZN4Item15getAttackDamageEP6Entity|
|Item::hurtEnemy|No|(ItemInstance*, Mob*, Mob*)|IDK|_ZN4Item9hurtEnemyEP12ItemInstanceP3MobS3_|
|Item::interactEnemy|No|(ItemInstance*, Mob*, Player*)|IDK|_ZN4Item13interactEnemyEP12ItemInstanceP3MobP6Player|
|Item::mineBlock|No|(ItemInstance*, int, int, int, int, Mob*)|IDK|_ZN4Item9mineBlockEP12ItemInstanceiiiiP3Mob|
|Item::handEquipped|No|()|IDK|_ZN4Item12handEquippedEv|
|Item::isHandEquipped|No|() const|IDK|_ZNK4Item14isHandEquippedEv|
|Item::isFood|No|() const|IDK|_ZNK4Item6isFoodEv|
|Item::isSeed|No|() const|IDK|_ZNK4Item6isSeedEv|
|Item::isArmor|No|() const|IDK|_ZNK4Item7isArmorEv|
|Item::getDescription|No|() const|IDK|_ZNK4Item14getDescriptionEv|
|Item::setDescriptionId|No|(std::string const&)|IDK|_ZN4Item16setDescriptionIdERKSs|
|TileItem::isEmissive|No|(int) const|IDK|_ZNK8TileItem10isEmissiveEi|
|TileItem::getDescriptionId|No|(ItemInstance const*) const|IDK|_ZNK8TileItem16getDescriptionIdEPK12ItemInstance|
|vtable for DirectionalTile|No|(undefined|IDK|_ZTV15DirectionalTile|
|vtable for HalfTransparentTile|No|(undefined|IDK|_ZTV19HalfTransparentTile|
|HeavyTile::getTickDelay|No|()|IDK|_ZN9HeavyTile12getTickDelayEv|
|HeavyTile::tick|No|(TileSource*, int, int, int, Random*)|IDK|_ZN9HeavyTile4tickEP10TileSourceiiiP6Random|
|HeavyTile::neighborChanged|No|(TileSource*, int, int, int, int, int, int)|IDK|_ZN9HeavyTile15neighborChangedEP10TileSourceiiiiii|
|HeavyTile::onPlace|No|(TileSource*, int, int, int)|IDK|_ZN9HeavyTile7onPlaceEP10TileSourceiii|
|EntityTile::neighborChanged|No|(TileSource*, int, int, int, int, int, int)|IDK|_ZN10EntityTile15neighborChangedEP10TileSourceiiiiii|
|EntityTile::triggerEvent|No|(TileSource*, int, int, int, int, int)|IDK|_ZN10EntityTile12triggerEventEP10TileSourceiiiii|
|EntityTile::newTileEntity|No|(TilePos const&)|IDK|_ZN10EntityTile13newTileEntityERK7TilePos|
|TileItem::getIcon|No|(int, int, bool) const|IDK|_ZNK8TileItem7getIconEiib|
|Item::getLevelDataForAuxValue|No|(int) const|IDK|_ZNK4Item23getLevelDataForAuxValueEi|
|Button::mouseReleased|No|(Minecraft*, int, int, int)|IDK|_ZN6Button13mouseReleasedEP9Minecraftiii|
|Button::clicked|No|(Minecraft*, int, int)|IDK|_ZN6Button7clickedEP9Minecraftii|
|Button::released|No|(int, int)|IDK|_ZN6Button8releasedEii|
|Button::setPressed|No|()|IDK|_ZN6Button10setPressedEv|
|Button::getYImage|No|(bool)|IDK|_ZN6Button9getYImageEb|
|Button::renderFace|No|(Minecraft*, int, int)|IDK|_ZN6Button10renderFaceEP9Minecraftii|
|Biome::setColor|No|(int)|IDK|_ZN5Biome8setColorEi|
|Biome::setColor|No|(int, bool)|IDK|_ZN5Biome8setColorEib|
|Biome::getTreeFeature|No|(Random*)|IDK|_ZN5Biome14getTreeFeatureEP6Random|
|Biome::getGrassFeature|No|(Random*)|IDK|_ZN5Biome15getGrassFeatureEP6Random|
|Biome::getTemperature|No|()|IDK|_ZN5Biome14getTemperatureEv|
|Biome::adjustScale|No|(float)|IDK|_ZN5Biome11adjustScaleEf|
|Biome::adjustDepth|No|(float)|IDK|_ZN5Biome11adjustDepthEf|
|Biome::getSkyColor|No|(float)|IDK|_ZN5Biome11getSkyColorEf|
|Biome::getMobs|No|(int)|IDK|_ZN5Biome7getMobsEi|
|Biome::getCreatureProbability|No|()|IDK|_ZN5Biome22getCreatureProbabilityEv|
|Biome::getFoliageColor|No|()|IDK|_ZN5Biome15getFoliageColorEv|
|Biome::getRandomFlowerTypeAndData|No|(Random&, TilePos const&)|IDK|_ZN5Biome26getRandomFlowerTypeAndDataER6RandomRK7TilePos|
|Biome::buildSurfaceAt|No|(Random&, LevelChunk&, TilePos const&, float)|IDK|_ZN5Biome14buildSurfaceAtER6RandomR10LevelChunkRK7TilePosf|
|Biome::getGrassColor|No|(TilePos const&)|IDK|_ZN5Biome13getGrassColorERK7TilePos|
|Biome::getTemperatureCategory|No|() const|IDK|_ZNK5Biome22getTemperatureCategoryEv|
|Biome::isSame|No|(Biome*)|IDK|_ZN5Biome6isSameEPS_|
|Biome::isHumid|No|()|IDK|_ZN5Biome7isHumidEv|
|Biome::createMutatedCopy|No|(int)|IDK|_ZN5Biome17createMutatedCopyEi|
|Tile::redStoneDust|No|(undefined|IDK|_ZN4Tile12redStoneDustE|
|Tile::netherFence|No|(undefined|IDK|_ZN4Tile11netherFenceE|
|PathfinderMob::MAX_TURN|No|(undefined|IDK|_ZN13PathfinderMob8MAX_TURNE|
|BiomeDecorator::gaussianKernel|No|(undefined|IDK|_ZN14BiomeDecorator14gaussianKernelE|
|BiomeDecorator::SNOW_SCALE|No|(undefined|IDK|_ZN14BiomeDecorator10SNOW_SCALEE|
|BiomeDecorator::SNOW_CUTOFF|No|(undefined|IDK|_ZN14BiomeDecorator11SNOW_CUTOFFE|
|TouchscreenInput::BUTTONS_TRANSPARENCY|No|(undefined|IDK|_ZN16TouchscreenInput20BUTTONS_TRANSPARENCYE|
|ChunkSource::getExistingChunk|No|(ChunkPos const&)|IDK|_ZN11ChunkSource16getExistingChunkERK8ChunkPos|
|ChunkSource::requestChunk|No|(ChunkPos const&, ChunkSource::LoadMode)|IDK|_ZN11ChunkSource12requestChunkERK8ChunkPosNS_8LoadModeE|
|ChunkSource::releaseChunk|No|(LevelChunk&)|IDK|_ZN11ChunkSource12releaseChunkER10LevelChunk|
|ChunkSource::postProcess|No|(ChunkViewSource&)|IDK|_ZN11ChunkSource11postProcessER15ChunkViewSource|
|ChunkSource::postProcessMobsAt|No|(TileSource*, int, int, Random&)|IDK|_ZN11ChunkSource17postProcessMobsAtEP10TileSourceiiR6Random|
|ChunkSource::saveLiveChunk|No|(LevelChunk&)|IDK|_ZN11ChunkSource13saveLiveChunkER10LevelChunk|
|ChunkSource::hintDiscardBatchBegin|No|()|IDK|_ZN11ChunkSource21hintDiscardBatchBeginEv|
|ChunkSource::hintDiscardBatchEnd|No|()|IDK|_ZN11ChunkSource19hintDiscardBatchEndEv|
|ChunkSource::getStoredChunks|No|() const|IDK|_ZNK11ChunkSource15getStoredChunksEv|
|Model::onAppSuspended|No|()|IDK|_ZN5Model14onAppSuspendedEv|
|Model::clear|No|()|IDK|_ZN5Model5clearEv|
|Mob::reset|No|()|IDK|_ZN3Mob5resetEv|
|Mob::lerpTo|No|(float, float, float, float, float, int)|IDK|_ZN3Mob6lerpToEfffffi|
|Mob::normalTick|No|()|IDK|_ZN3Mob10normalTickEv|
|Mob::baseTick|No|()|IDK|_ZN3Mob8baseTickEv|
|Mob::rideTick|No|()|IDK|_ZN3Mob8rideTickEv|
|Mob::getHeadHeight|No|()|IDK|_ZN3Mob13getHeadHeightEv|
|Mob::isPickable|No|()|IDK|_ZN3Mob10isPickableEv|
|Mob::isPushable|No|()|IDK|_ZN3Mob10isPushableEv|
|Mob::isShootable|No|()|IDK|_ZN3Mob11isShootableEv|
|Mob::isSneaking|No|()|IDK|_ZN3Mob10isSneakingEv|
|Mob::isAlive|No|()|IDK|_ZN3Mob7isAliveEv|
|Mob::isOnFire|No|()|IDK|_ZN3Mob8isOnFireEv|
|Mob::hurt|No|(Entity*, int)|IDK|_ZN3Mob4hurtEP6Entityi|
|Mob::animateHurt|No|()|IDK|_ZN3Mob11animateHurtEv|
|Mob::handleEntityEvent|No|(char)|IDK|_ZN3Mob17handleEntityEventEc|
|Mob::getEntityData|No|()|IDK|_ZN3Mob13getEntityDataEv|
|Mob::getEntityData|No|() const|IDK|_ZNK3Mob13getEntityDataEv|
|Mob::setSize|No|(float, float)|IDK|_ZN3Mob7setSizeEff|
|Mob::outOfWorld|No|()|IDK|_ZN3Mob10outOfWorldEv|
|Mob::causeFallDamage|No|(float)|IDK|_ZN3Mob15causeFallDamageEf|
|Mob::readAdditionalSaveData|No|(CompoundTag*)|IDK|_ZN3Mob22readAdditionalSaveDataEP11CompoundTag|
|Mob::addAdditionalSaveData|No|(CompoundTag*)|IDK|_ZN3Mob21addAdditionalSaveDataEP11CompoundTag|
|Mob::postInit|No|()|IDK|_ZN3Mob8postInitEv|
|Mob::knockback|No|(Entity*, int, float, float)|IDK|_ZN3Mob9knockbackEP6Entityiff|
|Mob::die|No|(Entity*)|IDK|_ZN3Mob3dieEP6Entity|
|Mob::canSee|No|(Entity*)|IDK|_ZN3Mob6canSeeEP6Entity|
|Mob::onLadder|No|()|IDK|_ZN3Mob8onLadderEv|
|Mob::spawnAnim|No|()|IDK|_ZN3Mob9spawnAnimEv|
|Mob::getTexture|No|()|IDK|_ZN3Mob10getTextureEv|
|Mob::isSleeping|No|()|IDK|_ZN3Mob10isSleepingEv|
|Mob::isWaterMob|No|()|IDK|_ZN3Mob10isWaterMobEv|
|Mob::setSneaking|No|(bool)|IDK|_ZN3Mob11setSneakingEb|
|Mob::getVoicePitch|No|()|IDK|_ZN3Mob13getVoicePitchEv|
|Mob::playAmbientSound|No|()|IDK|_ZN3Mob16playAmbientSoundEv|
|Mob::getAmbientSoundInterval|No|()|IDK|_ZN3Mob23getAmbientSoundIntervalEv|
|Mob::getItemInHandIcon|No|(ItemInstance const*, int)|IDK|_ZN3Mob17getItemInHandIconEPK12ItemInstancei|
|Mob::superTick|No|()|IDK|_ZN3Mob9superTickEv|
|Mob::heal|No|(int)|IDK|_ZN3Mob4healEi|
|Mob::actuallyHurt|No|(int)|IDK|_ZN3Mob12actuallyHurtEi|
|Mob::getArmorValue|No|()|IDK|_ZN3Mob13getArmorValueEv|
|Mob::pick|No|(float, float, bool)|IDK|_ZN3Mob4pickEffb|
|Mob::travel|No|(float, float)|IDK|_ZN3Mob6travelEff|
|Mob::updateWalkAnim|No|()|IDK|_ZN3Mob14updateWalkAnimEv|
|Mob::aiStep|No|()|IDK|_ZN3Mob6aiStepEv|
|Mob::lookAt|No|(Entity*, float, float)|IDK|_ZN3Mob6lookAtEP6Entityff|
|Mob::isLookingAtAnEntity|No|()|IDK|_ZN3Mob19isLookingAtAnEntityEv|
|Mob::beforeRemove|No|()|IDK|_ZN3Mob12beforeRemoveEv|
|Mob::shouldDespawn|No|() const|IDK|_ZNK3Mob13shouldDespawnEv|
|Mob::getAttackAnim|No|(float)|IDK|_ZN3Mob13getAttackAnimEf|
|Mob::getPos|No|(float)|IDK|_ZN3Mob6getPosEf|
|Mob::getLookAngle|No|() const|IDK|_ZNK3Mob12getLookAngleEv|
|Mob::getViewVector|No|(float) const|IDK|_ZNK3Mob13getViewVectorEf|
|Mob::swing|No|()|IDK|_ZN3Mob5swingEv|
|Mob::getMaxHeadXRot|No|()|IDK|_ZN3Mob14getMaxHeadXRotEv|
|Mob::getLastHurtByMob|No|()|IDK|_ZN3Mob16getLastHurtByMobEv|
|Mob::setLastHurtByMob|No|(Mob*)|IDK|_ZN3Mob16setLastHurtByMobEPS_|
|Mob::getLastHurtMob|No|()|IDK|_ZN3Mob14getLastHurtMobEv|
|Mob::setLastHurtMob|No|(Entity*)|IDK|_ZN3Mob14setLastHurtMobEP6Entity|
|Mob::getTarget|No|()|IDK|_ZN3Mob9getTargetEv|
|Mob::setTarget|No|(Mob*)|IDK|_ZN3Mob9setTargetEPS_|
|Mob::doHurtTarget|No|(Entity*)|IDK|_ZN3Mob12doHurtTargetEP6Entity|
|Mob::canBeControlledByRider|No|()|IDK|_ZN3Mob22canBeControlledByRiderEv|
|Mob::teleportTo|No|(float, float, float)|IDK|_ZN3Mob10teleportToEfff|
|Mob::removeWhenFarAway|No|()|IDK|_ZN3Mob17removeWhenFarAwayEv|
|Mob::getDeathLoot|No|()|IDK|_ZN3Mob12getDeathLootEv|
|Mob::dropDeathLoot|No|()|IDK|_ZN3Mob13dropDeathLootEv|
|Mob::isImmobile|No|()|IDK|_ZN3Mob10isImmobileEv|
|Mob::jumpFromGround|No|()|IDK|_ZN3Mob14jumpFromGroundEv|
|Mob::serverAiMobStep|No|()|IDK|_ZN3Mob15serverAiMobStepEv|
|Mob::getSoundVolume|No|()|IDK|_ZN3Mob14getSoundVolumeEv|
|Mob::getAmbientSound|No|()|IDK|_ZN3Mob15getAmbientSoundEv|
|Mob::getHurtSound|No|()|IDK|_ZN3Mob12getHurtSoundEv|
|Mob::getDeathSound|No|()|IDK|_ZN3Mob13getDeathSoundEv|
|Mob::getDamageAfterArmorAbsorb|No|(int)|IDK|_ZN3Mob25getDamageAfterArmorAbsorbEi|
|Mob::hurtArmor|No|(int)|IDK|_ZN3Mob9hurtArmorEi|
|Mob::useNewAi|No|()|IDK|_ZN3Mob8useNewAiEv|
|EntityRenderer::postRender|No|(Entity*, float, float, float, float, float)|IDK|_ZN14EntityRenderer10postRenderEP6Entityfffff|
|Layer::init|No|(long long)|IDK|_ZN5Layer4initEx|
|Layer::modeOrRandom|No|(int, int, int, int)|IDK|_ZN5Layer12modeOrRandomEiiii|
|Screen::updateEvents|No|()|IDK|_ZN6Screen12updateEventsEv|
|Screen::mouseEvent|No|()|IDK|_ZN6Screen10mouseEventEv|
|Screen::keyboardEvent|No|()|IDK|_ZN6Screen13keyboardEventEv|
|Screen::keyboardTextEvent|No|()|IDK|_ZN6Screen17keyboardTextEventEv|
|Screen::controllerEvent|No|()|IDK|_ZN6Screen15controllerEventEv|
|Screen::handleBackEvent|No|(bool)|IDK|_ZN6Screen15handleBackEventEb|
|Screen::renderBackground|No|(int)|IDK|_ZN6Screen16renderBackgroundEi|
|Screen::renderDirtBackground|No|(int)|IDK|_ZN6Screen20renderDirtBackgroundEi|
|Screen::renderMenuBackground|No|(float)|IDK|_ZN6Screen20renderMenuBackgroundEf|
|Screen::renderGameBehind|No|()|IDK|_ZN6Screen16renderGameBehindEv|
|Screen::isPauseScreen|No|()|IDK|_ZN6Screen13isPauseScreenEv|
|Screen::isErrorScreen|No|()|IDK|_ZN6Screen13isErrorScreenEv|
|Screen::isInGameScreen|No|()|IDK|_ZN6Screen14isInGameScreenEv|
|Screen::closeOnPlayerHurt|No|()|IDK|_ZN6Screen17closeOnPlayerHurtEv|
|Screen::lostFocus|No|()|IDK|_ZN6Screen9lostFocusEv|
|Screen::toGUICoordinate|No|(int&, int&)|IDK|_ZN6Screen15toGUICoordinateERiS0_|
|Screen::supppressedBySubWindow|No|()|IDK|_ZN6Screen22supppressedBySubWindowEv|
|Screen::setTextboxText|No|(std::string const&)|IDK|_ZN6Screen14setTextboxTextERKSs|
|Screen::updateTabButtonSelection|No|()|IDK|_ZN6Screen24updateTabButtonSelectionEv|
|Screen::controllerDirectionChanged|No|(int, Controller::StickDirection)|IDK|_ZN6Screen26controllerDirectionChangedEiN10Controller14StickDirectionE|
|Screen::controllerDirectionHeld|No|(int, Controller::StickDirection)|IDK|_ZN6Screen23controllerDirectionHeldEiN10Controller14StickDirectionE|
|Screen::keyboardNewChar|No|(std::string const&, bool)|IDK|_ZN6Screen15keyboardNewCharERKSsb|
|Screen::shouldSendAllKeyStates|No|()|IDK|_ZN6Screen22shouldSendAllKeyStatesEv|
|AgableMob::setSize|No|(float, float)|IDK|_ZN9AgableMob7setSizeEff|
|AgableMob::aiStep|No|()|IDK|_ZN9AgableMob6aiStepEv|
|AgableMob::isBaby|No|()|IDK|_ZN9AgableMob6isBabyEv|
|ChunkSource::acquireDiscarded|No|(std::unique_ptr<LevelChunk, std::default_delete<LevelChunk> >&)|IDK|_ZN11ChunkSource16acquireDiscardedERSt10unique_ptrI10LevelChunkSt14default_deleteIS1_EE|
|Animal::hurt|No|(Entity*, int)|IDK|_ZN6Animal4hurtEP6Entityi|
|Animal::readAdditionalSaveData|No|(CompoundTag*)|IDK|_ZN6Animal22readAdditionalSaveDataEP11CompoundTag|
|Animal::addAdditionalSaveData|No|(CompoundTag*)|IDK|_ZN6Animal21addAdditionalSaveDataEP11CompoundTag|
|Animal::getAmbientSoundInterval|No|()|IDK|_ZN6Animal23getAmbientSoundIntervalEv|
|Animal::aiStep|No|()|IDK|_ZN6Animal6aiStepEv|
|Animal::removeWhenFarAway|No|()|IDK|_ZN6Animal17removeWhenFarAwayEv|
|Animal::getWalkTargetValue|No|(TilePos const&)|IDK|_ZN6Animal18getWalkTargetValueERK7TilePos|
|Animal::findAttackTarget|No|()|IDK|_ZN6Animal16findAttackTargetEv|
|Animal::canMate|No|(Animal const*) const|IDK|_ZNK6Animal7canMateEPKS_|
|Monster::hurt|No|(Entity*, int)|IDK|_ZN7Monster4hurtEP6Entityi|
|Monster::readAdditionalSaveData|No|(CompoundTag*)|IDK|_ZN7Monster22readAdditionalSaveDataEP11CompoundTag|
|Monster::addAdditionalSaveData|No|(CompoundTag*)|IDK|_ZN7Monster21addAdditionalSaveDataEP11CompoundTag|
|Monster::canSpawn|No|()|IDK|_ZN7Monster8canSpawnEv|
|Monster::shouldDespawn|No|() const|IDK|_ZNK7Monster13shouldDespawnEv|
|Monster::doHurtTarget|No|(Entity*)|IDK|_ZN7Monster12doHurtTargetEP6Entity|
|Monster::getWalkTargetValue|No|(TilePos const&)|IDK|_ZN7Monster18getWalkTargetValueERK7TilePos|
|Monster::checkHurtTarget|No|(Entity*, float)|IDK|_ZN7Monster15checkHurtTargetEP6Entityf|
|Monster::getAttackDamage|No|(Entity*)|IDK|_ZN7Monster15getAttackDamageEP6Entity|
|Monster::getAttackTime|No|()|IDK|_ZN7Monster13getAttackTimeEv|
|Goal::stop|No|()|IDK|_ZN4Goal4stopEv|
|Screen::hasClippingArea|No|(IntRectangle&)|IDK|_ZN6Screen15hasClippingAreaER12IntRectangle|
|MutatedBiome::decorate|No|(TileSource*, Random&, TilePos const&, bool)|IDK|_ZN12MutatedBiome8decorateEP10TileSourceR6RandomRK7TilePosb|
|MutatedBiome::buildSurfaceAt|No|(Random&, LevelChunk&, TilePos const&, float)|IDK|_ZN12MutatedBiome14buildSurfaceAtER6RandomR10LevelChunkRK7TilePosf|
|MutatedBiome::getCreatureProbability|No|()|IDK|_ZN12MutatedBiome22getCreatureProbabilityEv|
|MutatedBiome::getTreeFeature|No|(Random*)|IDK|_ZN12MutatedBiome14getTreeFeatureEP6Random|
|MutatedBiome::getFoliageColor|No|()|IDK|_ZN12MutatedBiome15getFoliageColorEv|
|MutatedBiome::getGrassColor|No|(TilePos const&)|IDK|_ZN12MutatedBiome13getGrassColorERK7TilePos|
|MutatedBiome::isSame|No|(Biome*)|IDK|_ZN12MutatedBiome6isSameEP5Biome|
|MutatedBiome::getTemperatureCategory|No|() const|IDK|_ZNK12MutatedBiome22getTemperatureCategoryEv|
|ShortTag::write|No|(IDataOutput*)|IDK|_ZN8ShortTag5writeEP11IDataOutput|
|ShortTag::load|No|(IDataInput*)|IDK|_ZN8ShortTag4loadEP10IDataInput|
|ShortTag::getId|No|() const|IDK|_ZNK8ShortTag5getIdEv|
|FloatTag::write|No|(IDataOutput*)|IDK|_ZN8FloatTag5writeEP11IDataOutput|
|FloatTag::load|No|(IDataInput*)|IDK|_ZN8FloatTag4loadEP10IDataInput|
|FloatTag::getId|No|() const|IDK|_ZNK8FloatTag5getIdEv|
|Level::isNaturalDimension|No|()|IDK|_ZN5Level18isNaturalDimensionEv|
|Level::updateSleepingPlayerList|No|()|IDK|_ZN5Level24updateSleepingPlayerListEv|
|Item::getIconYOffset|No|() const|IDK|_ZNK4Item14getIconYOffsetEv|
|Item::isEmissive|No|(int) const|IDK|_ZNK4Item10isEmissiveEi|
|BeetrootTile::getBaseSeed|No|()|IDK|_ZN12BeetrootTile11getBaseSeedEv|
|BeetrootTile::getBasePlantId|No|()|IDK|_ZN12BeetrootTile14getBasePlantIdEv|
|Arrow::getShadowRadius|No|()|IDK|_ZN5Arrow15getShadowRadiusEv|
|Arrow::getShadowHeightOffs|No|()|IDK|_ZN5Arrow19getShadowHeightOffsEv|
|Arrow::getEntityTypeId|No|() const|IDK|_ZNK5Arrow15getEntityTypeIdEv|
|Arrow::getAuxData|No|()|IDK|_ZN5Arrow10getAuxDataEv|
|AppPlatform::saveScreenshot|No|(std::string const&, int, int)|IDK|_ZN11AppPlatform14saveScreenshotERKSsii|
|AppPlatform::playSound|No|(std::string const&, float, float)|IDK|_ZN11AppPlatform9playSoundERKSsff|
|AppPlatform::showDialog|No|(int)|IDK|_ZN11AppPlatform10showDialogEi|
|AppPlatform::createUserInput|No|()|IDK|_ZN11AppPlatform15createUserInputEv|
|AppPlatform::getUserInputStatus|No|()|IDK|_ZN11AppPlatform18getUserInputStatusEv|
|AppPlatform::getUserInput|No|()|IDK|_ZN11AppPlatform12getUserInputEv|
|AppPlatform::checkLicense|No|()|IDK|_ZN11AppPlatform12checkLicenseEv|
|AppPlatform::hasBuyButtonWhenInvalidLicense|No|()|IDK|_ZN11AppPlatform30hasBuyButtonWhenInvalidLicenseEv|
|AppPlatform::uploadPlatformDependentData|No|(int, void*)|IDK|_ZN11AppPlatform27uploadPlatformDependentDataEiPv|
|AppPlatform::_tick|No|()|IDK|_ZN11AppPlatform5_tickEv|
|AppPlatform::getScreenWidth|No|()|IDK|_ZN11AppPlatform14getScreenWidthEv|
|AppPlatform::getScreenHeight|No|()|IDK|_ZN11AppPlatform15getScreenHeightEv|
|AppPlatform::getPixelsPerMillimeter|No|()|IDK|_ZN11AppPlatform22getPixelsPerMillimeterEv|
|AppPlatform::isNetworkEnabled|No|(bool)|IDK|_ZN11AppPlatform16isNetworkEnabledEb|
|AppPlatform::openLoginWindow|No|()|IDK|_ZN11AppPlatform15openLoginWindowEv|
|AppPlatform::isPowerVR|No|()|IDK|_ZN11AppPlatform9isPowerVREv|
|AppPlatform::getKeyFromKeyCode|No|(int, int, int)|IDK|_ZN11AppPlatform17getKeyFromKeyCodeEiii|
|AppPlatform::buyGame|No|()|IDK|_ZN11AppPlatform7buyGameEv|
|AppPlatform::finish|No|()|IDK|_ZN11AppPlatform6finishEv|
|AppPlatform::supportsTouchscreen|No|()|IDK|_ZN11AppPlatform19supportsTouchscreenEv|
|AppPlatform::hasIDEProfiler|No|()|IDK|_ZN11AppPlatform14hasIDEProfilerEv|
|AppPlatform::supportsVibration|No|()|IDK|_ZN11AppPlatform17supportsVibrationEv|
|AppPlatform::vibrate|No|(int)|IDK|_ZN11AppPlatform7vibrateEi|
|AppPlatform::showKeyboard|No|(std::string const&, int, bool)|IDK|_ZN11AppPlatform12showKeyboardERKSsib|
|AppPlatform::hideKeyboard|No|()|IDK|_ZN11AppPlatform12hideKeyboardEv|
|AppPlatform::updateTextBoxText|No|(std::string const&)|IDK|_ZN11AppPlatform17updateTextBoxTextERKSs|
|AppPlatform::isKeyboardVisible|No|()|IDK|_ZN11AppPlatform17isKeyboardVisibleEv|
|AppPlatform::getLoginInformation|No|()|IDK|_ZN11AppPlatform19getLoginInformationEv|
|AppPlatform::setLoginInformation|No|(LoginInformation const&)|IDK|_ZN11AppPlatform19setLoginInformationERK16LoginInformation|
|AppPlatform::clearSessionIDAndRefreshToken|No|()|IDK|_ZN11AppPlatform29clearSessionIDAndRefreshTokenEv|
|AppPlatform::statsTrackData|No|(std::string const&, std::string const&)|IDK|_ZN11AppPlatform14statsTrackDataERKSsS1_|
|AppPlatform::updateStatsUserData|No|(std::string const&, std::string const&)|IDK|_ZN11AppPlatform19updateStatsUserDataERKSsS1_|
|AppPlatform::getAvailableMemory|No|()|IDK|_ZN11AppPlatform18getAvailableMemoryEv|
|AppPlatform::getBroadcastAddresses|No|()|IDK|_ZN11AppPlatform21getBroadcastAddressesEv|
|Entity::normalTick|No|()|IDK|_ZN6Entity10normalTickEv|
|UnderworldFeature::apply|No|(ChunkSource*, LevelChunk&, BiomeSource*, Random&)|IDK|_ZN17UnderworldFeature5applyEP11ChunkSourceR10LevelChunkP11BiomeSourceR6Random|
|Screen::buttonClicked|No|(Button*)|IDK|_ZN6Screen13buttonClickedEP6Button|
|Slider::mouseClicked|No|(Minecraft*, int, int, int)|IDK|_ZN6Slider12mouseClickedEP9Minecraftiii|
|TextBox::mouseReleased|No|(Minecraft*, int, int, int)|IDK|_ZN7TextBox13mouseReleasedEP9Minecraftiii|
|TextBox::suppressOtherGUI|No|()|IDK|_ZN7TextBox16suppressOtherGUIEv|
|LightGemTile::getResource|No|(int, Random*)|IDK|_ZN12LightGemTile11getResourceEiP6Random|
|Item::yellowDust|No|(undefined|IDK|_ZN4Item10yellowDustE|
|StairTile::getPlacementDataValue|No|(Mob*, int, int, int, signed char, float, float, float, int)|IDK|_ZN9StairTile21getPlacementDataValueEP3Mobiiiafffi|
|StairTile::animateTick|No|(TileSource*, int, int, int, Random*)|IDK|_ZN9StairTile11animateTickEP10TileSourceiiiP6Random|
|StairTile::attack|No|(Player*, int, int, int)|IDK|_ZN9StairTile6attackEP6Playeriii|
|StairTile::destroy|No|(TileSource*, int, int, int, int)|IDK|_ZN9StairTile7destroyEP10TileSourceiiii|
|StairTile::getExplosionResistance|No|(Entity*)|IDK|_ZN9StairTile22getExplosionResistanceEP6Entity|
|StairTile::getResourceCount|No|(Random*)|IDK|_ZN9StairTile16getResourceCountEP6Random|
|StairTile::getTexture|No|(signed char, int)|IDK|_ZN9StairTile10getTextureEai|
|StairTile::getTexture|No|(signed char)|IDK|_ZN9StairTile10getTextureEa|
|StairTile::getTexture|No|(TileSource*, int, int, int, signed char)|IDK|_ZN9StairTile10getTextureEP10TileSourceiiia|
|StairTile::getTickDelay|No|()|IDK|_ZN9StairTile12getTickDelayEv|
|StairTile::getTileAABB|No|(TileSource*, int, int, int, AABB&)|IDK|_ZN9StairTile11getTileAABBEP10TileSourceiiiR4AABB|
|StairTile::handleEntityInside|No|(TileSource*, int, int, int, Entity*, Vec3&)|IDK|_ZN9StairTile18handleEntityInsideEP10TileSourceiiiP6EntityR4Vec3|
|StairTile::mayPick|No|()|IDK|_ZN9StairTile7mayPickEv|
|StairTile::mayPick|No|(int, bool)|IDK|_ZN9StairTile7mayPickEib|
|StairTile::mayPlace|No|(TileSource*, int, int, int, signed char)|IDK|_ZN9StairTile8mayPlaceEP10TileSourceiiia|
|StairTile::onPlace|No|(TileSource*, int, int, int)|IDK|_ZN9StairTile7onPlaceEP10TileSourceiii|
|StairTile::onRemove|No|(TileSource*, int, int, int)|IDK|_ZN9StairTile8onRemoveEP10TileSourceiii|
|StairTile::prepareRender|No|(TileSource*, int, int, int)|IDK|_ZN9StairTile13prepareRenderEP10TileSourceiii|
|StairTile::stepOn|No|(Entity*, int, int, int)|IDK|_ZN9StairTile6stepOnEP6Entityiii|
|StairTile::tick|No|(TileSource*, int, int, int, Random*)|IDK|_ZN9StairTile4tickEP10TileSourceiiiP6Random|
|StairTile::use|No|(Player*, int, int, int)|IDK|_ZN9StairTile3useEP6Playeriii|
|StairTile::wasExploded|No|(TileSource*, int, int, int)|IDK|_ZN9StairTile11wasExplodedEP10TileSourceiii|
|SpawnData::~SpawnData|No|()|IDK|_ZN9SpawnDataD2Ev|
|vtable for SpawnData|No|(undefined|IDK|_ZTV9SpawnData|
|SpawnData::~SpawnData|No|()|IDK|_ZN9SpawnDataD1Ev|
|WaterlilyTile::getColor|No|(int)|IDK|_ZN13WaterlilyTile8getColorEi|
|WaterlilyTile::getColor|No|(TileSource*, int, int, int)|IDK|_ZN13WaterlilyTile8getColorEP10TileSourceiii|
|WaterlilyTile::mayPlaceOn|No|(int)|IDK|_ZN13WaterlilyTile10mayPlaceOnEi|
|WaterlilyTile::getCarriedTexture|No|(signed char, int)|IDK|_ZN13WaterlilyTile17getCarriedTextureEai|
|OptionsScreen::renderGameBehind|No|()|IDK|_ZN13OptionsScreen16renderGameBehindEv|
|OptionsScreen::removed|No|()|IDK|_ZN13OptionsScreen7removedEv|
|OptionsScreen::setTextboxText|No|(std::string const&)|IDK|_ZN13OptionsScreen14setTextboxTextERKSs|
|ProgressScreen::renderGameBehind|No|()|IDK|_ZN14ProgressScreen16renderGameBehindEv|
|DisconnectionScreen::isInGameScreen|No|()|IDK|_ZN19DisconnectionScreen14isInGameScreenEv|
|ProgressScreen::setupPositions|No|()|IDK|_ZN14ProgressScreen14setupPositionsEv|
|ProgressScreen::isInGameScreen|No|()|IDK|_ZN14ProgressScreen14isInGameScreenEv|
|ProgressScreen::feedMCOEvent|No|(MCOEvent)|IDK|_ZN14ProgressScreen12feedMCOEventE8MCOEvent|
|Zombie::getBaseSpeed|No|()|IDK|_ZN6Zombie12getBaseSpeedEv|
|Zombie::getMaxHealth|No|()|IDK|_ZN6Zombie12getMaxHealthEv|
|Zombie::getEntityTypeId|No|() const|IDK|_ZNK6Zombie15getEntityTypeIdEv|
|Zombie::getAmbientSound|No|()|IDK|_ZN6Zombie15getAmbientSoundEv|
|Zombie::getDeathLoot|No|()|IDK|_ZN6Zombie12getDeathLootEv|
|Zombie::useNewAi|No|()|IDK|_ZN6Zombie8useNewAiEv|
|Chicken::getBaseSpeed|No|()|IDK|_ZN7Chicken12getBaseSpeedEv|
|Chicken::getEntityTypeId|No|() const|IDK|_ZNK7Chicken15getEntityTypeIdEv|
|Chicken::getMaxHealth|No|()|IDK|_ZN7Chicken12getMaxHealthEv|
|Chicken::causeFallDamage|No|(float)|IDK|_ZN7Chicken15causeFallDamageEf|
|Chicken::getAmbientSound|No|()|IDK|_ZN7Chicken15getAmbientSoundEv|
|Chicken::useNewAi|No|()|IDK|_ZN7Chicken8useNewAiEv|
|Chicken::isFood|No|(ItemInstance const*) const|IDK|_ZNK7Chicken6isFoodEPK12ItemInstance|
|NetworkChunkSource::getStoredChunks|No|() const|IDK|_ZNK18NetworkChunkSource15getStoredChunksEv|
|DiggerItem::getDestroySpeed|No|(ItemInstance*, Tile*)|IDK|_ZN10DiggerItem15getDestroySpeedEP12ItemInstanceP4Tile|
|DiggerItem::getAttackDamage|No|(Entity*)|IDK|_ZN10DiggerItem15getAttackDamageEP6Entity|
|DiggerItem::isHandEquipped|No|() const|IDK|_ZNK10DiggerItem14isHandEquippedEv|
|HatchetItem::getDestroySpeed|No|(ItemInstance*, Tile*)|IDK|_ZN11HatchetItem15getDestroySpeedEP12ItemInstanceP4Tile|
|Model::render|No|(Entity*, float, float, float, float, float, float)|IDK|_ZN5Model6renderEP6Entityffffff|
|Model::setupAnim|No|(float, float, float, float, float, float)|IDK|_ZN5Model9setupAnimEffffff|
|Model::prepareMobModel|No|(Mob*, float, float, float)|IDK|_ZN5Model15prepareMobModelEP3Mobfff|
|MesaBiome::getTreeFeature|No|(Random*)|IDK|_ZN9MesaBiome14getTreeFeatureEP6Random|
|MesaBiome::getFoliageColor|No|()|IDK|_ZN9MesaBiome15getFoliageColorEv|
|MesaBiome::getGrassColor|No|(TilePos const&)|IDK|_ZN9MesaBiome13getGrassColorERK7TilePos|
|PumpkinTile::getPlacementDataValue|No|(Mob*, int, int, int, signed char, float, float, float, int)|IDK|_ZN11PumpkinTile21getPlacementDataValueEP3Mobiiiafffi|
|PumpkinTile::onPlace|No|(TileSource*, int, int, int)|IDK|_ZN11PumpkinTile7onPlaceEP10TileSourceiii|
|GameMode::~GameMode|No|()|IDK|_ZN8GameModeD2Ev|
|vtable for GameMode|No|(undefined|IDK|_ZTV8GameMode|
|GameMode::~GameMode|No|()|IDK|_ZN8GameModeD1Ev|
|GameMode::initLevel|No|(Level*)|IDK|_ZN8GameMode9initLevelEP5Level|
|GameMode::stopDestroyBlock|No|(Player*)|IDK|_ZN8GameMode16stopDestroyBlockEP6Player|
|GameMode::adjustPlayer|No|(Player&)|IDK|_ZN8GameMode12adjustPlayerER6Player|
|GameMode::canHurtPlayer|No|()|IDK|_ZN8GameMode13canHurtPlayerEv|
|GameMode::isCreativeType|No|()|IDK|_ZN8GameMode14isCreativeTypeEv|
|GameMode::isSurvivalType|No|()|IDK|_ZN8GameMode14isSurvivalTypeEv|
|GameMode::initAbilities|No|(Abilities&)|IDK|_ZN8GameMode13initAbilitiesER9Abilities|
|SurvivalMode::canHurtPlayer|No|()|IDK|_ZN12SurvivalMode13canHurtPlayerEv|
|SurvivalMode::isSurvivalType|No|()|IDK|_ZN12SurvivalMode14isSurvivalTypeEv|
|SurvivalMode::stopDestroyBlock|No|(Player*)|IDK|_ZN12SurvivalMode16stopDestroyBlockEP6Player|
|SurvivalMode::initAbilities|No|(Abilities&)|IDK|_ZN12SurvivalMode13initAbilitiesER9Abilities|
|Cow::getBaseSpeed|No|()|IDK|_ZN3Cow12getBaseSpeedEv|
|Cow::getEntityTypeId|No|() const|IDK|_ZNK3Cow15getEntityTypeIdEv|
|Cow::getMaxHealth|No|()|IDK|_ZN3Cow12getMaxHealthEv|
|Cow::getAmbientSound|No|()|IDK|_ZN3Cow15getAmbientSoundEv|
|Cow::getSoundVolume|No|()|IDK|_ZN3Cow14getSoundVolumeEv|
|Cow::getDeathLoot|No|()|IDK|_ZN3Cow12getDeathLootEv|
|Item::leather|No|(undefined|IDK|_ZN4Item7leatherE|
|Cow::useNewAi|No|()|IDK|_ZN3Cow8useNewAiEv|
|MushroomCow::getEntityTypeId|No|() const|IDK|_ZNK11MushroomCow15getEntityTypeIdEv|
|WoolCarpetTile::getTexture|No|(signed char, int)|IDK|_ZN14WoolCarpetTile10getTextureEai|
|WoolCarpetTile::neighborChanged|No|(TileSource*, int, int, int, int, int, int)|IDK|_ZN14WoolCarpetTile15neighborChangedEP10TileSourceiiiiii|
|WoolCarpetTile::getSpawnResourcesAuxValue|No|(int)|IDK|_ZN14WoolCarpetTile25getSpawnResourcesAuxValueEi|
|LargeImageButton::setupDefault|No|()|IDK|_ZN16LargeImageButton12setupDefaultEv|
|StoneSlabTile::getTexture|No|(signed char, int)|IDK|_ZN13StoneSlabTile10getTextureEai|
|StoneSlabTile::getTexture|No|(signed char)|IDK|_ZN13StoneSlabTile10getTextureEa|
|StoneSlabTile::getResource|No|(int, Random*)|IDK|_ZN13StoneSlabTile11getResourceEiP6Random|
|StoneSlabTile::getSpawnResourcesAuxValue|No|(int)|IDK|_ZN13StoneSlabTile25getSpawnResourcesAuxValueEi|
|FenceGateTile::getPlacementDataValue|No|(Mob*, int, int, int, signed char, float, float, float, int)|IDK|_ZN13FenceGateTile21getPlacementDataValueEP3Mobiiiafffi|
|RolledSelectionListH::renderHeader|No|(int, int, Tesselator&)|IDK|_ZN20RolledSelectionListH12renderHeaderEiiR10Tesselator|
|RolledSelectionListH::renderDecorations|No|(int, int)|IDK|_ZN20RolledSelectionListH17renderDecorationsEii|
|RolledSelectionListH::clickedHeader|No|(int, int)|IDK|_ZN20RolledSelectionListH13clickedHeaderEii|
|Touch::TouchWorldSelectionList::renderBackground|No|()|IDK|_ZN5Touch23TouchWorldSelectionList16renderBackgroundEv|
|Touch::TouchWorldSelectionList::touched|No|()|IDK|_ZN5Touch23TouchWorldSelectionList7touchedEv|
|Touch::TouchWorldSelectionList::getNumberOfItems|No|()|IDK|_ZN5Touch23TouchWorldSelectionList16getNumberOfItemsEv|
|Touch::TouchWorldSelectionList::isSelectedItem|No|(int)|IDK|_ZN5Touch23TouchWorldSelectionList14isSelectedItemEi|
|Touch::TouchWorldSelectionList::selectStart|No|(int, int, int)|IDK|_ZN5Touch23TouchWorldSelectionList11selectStartEiii|
|Touch::TouchWorldSelectionList::selectCancel|No|()|IDK|_ZN5Touch23TouchWorldSelectionList12selectCancelEv|
|Touch::SelectWorldScreen::setupPositions|No|()|IDK|_ZN5Touch17SelectWorldScreen14setupPositionsEv|
|Touch::SelectWorldScreen::isIndexValid|No|(int)|IDK|_ZN5Touch17SelectWorldScreen12isIndexValidEi|
|Touch::SelectWorldScreen::tick|No|()|IDK|_ZN5Touch17SelectWorldScreen4tickEv|
|Touch::SelectWorldScreen::isInGameScreen|No|()|IDK|_ZN5Touch17SelectWorldScreen14isInGameScreenEv|
|BaseContainerScreen::closeOnPlayerHurt|No|()|IDK|_ZN19BaseContainerScreen17closeOnPlayerHurtEv|
|ContainerSetSlotPacket::handle|No|(RakNet::RakNetGUID const&, NetEventCallback*)|IDK|_ZN22ContainerSetSlotPacket6handleERKN6RakNet10RakNetGUIDEP16NetEventCallback|
|ChestMenu::tileEntityDestroyedIsInvalid|No|(int)|IDK|_ZN9ChestMenu28tileEntityDestroyedIsInvalidEi|
|ChestScreen::shouldSendAllKeyStates|No|()|IDK|_ZN11ChestScreen22shouldSendAllKeyStatesEv|
|ChestScreen::onInternetUpdate|No|()|IDK|_ZN11ChestScreen16onInternetUpdateEv|
|ChestScreen::isAllowed|No|(int)|IDK|_ZN11ChestScreen9isAllowedEi|
|non-virtual thunk to ChestScreen::isAllowed|No|(int)|IDK|_ZThn136_N11ChestScreen9isAllowedEi|
|ChestScreen::renderGameBehind|No|()|IDK|_ZN11ChestScreen16renderGameBehindEv|
|UseItemPacket::handle|No|(RakNet::RakNetGUID const&, NetEventCallback*)|IDK|_ZN13UseItemPacket6handleERKN6RakNet10RakNetGUIDEP16NetEventCallback|
|PlayerActionPacket::handle|No|(RakNet::RakNetGUID const&, NetEventCallback*)|IDK|_ZN18PlayerActionPacket6handleERKN6RakNet10RakNetGUIDEP16NetEventCallback|
|RemoveBlockPacket::handle|No|(RakNet::RakNetGUID const&, NetEventCallback*)|IDK|_ZN17RemoveBlockPacket6handleERKN6RakNet10RakNetGUIDEP16NetEventCallback|
|GameMode::startDestroyBlock|No|(Player*, int, int, int, signed char)|IDK|_ZN8GameMode17startDestroyBlockEP6Playeriiia|
|GameMode::handleInventoryMouseClick|No|(int, int, int, Player*)|IDK|_ZN8GameMode25handleInventoryMouseClickEiiiP6Player|
|GameMode::handleCloseInventory|No|(int, Player*)|IDK|_ZN8GameMode20handleCloseInventoryEiP6Player|
|GameMode::getPickRange|No|()|IDK|_ZN8GameMode12getPickRangeEv|
|GameMode::initPlayer|No|(Player*)|IDK|_ZN8GameMode10initPlayerEP6Player|
|GameMode::tick|No|()|IDK|_ZN8GameMode4tickEv|
|FlatLayer::fillArea|No|(LayerData&, int, int, int, int)|IDK|_ZN9FlatLayer8fillAreaER9LayerDataiiii|
|TreeFeature::~TreeFeature|No|()|IDK|_ZN11TreeFeatureD2Ev|
|TreeFeature::~TreeFeature|No|()|IDK|_ZN11TreeFeatureD1Ev|
|NewLeafTile::getTexture|No|(signed char, int)|IDK|_ZN11NewLeafTile10getTextureEai|
|NewLeafTile::getCarriedTexture|No|(signed char, int)|IDK|_ZN11NewLeafTile17getCarriedTextureEai|
|NewLeafTile::getSpawnResourcesAuxValue|No|(int)|IDK|_ZN11NewLeafTile25getSpawnResourcesAuxValueEi|
|ControllerMoveInput::~ControllerMoveInput|No|()|IDK|_ZN19ControllerMoveInputD2Ev|
|ControllerMoveInput::~ControllerMoveInput|No|()|IDK|_ZN19ControllerMoveInputD1Ev|
|Label::setWidth|No|(int)|IDK|_ZN5Label8setWidthEi|
|Label::setColor|No|(int)|IDK|_ZN5Label8setColorEi|
|RemoveBlockPacket::~RemoveBlockPacket|No|()|IDK|_ZN17RemoveBlockPacketD2Ev|
|RemoveBlockPacket::~RemoveBlockPacket|No|()|IDK|_ZN17RemoveBlockPacketD1Ev|
|PlayerActionPacket::~PlayerActionPacket|No|()|IDK|_ZN18PlayerActionPacketD2Ev|
|PlayerActionPacket::~PlayerActionPacket|No|()|IDK|_ZN18PlayerActionPacketD1Ev|
|UseItemPacket::~UseItemPacket|No|()|IDK|_ZN13UseItemPacketD2Ev|
|UseItemPacket::~UseItemPacket|No|()|IDK|_ZN13UseItemPacketD1Ev|
|ContainerSetSlotPacket::~ContainerSetSlotPacket|No|()|IDK|_ZN22ContainerSetSlotPacketD2Ev|
|ContainerSetSlotPacket::~ContainerSetSlotPacket|No|()|IDK|_ZN22ContainerSetSlotPacketD1Ev|
|SurvivalMode::~SurvivalMode|No|()|IDK|_ZN12SurvivalModeD2Ev|
|SurvivalMode::~SurvivalMode|No|()|IDK|_ZN12SurvivalModeD1Ev|
|RestrictSunGoal::~RestrictSunGoal|No|()|IDK|_ZN15RestrictSunGoalD2Ev|
|RestrictSunGoal::~RestrictSunGoal|No|()|IDK|_ZN15RestrictSunGoalD1Ev|
|TempEPtr<Mob>::invalidate|No|()|IDK|_ZN8TempEPtrI3MobE10invalidateEv|
|SpawnData::~SpawnData|No|()|IDK|_ZN9SpawnDataD0Ev|
|GameMode::~GameMode|No|()|IDK|_ZN8GameModeD0Ev|
|TreeFeature::~TreeFeature|No|()|IDK|_ZN11TreeFeatureD0Ev|
|ControllerMoveInput::~ControllerMoveInput|No|()|IDK|_ZN19ControllerMoveInputD0Ev|
|RemoveBlockPacket::~RemoveBlockPacket|No|()|IDK|_ZN17RemoveBlockPacketD0Ev|
|PlayerActionPacket::~PlayerActionPacket|No|()|IDK|_ZN18PlayerActionPacketD0Ev|
|UseItemPacket::~UseItemPacket|No|()|IDK|_ZN13UseItemPacketD0Ev|
|ContainerSetSlotPacket::~ContainerSetSlotPacket|No|()|IDK|_ZN22ContainerSetSlotPacketD0Ev|
|SurvivalMode::~SurvivalMode|No|()|IDK|_ZN12SurvivalModeD0Ev|
|RestrictSunGoal::~RestrictSunGoal|No|()|IDK|_ZN15RestrictSunGoalD0Ev|
|Label::getText|No|() const|IDK|_ZNK5Label7getTextEv|
|ShortTag::equals|No|(Tag const&) const|IDK|_ZNK8ShortTag6equalsERK3Tag|
|FloatTag::equals|No|(Tag const&) const|IDK|_ZNK8FloatTag6equalsERK3Tag|
|TextBox::setTextboxText|No|(std::string const&)|IDK|_ZN7TextBox14setTextboxTextERKSs|
|Label::setText|No|(std::string)|IDK|_ZN5Label7setTextESs|
|AppPlatform::getDateString|No|(int)|IDK|_ZN11AppPlatform13getDateStringEi|
|AppPlatform::getPlatformStringVar|No|(int)|IDK|_ZN11AppPlatform20getPlatformStringVarEi|
|Zombie::getHurtSound|No|()|IDK|_ZN6Zombie12getHurtSoundEv|
|Zombie::getDeathSound|No|()|IDK|_ZN6Zombie13getDeathSoundEv|
|Chicken::getHurtSound|No|()|IDK|_ZN7Chicken12getHurtSoundEv|
|Chicken::getDeathSound|No|()|IDK|_ZN7Chicken13getDeathSoundEv|
|Cow::getHurtSound|No|()|IDK|_ZN3Cow12getHurtSoundEv|
|Cow::getDeathSound|No|()|IDK|_ZN3Cow13getDeathSoundEv|
|WoolCarpetTile::shouldRenderFace|No|(TileSource*, int, int, int, signed char, AABB const&)|IDK|_ZN14WoolCarpetTile16shouldRenderFaceEP10TileSourceiiiaRK4AABB|
|WaterlilyTile::getAABB|No|(TileSource*, int, int, int, AABB&, int, bool, int)|IDK|_ZN13WaterlilyTile7getAABBEP10TileSourceiiiR4AABBibi|
|Level::playSound|No|(Entity*, std::string const&, float, float)|IDK|_ZN5Level9playSoundEP6EntityRKSsff|
|AppPlatform::loadTGA|No|(ImageData&, std::string const&)|IDK|_ZN11AppPlatform7loadTGAER9ImageDataRKSs|
|SynchedEntityData::~SynchedEntityData|No|()|IDK|_ZN17SynchedEntityDataD1Ev|
|vtable for Entity|No|(undefined|IDK|_ZTV6Entity|
|Entity::~Entity|No|()|IDK|_ZN6EntityD1Ev|
|Entity::~Entity|No|()|IDK|_ZN6EntityD0Ev|
|Particle::~Particle|No|()|IDK|_ZN8ParticleD2Ev|
|Particle::~Particle|No|()|IDK|_ZN8ParticleD1Ev|
|Particle::~Particle|No|()|IDK|_ZN8ParticleD0Ev|
|Arrow::~Arrow|No|()|IDK|_ZN5ArrowD2Ev|
|vtable for Arrow|No|(undefined|IDK|_ZTV5Arrow|
|Arrow::~Arrow|No|()|IDK|_ZN5ArrowD1Ev|
|Arrow::~Arrow|No|()|IDK|_ZN5ArrowD0Ev|
|AABB::cloneMove|No|(Vec3 const&) const|IDK|_ZNK4AABB9cloneMoveERK4Vec3|
|SurvivalMode::startDestroyBlock|No|(Player*, int, int, int, signed char)|IDK|_ZN12SurvivalMode17startDestroyBlockEP6Playeriiia|
|StairTile::getAABB|No|(TileSource*, int, int, int, AABB&, int, bool, int)|IDK|_ZN9StairTile7getAABBEP10TileSourceiiiR4AABBibi|
|AABB::getSize|No|() const|IDK|_ZNK4AABB7getSizeEv|
|AABB::flooredCopy|No|(float, float) const|IDK|_ZNK4AABB11flooredCopyEff|
|UnderworldFeature::addFeature|No|(LevelChunk&, BiomeSource*, Random&, int, int)|IDK|_ZN17UnderworldFeature10addFeatureER10LevelChunkP11BiomeSourceR6Randomii|
|PerlinNoise::getValue|No|(Vec3 const&) const|IDK|_ZNK11PerlinNoise8getValueERK4Vec3|
|RestrictSunGoal::canUse|No|()|IDK|_ZN15RestrictSunGoal6canUseEv|
|RestrictSunGoal::start|No|()|IDK|_ZN15RestrictSunGoal5startEv|
|PathNavigation::setAvoidSun|No|(bool)|IDK|_ZN14PathNavigation11setAvoidSunEb|
|RestrictSunGoal::stop|No|()|IDK|_ZN15RestrictSunGoal4stopEv|
|AddSnowLayer::fillArea|No|(LayerData&, int, int, int, int)|IDK|_ZN12AddSnowLayer8fillAreaER9LayerDataiiii|
|RemoveTooMuchOceanLayer::fillArea|No|(LayerData&, int, int, int, int)|IDK|_ZN23RemoveTooMuchOceanLayer8fillAreaER9LayerDataiiii|
|AddMushroomIslandLayer::fillArea|No|(LayerData&, int, int, int, int)|IDK|_ZN22AddMushroomIslandLayer8fillAreaER9LayerDataiiii|
|Biome::mushroomIsland|No|(undefined|IDK|_ZN5Biome14mushroomIslandE|
|OptionsScreen::renderBgFill|No|()|IDK|_ZN13OptionsScreen12renderBgFillEv|
|Slider::setOption|No|(Minecraft*)|IDK|_ZN6Slider9setOptionEP9Minecraft|
|Options::getIntValue|No|(Options::Option const*)|IDK|_ZN7Options11getIntValueEPKNS_6OptionE|
|Options::set|No|(Options::Option const*, int)|IDK|_ZN7Options3setEPKNS_6OptionEi|
|Slider::~Slider|No|()|IDK|_ZN6SliderD2Ev|
|vtable for Slider|No|(undefined|IDK|_ZTV6Slider|
|Slider::~Slider|No|()|IDK|_ZN6SliderD1Ev|
|TextBox::render|No|(Minecraft*, int, int)|IDK|_ZN7TextBox6renderEP9Minecraftii|
|Font::draw|No|(std::string const&, float, float, int, bool)|IDK|_ZN4Font4drawERKSsffib|
|TextBox::tick|No|(Minecraft*)|IDK|_ZN7TextBox4tickEP9Minecraft|
|Options::canModify|No|(Options::Option const*)|IDK|_ZN7Options9canModifyEPKNS_6OptionE|
|StairTile::clip|No|(TileSource*, int, int, int, Vec3 const&, Vec3 const&, bool, int)|IDK|_ZN9StairTile4clipEP10TileSourceiiiRK4Vec3S4_bi|
|HitResult::HitResult|No|(HitResult const&)|IDK|_ZN9HitResultC1ERKS_|
|StairTile::DEAD_SPACES|No|(undefined|IDK|_ZN9StairTile11DEAD_SPACESE|
|DEFAULT_ASSERT_HANDLER|No|(char const*, char const*, char const*, int, char const*, char const*)|IDK|_Z22DEFAULT_ASSERT_HANDLERPKcS0_S0_iS0_S0_|
|SlabTile::isObstructingChests|No|(TileSource*, int, int, int)|IDK|_ZN8SlabTile19isObstructingChestsEP10TileSourceiii|
|SlabTile::isBottomSlab|No|(TileSource*, int, int, int)|IDK|_ZN8SlabTile12isBottomSlabEP10TileSourceiii|
|NewLeafTile::getTypeDescriptionId|No|(int)|IDK|_ZN11NewLeafTile20getTypeDescriptionIdEi|
|BaseContainerScreen::init|No|()|IDK|_ZN19BaseContainerScreen4initEv|
|Screen::init|No|()|IDK|_ZN6Screen4initEv|
|OptionsScreen::tick|No|()|IDK|_ZN13OptionsScreen4tickEv|
|BaseContainerScreen::~BaseContainerScreen|No|()|IDK|_ZN19BaseContainerScreenD2Ev|
|vtable for BaseContainerScreen|No|(undefined|IDK|_ZTV19BaseContainerScreen|
|BaseContainerScreen::~BaseContainerScreen|No|()|IDK|_ZN19BaseContainerScreenD1Ev|
|BaseContainerScreen::~BaseContainerScreen|No|()|IDK|_ZN19BaseContainerScreenD0Ev|
|OptionsScreen::~OptionsScreen|No|()|IDK|_ZN13OptionsScreenD2Ev|
|vtable for OptionsScreen|No|(undefined|IDK|_ZTV13OptionsScreen|
|OptionsScreen::~OptionsScreen|No|()|IDK|_ZN13OptionsScreenD1Ev|
|OptionsScreen::~OptionsScreen|No|()|IDK|_ZN13OptionsScreenD0Ev|
|ProgressScreen::~ProgressScreen|No|()|IDK|_ZN14ProgressScreenD2Ev|
|vtable for ProgressScreen|No|(undefined|IDK|_ZTV14ProgressScreen|
|ProgressScreen::~ProgressScreen|No|()|IDK|_ZN14ProgressScreenD1Ev|
|DownfallMixerLayer::fillArea|No|(LayerData&, int, int, int, int)|IDK|_ZN18DownfallMixerLayer8fillAreaER9LayerDataiiii|
|Biome::getBiome|No|(int, Biome*)|IDK|_ZN5Biome8getBiomeEiPS_|
|Biome::getDownfallInt|No|()|IDK|_ZN5Biome14getDownfallIntEv|
|Biome::DEFAULT|No|(undefined|IDK|_ZN5Biome7DEFAULTE|
|Monster::findAttackTarget|No|()|IDK|_ZN7Monster16findAttackTargetEv|
|Monster::~Monster|No|()|IDK|_ZN7MonsterD2Ev|
|Monster::~Monster|No|()|IDK|_ZN7MonsterD1Ev|
|Monster::~Monster|No|()|IDK|_ZN7MonsterD0Ev|
|Zombie::~Zombie|No|()|IDK|_ZN6ZombieD2Ev|
|Zombie::~Zombie|No|()|IDK|_ZN6ZombieD1Ev|
|Zombie::~Zombie|No|()|IDK|_ZN6ZombieD0Ev|
|Cow::~Cow|No|()|IDK|_ZN3CowD2Ev|
|Cow::~Cow|No|()|IDK|_ZN3CowD1Ev|
|Cow::~Cow|No|()|IDK|_ZN3CowD0Ev|
|MushroomCow::~MushroomCow|No|()|IDK|_ZN11MushroomCowD2Ev|
|MushroomCow::~MushroomCow|No|()|IDK|_ZN11MushroomCowD1Ev|
|MushroomCow::~MushroomCow|No|()|IDK|_ZN11MushroomCowD0Ev|
|Chicken::~Chicken|No|()|IDK|_ZN7ChickenD2Ev|
|Chicken::~Chicken|No|()|IDK|_ZN7ChickenD1Ev|
|Chicken::~Chicken|No|()|IDK|_ZN7ChickenD0Ev|
|Zombie::getArmorValue|No|()|IDK|_ZN6Zombie13getArmorValueEv|
|Zombie::getAttackDamage|No|(Entity*)|IDK|_ZN6Zombie15getAttackDamageEP6Entity|
|ItemInstance::getAttackDamage|No|(Entity*)|IDK|_ZN12ItemInstance15getAttackDamageEP6Entity|
|Cow::normalTick|No|()|IDK|_ZN3Cow10normalTickEv|
|Chicken::readAdditionalSaveData|No|(CompoundTag*)|IDK|_ZN7Chicken22readAdditionalSaveDataEP11CompoundTag|
|Cow::readAdditionalSaveData|No|(CompoundTag*)|IDK|_ZN3Cow22readAdditionalSaveDataEP11CompoundTag|
|Chicken::addAdditionalSaveData|No|(CompoundTag*)|IDK|_ZN7Chicken21addAdditionalSaveDataEP11CompoundTag|
|Cow::addAdditionalSaveData|No|(CompoundTag*)|IDK|_ZN3Cow21addAdditionalSaveDataEP11CompoundTag|
|NetworkChunkSource::onLowMemory|No|()|IDK|_ZN18NetworkChunkSource11onLowMemoryEv|
|FullChunkDataPacket::_cleanupStaticBuffers|No|()|IDK|_ZN19FullChunkDataPacket21_cleanupStaticBuffersEv|
|non-virtual thunk to NetworkChunkSource::onLowMemory|No|()|IDK|_ZThn20_N18NetworkChunkSource11onLowMemoryEv|
|DiggerItem::hurtEnemy|No|(ItemInstance*, Mob*, Mob*)|IDK|_ZN10DiggerItem9hurtEnemyEP12ItemInstanceP3MobS3_|
|ItemInstance::hurtAndBreak|No|(int, Mob*)|IDK|_ZN12ItemInstance12hurtAndBreakEiP3Mob|
|DiggerItem::mineBlock|No|(ItemInstance*, int, int, int, int, Mob*)|IDK|_ZN10DiggerItem9mineBlockEP12ItemInstanceiiiiP3Mob|
|ChestModel::render|No|()|IDK|_ZN10ChestModel6renderEv|
|SignModel::render|No|()|IDK|_ZN9SignModel6renderEv|
|PumpkinTile::mayPlace|No|(TileSource*, int, int, int)|IDK|_ZN11PumpkinTile8mayPlaceEP10TileSourceiii|
|SurvivalMode::continueDestroyBlock|No|(Player*, int, int, int, signed char)|IDK|_ZN12SurvivalMode20continueDestroyBlockEP6Playeriiia|
|SoundEngine::play|No|(std::string const&, float, float, float, float, float)|IDK|_ZN11SoundEngine4playERKSsfffff|
|Cow::canInteractWith|No|(Player*)|IDK|_ZN3Cow15canInteractWithEP6Player|
|MushroomCow::canInteractWith|No|(Player*)|IDK|_ZN11MushroomCow15canInteractWithEP6Player|
|AgableMob::getAge|No|()|IDK|_ZN9AgableMob6getAgeEv|
|WoolCarpetTile::getShape|No|(unsigned char, AABB&, bool)|IDK|_ZN14WoolCarpetTile8getShapeEhR4AABBb|
|vtable for AppPlatformListener|No|(undefined|IDK|_ZTV19AppPlatformListener|
|AppPlatform::_singleton|No|(undefined|IDK|_ZN11AppPlatform10_singletonE|
|AppPlatformListener::~AppPlatformListener|No|()|IDK|_ZN19AppPlatformListenerD1Ev|
|AppPlatformListener::~AppPlatformListener|No|()|IDK|_ZN19AppPlatformListenerD0Ev|
|FenceGateTile::mayPlace|No|(TileSource*, int, int, int)|IDK|_ZN13FenceGateTile8mayPlaceEP10TileSourceiii|
|Touch::TouchWorldSelectionList::capXPosition|No|()|IDK|_ZN5Touch23TouchWorldSelectionList12capXPositionEv|
|RolledSelectionListH::capXPosition|No|()|IDK|_ZN20RolledSelectionListH12capXPositionEv|
|Touch::SelectWorldScreen::render|No|(int, int, float)|IDK|_ZN5Touch17SelectWorldScreen6renderEiif|
|Mouse::getButtonState|No|(int)|IDK|_ZN5Mouse14getButtonStateEi|
|Touch::TouchDeleteWorldScreen::postResult|No|(bool)|IDK|_ZN5Touch22TouchDeleteWorldScreen10postResultEb|
|Minecraft::getLevelSource|No|()|IDK|_ZN9Minecraft14getLevelSourceEv|
|PlayScreen::PlayScreen|No|(bool)|IDK|_ZN10PlayScreenC1Eb|
|GameMode::createPlayer|No|(Level*)|IDK|_ZN8GameMode12createPlayerEP5Level|
|LocalPlayer::LocalPlayer|No|(Minecraft*, Level*, User*, bool)|IDK|_ZN11LocalPlayerC1EP9MinecraftP5LevelP4Userb|
|GameMode::interact|No|(Player*, Entity*)|IDK|_ZN8GameMode8interactEP6PlayerP6Entity|
|Player::interact|No|(Entity*)|IDK|_ZN6Player8interactEP6Entity|
|GameMode::destroyBlock|No|(Player*, int, int, int, signed char)|IDK|_ZN8GameMode12destroyBlockEP6Playeriiia|
|Minecraft::isOnline|No|()|IDK|_ZN9Minecraft8isOnlineEv|
|vtable for RemoveBlockPacket|No|(undefined|IDK|_ZTV17RemoveBlockPacket|
|SurvivalMode::destroyBlock|No|(Player*, int, int, int, signed char)|IDK|_ZN12SurvivalMode12destroyBlockEP6Playeriiia|
|ItemInstance::mineBlock|No|(int, int, int, int, Mob*)|IDK|_ZN12ItemInstance9mineBlockEiiiiP3Mob|
|FillingContainer::clearSlot|No|(int)|IDK|_ZN16FillingContainer9clearSlotEi|
|GameMode::releaseUsingItem|No|(Player*)|IDK|_ZN8GameMode16releaseUsingItemEP6Player|
|Player::releaseUsingItem|No|()|IDK|_ZN6Player16releaseUsingItemEv|
|vtable for PlayerActionPacket|No|(undefined|IDK|_ZTV18PlayerActionPacket|
|ControllerMoveInput::setKey|No|(int, bool)|IDK|_ZN19ControllerMoveInput6setKeyEib|
|KeyboardInput::setKey|No|(int, bool)|IDK|_ZN13KeyboardInput6setKeyEib|
|ControllerMoveInput::releaseAllKeys|No|()|IDK|_ZN19ControllerMoveInput14releaseAllKeysEv|
|KeyboardInput::releaseAllKeys|No|()|IDK|_ZN13KeyboardInput14releaseAllKeysEv|
|Label::setupPositions|No|()|IDK|_ZN5Label14setupPositionsEv|
|NewLeafTile::~NewLeafTile|No|()|IDK|_ZN11NewLeafTileD2Ev|
|vtable for NewLeafTile|No|(undefined|IDK|_ZTV11NewLeafTile|
|NewLeafTile::~NewLeafTile|No|()|IDK|_ZN11NewLeafTileD1Ev|
|NewLeafTile::~NewLeafTile|No|()|IDK|_ZN11NewLeafTileD0Ev|
|ChestMenu::~ChestMenu|No|()|IDK|_ZN9ChestMenuD2Ev|
|ContainerMenu::~ContainerMenu|No|()|IDK|_ZN13ContainerMenuD2Ev|
|vtable for ChestMenu|No|(undefined|IDK|_ZTV9ChestMenu|
|ChestMenu::~ChestMenu|No|()|IDK|_ZN9ChestMenuD1Ev|
|ChestMenu::~ChestMenu|No|()|IDK|_ZN9ChestMenuD0Ev|
|MushroomIslandBiome::~MushroomIslandBiome|No|()|IDK|_ZN19MushroomIslandBiomeD2Ev|
|vtable for MushroomIslandBiome|No|(undefined|IDK|_ZTV19MushroomIslandBiome|
|MushroomIslandBiome::~MushroomIslandBiome|No|()|IDK|_ZN19MushroomIslandBiomeD1Ev|
|MushroomIslandBiome::~MushroomIslandBiome|No|()|IDK|_ZN19MushroomIslandBiomeD0Ev|
|MutatedBiome::~MutatedBiome|No|()|IDK|_ZN12MutatedBiomeD2Ev|
|vtable for MutatedBiome|No|(undefined|IDK|_ZTV12MutatedBiome|
|MutatedBiome::~MutatedBiome|No|()|IDK|_ZN12MutatedBiomeD1Ev|
|MutatedBiome::~MutatedBiome|No|()|IDK|_ZN12MutatedBiomeD0Ev|
|SignModel::~SignModel|No|()|IDK|_ZN9SignModelD2Ev|
|vtable for SignModel|No|(undefined|IDK|_ZTV9SignModel|
|SignModel::~SignModel|No|()|IDK|_ZN9SignModelD1Ev|
|ChestModel::~ChestModel|No|()|IDK|_ZN10ChestModelD2Ev|
|vtable for ChestModel|No|(undefined|IDK|_ZTV10ChestModel|
|ChestModel::~ChestModel|No|()|IDK|_ZN10ChestModelD1Ev|
|UnderworldFeature::~UnderworldFeature|No|()|IDK|_ZN17UnderworldFeatureD2Ev|
|PerlinNoise::~PerlinNoise|No|()|IDK|_ZN11PerlinNoiseD1Ev|
|LargeFeature::~LargeFeature|No|()|IDK|_ZN12LargeFeatureD2Ev|
|vtable for UnderworldFeature|No|(undefined|IDK|_ZTV17UnderworldFeature|
|UnderworldFeature::~UnderworldFeature|No|()|IDK|_ZN17UnderworldFeatureD1Ev|
|TextBox::setFocus|No|(Minecraft*)|IDK|_ZN7TextBox8setFocusEP9Minecraft|
|TextBox::mouseClicked|No|(Minecraft*, int, int, int)|IDK|_ZN7TextBox12mouseClickedEP9Minecraftiii|
|TextBox::focusuedMouseClicked|No|(Minecraft*, int, int, int)|IDK|_ZN7TextBox20focusuedMouseClickedEP9Minecraftiii|
|OptionsScreen::keyPressed|No|(int)|IDK|_ZN13OptionsScreen10keyPressedEi|
|PumpkinTile::getTexture|No|(signed char, int)|IDK|_ZN11PumpkinTile10getTextureEai|
|ChestScreen::buttonClicked|No|(Button*)|IDK|_ZN11ChestScreen13buttonClickedEP6Button|
|ChestScreen::handleBackEvent|No|(bool)|IDK|_ZN11ChestScreen15handleBackEventEb|
|GameMode::render|No|(float)|IDK|_ZN8GameMode6renderEf|
|WoolCarpetTile::mayPlace|No|(TileSource*, int, int, int)|IDK|_ZN14WoolCarpetTile8mayPlaceEP10TileSourceiii|
|OptionsScreen::mouseClicked|No|(int, int, int)|IDK|_ZN13OptionsScreen12mouseClickedEiii|
|OptionsScreen::mouseReleased|No|(int, int, int)|IDK|_ZN13OptionsScreen13mouseReleasedEiii|
|DisconnectionScreen::buttonClicked|No|(Button*)|IDK|_ZN19DisconnectionScreen13buttonClickedEP6Button|
|Minecraft::leaveGame|No|(bool, bool)|IDK|_ZN9Minecraft9leaveGameEbb|
|Cow::interactWithPlayer|No|(Player*)|IDK|_ZN3Cow18interactWithPlayerEP6Player|
|WoolCarpetTile::canSurvive|No|(TileSource*, int, int, int)|IDK|_ZN14WoolCarpetTile10canSurviveEP10TileSourceiii|
|Touch::TouchWorldSelectionList::getPos|No|(float)|IDK|_ZN5Touch23TouchWorldSelectionList6getPosEf|
|RolledSelectionListH::getPos|No|(float)|IDK|_ZN20RolledSelectionListH6getPosEf|
|Touch::SelectWorldScreen::handleBackEvent|No|(bool)|IDK|_ZN5Touch17SelectWorldScreen15handleBackEventEb|
|Minecraft::cancelLocateMultiplayer|No|()|IDK|_ZN9Minecraft23cancelLocateMultiplayerEv|
|NewLeafTile::dropExtraLoot|No|(TileSource*, int, int, int, int)|IDK|_ZN11NewLeafTile13dropExtraLootEP10TileSourceiiii|
|Item::apple|No|(undefined|IDK|_ZN4Item5appleE|
|Label::render|No|(Minecraft*, int, int)|IDK|_ZN5Label6renderEP9Minecraftii|
|Font::drawWordWrap|No|(std::string const&, float, float, float, int, bool, bool)|IDK|_ZN4Font12drawWordWrapERKSsfffibb|
|Arrow::lerpMotion|No|(float, float, float)|IDK|_ZN5Arrow10lerpMotionEfff|
|WaterlilyTile::canSurvive|No|(TileSource*, int, int, int)|IDK|_ZN13WaterlilyTile10canSurviveEP10TileSourceiii|
|BaseContainerScreen::tick|No|()|IDK|_ZN19BaseContainerScreen4tickEv|
|ChestScreen::keyPressed|No|(int)|IDK|_ZN11ChestScreen10keyPressedEi|
|LargeImageButton::render|No|(Minecraft*, int, int)|IDK|_ZN16LargeImageButton6renderEP9Minecraftii|
|NetworkChunkSource::releaseChunk|No|(LevelChunk&)|IDK|_ZN18NetworkChunkSource12releaseChunkER10LevelChunk|
|GameMode::useItem|No|(Player*, Level*, ItemInstance*)|IDK|_ZN8GameMode7useItemEP6PlayerP5LevelP12ItemInstance|
|ItemInstance::use|No|(Level*, Player*)|IDK|_ZN12ItemInstance3useEP5LevelP6Player|
|vtable for UseItemPacket|No|(undefined|IDK|_ZTV13UseItemPacket|
|GameMode::useItemOn|No|(Player*, Level*, ItemInstance*, int, int, int, signed char, Vec3 const&)|IDK|_ZN8GameMode9useItemOnEP6PlayerP5LevelP12ItemInstanceiiiaRK4Vec3|
|ItemInstance::useOn|No|(Player*, int, int, int, signed char, float, float, float)|IDK|_ZN12ItemInstance5useOnEP6Playeriiiafff|
|ItemInstance::setAuxValue|No|(int)|IDK|_ZN12ItemInstance11setAuxValueEi|
|BaseMobSpawner::~BaseMobSpawner|No|()|IDK|_ZN14BaseMobSpawnerD2Ev|
|vtable for BaseMobSpawner|No|(undefined|IDK|_ZTV14BaseMobSpawner|
|BaseMobSpawner::~BaseMobSpawner|No|()|IDK|_ZN14BaseMobSpawnerD1Ev|
|BaseMobSpawner::~BaseMobSpawner|No|()|IDK|_ZN14BaseMobSpawnerD0Ev|
|Slider::~Slider|No|()|IDK|_ZN6SliderD0Ev|
|SignModel::~SignModel|No|()|IDK|_ZN9SignModelD0Ev|
|UnderworldFeature::~UnderworldFeature|No|()|IDK|_ZN17UnderworldFeatureD0Ev|
|NetworkChunkSource::~NetworkChunkSource|No|()|IDK|_ZN18NetworkChunkSourceD2Ev|
|vtable for NetworkChunkSource|No|(undefined|IDK|_ZTV18NetworkChunkSource|
|NetworkChunkSource::~NetworkChunkSource|No|()|IDK|_ZN18NetworkChunkSourceD1Ev|
|non-virtual thunk to NetworkChunkSource::~NetworkChunkSource|No|()|IDK|_ZThn20_N18NetworkChunkSourceD1Ev|
|NetworkChunkSource::~NetworkChunkSource|No|()|IDK|_ZN18NetworkChunkSourceD0Ev|
|non-virtual thunk to NetworkChunkSource::~NetworkChunkSource|No|()|IDK|_ZThn20_N18NetworkChunkSourceD0Ev|
|ChestModel::~ChestModel|No|()|IDK|_ZN10ChestModelD0Ev|
|TempEPtr<Mob>::~TempEPtr|No|()|IDK|_ZN8TempEPtrI3MobED2Ev|
|vtable for TempEPtr<Mob>|No|(undefined|IDK|_ZTV8TempEPtrI3MobE|
|TempEPtr<Mob>::~TempEPtr|No|()|IDK|_ZN8TempEPtrI3MobED1Ev|
|TempEPtr<Mob>::~TempEPtr|No|()|IDK|_ZN8TempEPtrI3MobED0Ev|
|ProgressScreen::~ProgressScreen|No|()|IDK|_ZN14ProgressScreenD0Ev|
|vtable for MeleeAttackGoal|No|(undefined|IDK|_ZTV15MeleeAttackGoal|
|MeleeAttackGoal::~MeleeAttackGoal|No|()|IDK|_ZN15MeleeAttackGoalD1Ev|
|MeleeAttackGoal::~MeleeAttackGoal|No|()|IDK|_ZN15MeleeAttackGoalD0Ev|
|ContainerSetSlotPacket::read|No|(RakNet::BitStream*)|IDK|_ZN22ContainerSetSlotPacket4readEPN6RakNet9BitStreamE|
|ContainerSetSlotPacket::write|No|(RakNet::BitStream*)|IDK|_ZN22ContainerSetSlotPacket5writeEPN6RakNet9BitStreamE|
|MeleeAttackGoal::getAttackReachSqr|No|()|IDK|_ZN15MeleeAttackGoal17getAttackReachSqrEv|
|FlatLayer::~FlatLayer|No|()|IDK|_ZN9FlatLayerD2Ev|
|FlatLayer::~FlatLayer|No|()|IDK|_ZN9FlatLayerD1Ev|
|RemoveTooMuchOceanLayer::~RemoveTooMuchOceanLayer|No|()|IDK|_ZN23RemoveTooMuchOceanLayerD2Ev|
|RemoveTooMuchOceanLayer::~RemoveTooMuchOceanLayer|No|()|IDK|_ZN23RemoveTooMuchOceanLayerD1Ev|
|AddSnowLayer::~AddSnowLayer|No|()|IDK|_ZN12AddSnowLayerD2Ev|
|AddSnowLayer::~AddSnowLayer|No|()|IDK|_ZN12AddSnowLayerD1Ev|
|AddMushroomIslandLayer::~AddMushroomIslandLayer|No|()|IDK|_ZN22AddMushroomIslandLayerD2Ev|
|AddMushroomIslandLayer::~AddMushroomIslandLayer|No|()|IDK|_ZN22AddMushroomIslandLayerD1Ev|
|FlatLayer::~FlatLayer|No|()|IDK|_ZN9FlatLayerD0Ev|
|AddSnowLayer::~AddSnowLayer|No|()|IDK|_ZN12AddSnowLayerD0Ev|
|RemoveTooMuchOceanLayer::~RemoveTooMuchOceanLayer|No|()|IDK|_ZN23RemoveTooMuchOceanLayerD0Ev|
|AddMushroomIslandLayer::~AddMushroomIslandLayer|No|()|IDK|_ZN22AddMushroomIslandLayerD0Ev|
|RemoveBlockPacket::write|No|(RakNet::BitStream*)|IDK|_ZN17RemoveBlockPacket5writeEPN6RakNet9BitStreamE|
|RemoveBlockPacket::read|No|(RakNet::BitStream*)|IDK|_ZN17RemoveBlockPacket4readEPN6RakNet9BitStreamE|
|DownfallMixerLayer::~DownfallMixerLayer|No|()|IDK|_ZN18DownfallMixerLayerD2Ev|
|vtable for DownfallMixerLayer|No|(undefined|IDK|_ZTV18DownfallMixerLayer|
|DownfallMixerLayer::~DownfallMixerLayer|No|()|IDK|_ZN18DownfallMixerLayerD1Ev|
|ChestScreen::getItems|No|(Touch::InventoryPane const*)|IDK|_ZN11ChestScreen8getItemsEPKN5Touch13InventoryPaneE|
|non-virtual thunk to ChestScreen::getItems|No|(Touch::InventoryPane const*)|IDK|_ZThn136_N11ChestScreen8getItemsEPKN5Touch13InventoryPaneE|
|DownfallMixerLayer::~DownfallMixerLayer|No|()|IDK|_ZN18DownfallMixerLayerD0Ev|
|SoundDesc::~SoundDesc|No|()|IDK|_ZN9SoundDescD2Ev|
|SoundDesc::~SoundDesc|No|()|IDK|_ZN9SoundDescD1Ev|
|PlayerActionPacket::write|No|(RakNet::BitStream*)|IDK|_ZN18PlayerActionPacket5writeEPN6RakNet9BitStreamE|
|ProgressScreen::progressMessages|No|(undefined|IDK|_ZN14ProgressScreen16progressMessagesE|
|FloatTag::~FloatTag|No|()|IDK|_ZN8FloatTagD2Ev|
|FloatTag::~FloatTag|No|()|IDK|_ZN8FloatTagD1Ev|
|ShortTag::~ShortTag|No|()|IDK|_ZN8ShortTagD2Ev|
|ShortTag::~ShortTag|No|()|IDK|_ZN8ShortTagD1Ev|
|HeavyTile::~HeavyTile|No|()|IDK|_ZN9HeavyTileD2Ev|
|HeavyTile::~HeavyTile|No|()|IDK|_ZN9HeavyTileD1Ev|
|FenceGateTile::~FenceGateTile|No|()|IDK|_ZN13FenceGateTileD2Ev|
|FenceGateTile::~FenceGateTile|No|()|IDK|_ZN13FenceGateTileD1Ev|
|WoolCarpetTile::~WoolCarpetTile|No|()|IDK|_ZN14WoolCarpetTileD2Ev|
|WoolCarpetTile::~WoolCarpetTile|No|()|IDK|_ZN14WoolCarpetTileD1Ev|
|StairTile::~StairTile|No|()|IDK|_ZN9StairTileD2Ev|
|StairTile::~StairTile|No|()|IDK|_ZN9StairTileD1Ev|
|LightGemTile::~LightGemTile|No|()|IDK|_ZN12LightGemTileD2Ev|
|LightGemTile::~LightGemTile|No|()|IDK|_ZN12LightGemTileD1Ev|
|PumpkinTile::~PumpkinTile|No|()|IDK|_ZN11PumpkinTileD2Ev|
|PumpkinTile::~PumpkinTile|No|()|IDK|_ZN11PumpkinTileD1Ev|
|StoneSlabTile::~StoneSlabTile|No|()|IDK|_ZN13StoneSlabTileD2Ev|
|StoneSlabTile::~StoneSlabTile|No|()|IDK|_ZN13StoneSlabTileD1Ev|
|WaterlilyTile::~WaterlilyTile|No|()|IDK|_ZN13WaterlilyTileD2Ev|
|WaterlilyTile::~WaterlilyTile|No|()|IDK|_ZN13WaterlilyTileD1Ev|
|Label::~Label|No|()|IDK|_ZN5LabelD2Ev|
|vtable for Label|No|(undefined|IDK|_ZTV5Label|
|Label::~Label|No|()|IDK|_ZN5LabelD1Ev|
|MesaBiome::~MesaBiome|No|()|IDK|_ZN9MesaBiomeD2Ev|
|vtable for MesaBiome|No|(undefined|IDK|_ZTV9MesaBiome|
|MesaBiome::~MesaBiome|No|()|IDK|_ZN9MesaBiomeD1Ev|
|MesaBiome::~MesaBiome|No|()|IDK|_ZN9MesaBiomeD0Ev|
|HeavyTile::~HeavyTile|No|()|IDK|_ZN9HeavyTileD0Ev|
|ShortTag::~ShortTag|No|()|IDK|_ZN8ShortTagD0Ev|
|FloatTag::~FloatTag|No|()|IDK|_ZN8FloatTagD0Ev|
|FenceGateTile::~FenceGateTile|No|()|IDK|_ZN13FenceGateTileD0Ev|
|WoolCarpetTile::~WoolCarpetTile|No|()|IDK|_ZN14WoolCarpetTileD0Ev|
|LightGemTile::~LightGemTile|No|()|IDK|_ZN12LightGemTileD0Ev|
|StairTile::~StairTile|No|()|IDK|_ZN9StairTileD0Ev|
|WaterlilyTile::~WaterlilyTile|No|()|IDK|_ZN13WaterlilyTileD0Ev|
|PumpkinTile::~PumpkinTile|No|()|IDK|_ZN11PumpkinTileD0Ev|
|StoneSlabTile::~StoneSlabTile|No|()|IDK|_ZN13StoneSlabTileD0Ev|
|UseItemPacket::write|No|(RakNet::BitStream*)|IDK|_ZN13UseItemPacket5writeEPN6RakNet9BitStreamE|
|Label::~Label|No|()|IDK|_ZN5LabelD0Ev|
|NetworkChunkSource::getExistingChunk|No|(ChunkPos const&)|IDK|_ZN18NetworkChunkSource16getExistingChunkERK8ChunkPos|
|Touch::TouchDeleteWorldScreen::~TouchDeleteWorldScreen|No|()|IDK|_ZN5Touch22TouchDeleteWorldScreenD2Ev|
|ConfirmScreen::~ConfirmScreen|No|()|IDK|_ZN13ConfirmScreenD2Ev|
|vtable for Touch::TouchDeleteWorldScreen|No|(undefined|IDK|_ZTVN5Touch22TouchDeleteWorldScreenE|
|Touch::TouchDeleteWorldScreen::~TouchDeleteWorldScreen|No|()|IDK|_ZN5Touch22TouchDeleteWorldScreenD1Ev|
|DiggerItem::~DiggerItem|No|()|IDK|_ZN10DiggerItemD2Ev|
|vtable for DiggerItem|No|(undefined|IDK|_ZTV10DiggerItem|
|DiggerItem::~DiggerItem|No|()|IDK|_ZN10DiggerItemD1Ev|
|HatchetItem::~HatchetItem|No|()|IDK|_ZN11HatchetItemD2Ev|
|HatchetItem::~HatchetItem|No|()|IDK|_ZN11HatchetItemD1Ev|
|LargeImageButton::~LargeImageButton|No|()|IDK|_ZN16LargeImageButtonD2Ev|
|LargeImageButton::~LargeImageButton|No|()|IDK|_ZN16LargeImageButtonD1Ev|
|Cow::getInteractText|No|(Player*)|IDK|_ZN3Cow15getInteractTextEP6Player|
|DisconnectionScreen::~DisconnectionScreen|No|()|IDK|_ZN19DisconnectionScreenD2Ev|
|vtable for DisconnectionScreen|No|(undefined|IDK|_ZTV19DisconnectionScreen|
|DisconnectionScreen::~DisconnectionScreen|No|()|IDK|_ZN19DisconnectionScreenD1Ev|
|DiggerItem::~DiggerItem|No|()|IDK|_ZN10DiggerItemD0Ev|
|Touch::TouchDeleteWorldScreen::~TouchDeleteWorldScreen|No|()|IDK|_ZN5Touch22TouchDeleteWorldScreenD0Ev|
|LargeImageButton::~LargeImageButton|No|()|IDK|_ZN16LargeImageButtonD0Ev|
|HatchetItem::~HatchetItem|No|()|IDK|_ZN11HatchetItemD0Ev|
|DisconnectionScreen::~DisconnectionScreen|No|()|IDK|_ZN19DisconnectionScreenD0Ev|
|OptionsScreen::keyboardNewChar|No|(std::string const&, bool)|IDK|_ZN13OptionsScreen15keyboardNewCharERKSsb|
|TextBox::~TextBox|No|()|IDK|_ZN7TextBoxD2Ev|
|vtable for TextBox|No|(undefined|IDK|_ZTV7TextBox|
|TextBox::~TextBox|No|()|IDK|_ZN7TextBoxD1Ev|
|TextBox::~TextBox|No|()|IDK|_ZN7TextBoxD0Ev|
|ShortTag::copy|No|() const|IDK|_ZNK8ShortTag4copyEv|
|vtable for ShortTag|No|(undefined|IDK|_ZTV8ShortTag|
|FloatTag::copy|No|() const|IDK|_ZNK8FloatTag4copyEv|
|vtable for FloatTag|No|(undefined|IDK|_ZTV8FloatTag|
|BeetrootTile::~BeetrootTile|No|()|IDK|_ZN12BeetrootTileD2Ev|
|vtable for BeetrootTile|No|(undefined|IDK|_ZTV12BeetrootTile|
|BeetrootTile::~BeetrootTile|No|()|IDK|_ZN12BeetrootTileD1Ev|
|BeetrootTile::~BeetrootTile|No|()|IDK|_ZN12BeetrootTileD0Ev|
|Touch::TouchWorldSelectionList::~TouchWorldSelectionList|No|()|IDK|_ZN5Touch23TouchWorldSelectionListD2Ev|
|vtable for Touch::TouchWorldSelectionList|No|(undefined|IDK|_ZTVN5Touch23TouchWorldSelectionListE|
|vtable for RolledSelectionListH|No|(undefined|IDK|_ZTV20RolledSelectionListH|
|Touch::TouchWorldSelectionList::~TouchWorldSelectionList|No|()|IDK|_ZN5Touch23TouchWorldSelectionListD1Ev|
|Touch::TouchWorldSelectionList::~TouchWorldSelectionList|No|()|IDK|_ZN5Touch23TouchWorldSelectionListD0Ev|
|TextBox::topRender|No|(Minecraft*, int, int)|IDK|_ZN7TextBox9topRenderEP9Minecraftii|
|ShortTag::toString|No|() const|IDK|_ZNK8ShortTag8toStringEv|
|DisconnectionScreen::render|No|(int, int, float)|IDK|_ZN19DisconnectionScreen6renderEiif|
|FloatTag::toString|No|() const|IDK|_ZNK8FloatTag8toStringEv|
|Slider::render|No|(Minecraft*, int, int)|IDK|_ZN6Slider6renderEP9Minecraftii|
|ChestScreen::~ChestScreen|No|()|IDK|_ZN11ChestScreenD2Ev|
|vtable for ChestScreen|No|(undefined|IDK|_ZTV11ChestScreen|
|ChestScreen::~ChestScreen|No|()|IDK|_ZN11ChestScreenD1Ev|
|non-virtual thunk to ChestScreen::~ChestScreen|No|()|IDK|_ZThn136_N11ChestScreenD1Ev|
|ChestScreen::~ChestScreen|No|()|IDK|_ZN11ChestScreenD0Ev|
|non-virtual thunk to ChestScreen::~ChestScreen|No|()|IDK|_ZThn136_N11ChestScreenD0Ev|
|TextBox::keyboardNewChar|No|(Minecraft*, std::string, bool)|IDK|_ZN7TextBox15keyboardNewCharEP9MinecraftSsb|
|Util::utf8len|No|(std::string const&)|IDK|_ZN4Util7utf8lenERKSs|
|Util::utf8substring|No|(std::string const&, int, int)|IDK|_ZN4Util13utf8substringERKSsii|
|OptionsScreen::render|No|(int, int, float)|IDK|_ZN13OptionsScreen6renderEiif|
|ControllerButtonRenderer::renderJoystick|No|(int, int, std::string const&)|IDK|_ZN24ControllerButtonRenderer14renderJoystickEiiRKSs|
|ControllerButtonRenderer::renderControllerDiagram|No|(int, int)|IDK|_ZN24ControllerButtonRenderer23renderControllerDiagramEii|
|Touch::TouchWorldSelectionList::renderItem|No|(int, int, int, int, Tesselator&)|IDK|_ZN5Touch23TouchWorldSelectionList10renderItemEiiiiR10Tesselator|
|GuiComponent::drawString|No|(Font*, std::string const&, int, int, int)|IDK|_ZN12GuiComponent10drawStringEP4FontRKSsiii|
|LightGemTile::getResourceCount|No|(Random*)|IDK|_ZN12LightGemTile16getResourceCountEP6Random|
|Chicken::dropDeathLoot|No|()|IDK|_ZN7Chicken13dropDeathLootEv|
|Item::feather|No|(undefined|IDK|_ZN4Item7featherE|
|Item::chicken_raw|No|(undefined|IDK|_ZN4Item11chicken_rawE|
|Item::chicken_cooked|No|(undefined|IDK|_ZN4Item14chicken_cookedE|
|MushroomCow::getInteractText|No|(Player*)|IDK|_ZN11MushroomCow15getInteractTextEP6Player|
|TextBox::keyPressed|No|(Minecraft*, int)|IDK|_ZN7TextBox10keyPressedEP9Minecrafti|
|Zombie::die|No|(Entity*)|IDK|_ZN6Zombie3dieEP6Entity|
|Cow::dropDeathLoot|No|()|IDK|_ZN3Cow13dropDeathLootEv|
|Item::beef_cooked|No|(undefined|IDK|_ZN4Item11beef_cookedE|
|BeetrootTile::spawnResources|No|(TileSource*, int, int, int, int, float)|IDK|_ZN12BeetrootTile14spawnResourcesEP10TileSourceiiiif|
|Arrow::playerTouch|No|(Player*)|IDK|_ZN5Arrow11playerTouchEP6Player|
|Item::arrow|No|(undefined|IDK|_ZN4Item5arrowE|
|Level::checkAndHandleWater|No|(AABB const&, Material const*, Entity*)|IDK|_ZN5Level19checkAndHandleWaterERK4AABBPK8MaterialP6Entity|
|Chicken::aiStep|No|()|IDK|_ZN7Chicken6aiStepEv|
|BeetrootTile::spawnItem|No|(TileSource*, int, int, int, ItemInstance const&)|IDK|_ZN12BeetrootTile9spawnItemEP10TileSourceiiiRK12ItemInstance|
|Arrow::_init|No|()|IDK|_ZN5Arrow5_initEv|
|Arrow::shoot|No|(float, float, float, float, float)|IDK|_ZN5Arrow5shootEfffff|
|AppPlatform::AppPlatform|No|()|IDK|_ZN11AppPlatformC2Ev|
|vtable for AppPlatform|No|(undefined|IDK|_ZTV11AppPlatform|
|AppPlatform::TEXTURE_MAX_LEVEL|No|(undefined|IDK|_ZN11AppPlatform17TEXTURE_MAX_LEVELE|
|AppPlatform::ANISOTROPIC_FILTER|No|(undefined|IDK|_ZN11AppPlatform18ANISOTROPIC_FILTERE|
|AppPlatform::ANISOTROPIC_MAX_LEVEL|No|(undefined|IDK|_ZN11AppPlatform21ANISOTROPIC_MAX_LEVELE|
|AppPlatform::AppPlatform|No|()|IDK|_ZN11AppPlatformC1Ev|
|AppPlatform::getPreloadingHTMLLength|No|()|IDK|_ZN11AppPlatform23getPreloadingHTMLLengthEv|
|AppPlatform::preloadingHTML|No|(undefined|IDK|_ZN11AppPlatform14preloadingHTMLE|
|AppPlatform::loadImage|No|(ImageData&, std::string const&, bool)|IDK|_ZN11AppPlatform9loadImageER9ImageDataRKSsb|
|Util::endsWith|No|(std::string const&, std::string const&)|IDK|_ZN4Util8endsWithERKSsS1_|
|AppPlatform::loadTexture|No|(std::string const&, bool)|IDK|_ZN11AppPlatform11loadTextureERKSsb|
|TextureData::TextureData|No|()|IDK|_ZN11TextureDataC1Ev|
|AppPlatform::_fireLowMemory|No|()|IDK|_ZN11AppPlatform14_fireLowMemoryEv|
|AppPlatform::_fireAppSuspended|No|()|IDK|_ZN11AppPlatform17_fireAppSuspendedEv|
|AppPlatform::_fireAppResumed|No|()|IDK|_ZN11AppPlatform15_fireAppResumedEv|
|AppPlatform::_fireAppFocusLost|No|()|IDK|_ZN11AppPlatform17_fireAppFocusLostEv|
|AppPlatform::_fireAppFocusGained|No|()|IDK|_ZN11AppPlatform19_fireAppFocusGainedEv|
|Entity::operator==|No|(Entity&)|IDK|_ZN6EntityeqERS_|
|Entity::distanceTo|No|(float, float, float)|IDK|_ZN6Entity10distanceToEfff|
|Entity::distanceSqrToBlockPosCenter|No|(TilePos const&)|IDK|_ZN6Entity27distanceSqrToBlockPosCenterERK7TilePos|
|Entity::_init|No|()|IDK|_ZN6Entity5_initEv|
|Entity::shouldRender|No|()|IDK|_ZN6Entity12shouldRenderEv|
|Entity::getRandomPointInAABB|No|(Random&)|IDK|_ZN6Entity20getRandomPointInAABBER6Random|
|Entity::setOnFire|No|(int)|IDK|_ZN6Entity9setOnFireEi|
|Level::getSunlightDirection|No|(float)|IDK|_ZN5Level20getSunlightDirectionEf|
|Level::getSkyColor|No|(Entity*, float)|IDK|_ZN5Level11getSkyColorEP6Entityf|
|Level::getSunriseColor|No|(float)|IDK|_ZN5Level15getSunriseColorEf|
|GameMode::attack|No|(Player*, Entity*)|IDK|_ZN8GameMode6attackEP6PlayerP6Entity|
|Player::attack|No|(Entity*)|IDK|_ZN6Player6attackEP6Entity|
|Arrow::normalTick|No|()|IDK|_ZN5Arrow10normalTickEv|
|AABB::contains|No|(Vec3 const&) const|IDK|_ZNK4AABB8containsERK4Vec3|
|AABB::expand|No|(float, float, float)|IDK|_ZN4AABB6expandEfff|
|AABB::clip|No|(Vec3 const&, Vec3 const&) const|IDK|_ZNK4AABB4clipERK4Vec3S2_|
|HitResult::HitResult|No|(Entity*)|IDK|_ZN9HitResultC1EP6Entity|
|Entity::setRegion|No|(TileSource&)|IDK|_ZN6Entity9setRegionER10TileSource|
|UnderworldFeature::UnderworldFeature|No|(long)|IDK|_ZN17UnderworldFeatureC2El|
|LargeFeature::LargeFeature|No|()|IDK|_ZN12LargeFeatureC2Ev|
|PerlinNoise::PerlinNoise|No|(long, int, int)|IDK|_ZN11PerlinNoiseC1Elii|
|UnderworldFeature::UnderworldFeature|No|(long)|IDK|_ZN17UnderworldFeatureC1El|
|PlayerData::loadPlayer|No|(Player*) const|IDK|_ZNK10PlayerData10loadPlayerEP6Player|
|RestrictSunGoal::RestrictSunGoal|No|(PathfinderMob*)|IDK|_ZN15RestrictSunGoalC2EP13PathfinderMob|
|vtable for RestrictSunGoal|No|(undefined|IDK|_ZTV15RestrictSunGoal|
|RestrictSunGoal::RestrictSunGoal|No|(PathfinderMob*)|IDK|_ZN15RestrictSunGoalC1EP13PathfinderMob|
|AddMushroomIslandLayer::AddMushroomIslandLayer|No|(long, std::shared_ptr<Layer>&)|IDK|_ZN22AddMushroomIslandLayerC2ElRSt10shared_ptrI5LayerE|
|vtable for AddMushroomIslandLayer|No|(undefined|IDK|_ZTV22AddMushroomIslandLayer|
|AddMushroomIslandLayer::AddMushroomIslandLayer|No|(long, std::shared_ptr<Layer>&)|IDK|_ZN22AddMushroomIslandLayerC1ElRSt10shared_ptrI5LayerE|
|Controller::feedTrigger|No|(int, float)|IDK|_ZN10Controller11feedTriggerEif|
|Controller::triggerValues|No|(undefined|IDK|_ZN10Controller13triggerValuesE|
|Controller::inReset|No|(undefined|IDK|_ZN10Controller7inResetE|
|Controller::linearTransform|No|(float, float, float, bool)|IDK|_ZN10Controller15linearTransformEfffb|
|Controller::isValidStick|No|(int)|IDK|_ZN10Controller12isValidStickEi|
|Controller::isTouchedValues|No|(undefined|IDK|_ZN10Controller15isTouchedValuesE|
|Controller::feed|No|(int, int, float, float)|IDK|_ZN10Controller4feedEiiff|
|Controller::stickValuesX|No|(undefined|IDK|_ZN10Controller12stickValuesXE|
|Controller::stickValuesY|No|(undefined|IDK|_ZN10Controller12stickValuesYE|
|Controller::getX|No|(int)|IDK|_ZN10Controller4getXEi|
|Controller::getY|No|(int)|IDK|_ZN10Controller4getYEi|
|ControllerMoveInput::tick|No|(Player*)|IDK|_ZN19ControllerMoveInput4tickEP6Player|
|KeyboardInput::tick|No|(Player*)|IDK|_ZN13KeyboardInput4tickEP6Player|
|Controller::getXDirection|No|(int, float)|IDK|_ZN10Controller13getXDirectionEif|
|Controller::getYDirection|No|(int, float)|IDK|_ZN10Controller13getYDirectionEif|
|Controller::getTransformedX|No|(int, float, float, bool)|IDK|_ZN10Controller15getTransformedXEiffb|
|Controller::getTransformedY|No|(int, float, float, bool)|IDK|_ZN10Controller15getTransformedYEiffb|
|Controller::isValidTrigger|No|(int)|IDK|_ZN10Controller14isValidTriggerEi|
|Controller::getPressure|No|(int)|IDK|_ZN10Controller11getPressureEi|
|Controller::reset|No|()|IDK|_ZN10Controller5resetEv|
|Controller::isReset|No|()|IDK|_ZN10Controller7isResetEv|
|vtable for HeavyTile|No|(undefined|IDK|_ZTV9HeavyTile|
|HeavyTile::HeavyTile|No|(int, std::string const&, Material const*)|IDK|_ZN9HeavyTileC1EiRKSsPK8Material|
|HeavyTile::_scheduleCheck|No|(TileSource&, TilePos const&, Tile*, int)|IDK|_ZN9HeavyTile14_scheduleCheckER10TileSourceRK7TilePosP4Tilei|
|TileTickingQueue::add|No|(TileSource*, TilePos const&, int, int)|IDK|_ZN16TileTickingQueue3addEP10TileSourceRK7TilePosii|
|HeavyTile::_scheduleCheckIfSliding|No|(TileSource&, TilePos const&, Tile*)|IDK|_ZN9HeavyTile23_scheduleCheckIfSlidingER10TileSourceRK7TilePosP4Tile|
|HeavyTile::_findBottomSlidingTile|No|(TileSource&, TilePos const&)|IDK|_ZN9HeavyTile22_findBottomSlidingTileER10TileSourceRK7TilePos|
|HeavyTile::_tickTilesAround2D|No|(TileSource&, TilePos const&, Tile*)|IDK|_ZN9HeavyTile18_tickTilesAround2DER10TileSourceRK7TilePosP4Tile|
|HeavyTile::_startFalling|No|(TileSource&, TilePos const&, Tile*)|IDK|_ZN9HeavyTile13_startFallingER10TileSourceRK7TilePosP4Tile|
|HeavyTile::_isFree|No|(TileSource*, TilePos const&)|IDK|_ZN9HeavyTile7_isFreeEP10TileSourceRK7TilePos|
|HeavyTile::_checkSlide|No|(TileSource*, int, int, int)|IDK|_ZN9HeavyTile11_checkSlideEP10TileSourceiii|
|AddSnowLayer::AddSnowLayer|No|(long, std::shared_ptr<Layer>&)|IDK|_ZN12AddSnowLayerC2ElRSt10shared_ptrI5LayerE|
|vtable for AddSnowLayer|No|(undefined|IDK|_ZTV12AddSnowLayer|
|AddSnowLayer::AddSnowLayer|No|(long, std::shared_ptr<Layer>&)|IDK|_ZN12AddSnowLayerC1ElRSt10shared_ptrI5LayerE|
|ImprovedNoise::init|No|(Random&)|IDK|_ZN13ImprovedNoise4initER6Random|
|ImprovedNoise::ImprovedNoise|No|()|IDK|_ZN13ImprovedNoiseC2Ev|
|ImprovedNoise::ImprovedNoise|No|()|IDK|_ZN13ImprovedNoiseC1Ev|
|ImprovedNoise::ImprovedNoise|No|(Random&)|IDK|_ZN13ImprovedNoiseC2ER6Random|
|ImprovedNoise::ImprovedNoise|No|(Random&)|IDK|_ZN13ImprovedNoiseC1ER6Random|
|ImprovedNoise::lerp|No|(float, float, float)|IDK|_ZN13ImprovedNoise4lerpEfff|
|ImprovedNoise::grad2|No|(int, float, float)|IDK|_ZN13ImprovedNoise5grad2Eiff|
|ImprovedNoise::grad|No|(int, float, float, float)|IDK|_ZN13ImprovedNoise4gradEifff|
|ImprovedNoise::noise|No|(float, float, float) const|IDK|_ZNK13ImprovedNoise5noiseEfff|
|ImprovedNoise::getValue|No|(float, float) const|IDK|_ZNK13ImprovedNoise8getValueEff|
|ImprovedNoise::getValue|No|(float, float, float) const|IDK|_ZNK13ImprovedNoise8getValueEfff|
|ImprovedNoise::readArea|No|(float*, float, float, float, int, int, int, float, float, float, float) const|IDK|_ZNK13ImprovedNoise8readAreaEPffffiiiffff|
|ImprovedNoise::hashCode|No|() const|IDK|_ZNK13ImprovedNoise8hashCodeEv|
|Slider::Slider|No|(Minecraft*, Options::Option const*, float, float)|IDK|_ZN6SliderC2EP9MinecraftPKN7Options6OptionEff|
|Slider::Slider|No|(Minecraft*, Options::Option const*, std::vector<int, std::allocator<int> > const&)|IDK|_ZN6SliderC2EP9MinecraftPKN7Options6OptionERKSt6vectorIiSaIiEE|
|Slider::updateStepPercentage|No|()|IDK|_ZN6Slider20updateStepPercentageEv|
|Slider::mouseReleased|No|(Minecraft*, int, int, int)|IDK|_ZN6Slider13mouseReleasedEP9Minecraftiii|
|Slider::processControllerInput|No|(Minecraft*, int)|IDK|_ZN6Slider22processControllerInputEP9Minecrafti|
|Slider::tick|No|(Minecraft*)|IDK|_ZN6Slider4tickEP9Minecraft|
|TextBox::TextBox|No|(Minecraft*, Options::Option const*, std::string const&)|IDK|_ZN7TextBoxC2EP9MinecraftPKN7Options6OptionERKSs|
|Options::getStringValue|No|(Options::Option const*)|IDK|_ZN7Options14getStringValueEPKNS_6OptionE|
|Touch::TButton::TButton|No|(int, int, int, std::string const&, Minecraft*)|IDK|_ZN5Touch7TButtonC1EiiiRKSsP9Minecraft|
|TextBox::TextBox|No|(Minecraft*, std::string const&, int, char const*, int, Screen*, void |IDK|_ZN7TextBoxC2EP9MinecraftRKSsiPKciP6ScreenMS6_FviEi|
|TextBox::TextBox|No|(Minecraft*, std::string const&, int, char const*, int, Screen*, void |IDK|_ZN7TextBoxC1EP9MinecraftRKSsiPKciP6ScreenMS6_FviEi|
|TextBox::updateText|No|(Minecraft*)|IDK|_ZN7TextBox10updateTextEP9Minecraft|
|Options::set|No|(Options::Option const*, std::string)|IDK|_ZN7Options3setEPKNS_6OptionESs|
|TextBox::loseFocus|No|(Minecraft*)|IDK|_ZN7TextBox9loseFocusEP9Minecraft|
|TextBox::focusuedMouseReleased|No|(Minecraft*, int, int, int)|IDK|_ZN7TextBox21focusuedMouseReleasedEP9Minecraftiii|
|TextBox::backPressed|No|(Minecraft*, bool)|IDK|_ZN7TextBox11backPressedEP9Minecraftb|
|TextBox::getText|No|() const|IDK|_ZNK7TextBox7getTextEv|
|TextBox::getKey|No|()|IDK|_ZN7TextBox6getKeyEv|
|TextBox::setText|No|(std::string const&)|IDK|_ZN7TextBox7setTextERKSs|
|LightGemTile::LightGemTile|No|(int, std::string const&, Material const*)|IDK|_ZN12LightGemTileC2EiRKSsPK8Material|
|vtable for LightGemTile|No|(undefined|IDK|_ZTV12LightGemTile|
|StairTile::StairTile|No|(int, Tile*, int)|IDK|_ZN9StairTileC2EiP4Tilei|
|vtable for StairTile|No|(undefined|IDK|_ZTV9StairTile|
|StairTile::setBaseShape|No|(TileSource*, int, int, int, AABB&)|IDK|_ZN9StairTile12setBaseShapeEP10TileSourceiiiR4AABB|
|StairTile::isStairs|No|(int)|IDK|_ZN9StairTile8isStairsEi|
|StairTile::isLockAttached|No|(TileSource*, int, int, int, int)|IDK|_ZN9StairTile14isLockAttachedEP10TileSourceiiii|
|StairTile::setStepShape|No|(TileSource*, int, int, int, AABB&)|IDK|_ZN9StairTile12setStepShapeEP10TileSourceiiiR4AABB|
|StairTile::setInnerPieceShape|No|(TileSource*, int, int, int, AABB&)|IDK|_ZN9StairTile18setInnerPieceShapeEP10TileSourceiiiR4AABB|
|StairTile::addAABBs|No|(TileSource*, int, int, int, AABB const*, std::vector<AABB, std::allocator<AABB> >&)|IDK|_ZN9StairTile8addAABBsEP10TileSourceiiiPK4AABBRSt6vectorIS2_SaIS2_EE|
|SpawnData::SpawnData|No|()|IDK|_ZN9SpawnDataC2Ev|
|SpawnData::SpawnData|No|()|IDK|_ZN9SpawnDataC1Ev|
|SpawnData::SpawnData|No|(int, int)|IDK|_ZN9SpawnDataC2Eii|
|SpawnData::SpawnData|No|(int, int)|IDK|_ZN9SpawnDataC1Eii|
|SpawnData::SpawnData|No|(int, int, CompoundTag*)|IDK|_ZN9SpawnDataC2EiiP11CompoundTag|
|SpawnData::SpawnData|No|(int, int, CompoundTag*)|IDK|_ZN9SpawnDataC1EiiP11CompoundTag|
|BaseMobSpawner::BaseMobSpawner|No|(int)|IDK|_ZN14BaseMobSpawnerC2Ei|
|BaseMobSpawner::BaseMobSpawner|No|(int)|IDK|_ZN14BaseMobSpawnerC1Ei|
|BaseMobSpawner::getNextSpawnData|No|() const|IDK|_ZNK14BaseMobSpawner16getNextSpawnDataEv|
|BaseMobSpawner::getEntityId|No|() const|IDK|_ZNK14BaseMobSpawner11getEntityIdEv|
|BaseMobSpawner::setNextSpawnData|No|(SpawnData*)|IDK|_ZN14BaseMobSpawner16setNextSpawnDataEP9SpawnData|
|BaseMobSpawner::setEntityId|No|(int)|IDK|_ZN14BaseMobSpawner11setEntityIdEi|
|BaseMobSpawner::getLevel|No|()|IDK|_ZN14BaseMobSpawner8getLevelEv|
|BaseMobSpawner::isNearPlayer|No|()|IDK|_ZN14BaseMobSpawner12isNearPlayerEv|
|Level::getNearestPlayer|No|(float, float, float, float)|IDK|_ZN5Level16getNearestPlayerEffff|
|BaseMobSpawner::delay|No|()|IDK|_ZN14BaseMobSpawner5delayEv|
|BaseMobSpawner::loadDataAndAddEntity|No|(Mob*)|IDK|_ZN14BaseMobSpawner20loadDataAndAddEntityEP3Mob|
|BaseMobSpawner::tick|No|()|IDK|_ZN14BaseMobSpawner4tickEv|
|MobFactory::CreateMob|No|(int, TileSource*, Vec3 const&, Vec3*)|IDK|_ZN10MobFactory9CreateMobEiP10TileSourceRK4Vec3PS2_|
|BaseMobSpawner::getDisplayEntity|No|()|IDK|_ZN14BaseMobSpawner16getDisplayEntityEv|
|BaseMobSpawner::onEventTriggered|No|(int)|IDK|_ZN14BaseMobSpawner16onEventTriggeredEi|
|Base64::base64Encode|No|(std::string const&)|IDK|_ZN6Base6412base64EncodeERKSs|
|Base64::b64_table|No|(undefined|IDK|_ZN6Base649b64_tableE|
|Base64::base64Decode|No|(std::string const&)|IDK|_ZN6Base6412base64DecodeERKSs|
|Base64::reverse_table|No|(undefined|IDK|_ZN6Base6413reverse_tableE|
|_setThreadName|No|(std::string const&)|IDK|_Z14_setThreadNameRKSs|
|SET_THREAD_NAME|No|(std::string const&)|IDK|_Z15SET_THREAD_NAMERKSs|
|CraftingFilters::isStonecutterItem|No|(ItemInstance const&)|IDK|_ZN15CraftingFilters17isStonecutterItemERK12ItemInstance|
|WaterlilyTile::WaterlilyTile|No|(int)|IDK|_ZN13WaterlilyTileC2Ei|
|vtable for WaterlilyTile|No|(undefined|IDK|_ZTV13WaterlilyTile|
|RenderChunk::Builder::~Builder|No|()|IDK|_ZN11RenderChunk7BuilderD2Ev|
|RenderChunk::Builder::~Builder|No|()|IDK|_ZN11RenderChunk7BuilderD1Ev|
|RenderChunk::Builder::trim|No|()|IDK|_ZN11RenderChunk7Builder4trimEv|
|Tesselator::trim|No|()|IDK|_ZN10Tesselator4trimEv|
|RenderChunk::loadDataChunk|No|()|IDK|_ZN11RenderChunk13loadDataChunkEv|
|RenderChunk::getDataState|No|(TileSource&)|IDK|_ZN11RenderChunk12getDataStateER10TileSource|
|RenderChunk::render|No|(TerrainLayer)|IDK|_ZN11RenderChunk6renderE12TerrainLayer|
|MeshBuffer::render|No|(int, int) const|IDK|_ZNK10MeshBuffer6renderEii|
|RenderChunk::distanceToSqr|No|(Entity const*) const|IDK|_ZNK11RenderChunk13distanceToSqrEPK6Entity|
|RenderChunk::reset|No|()|IDK|_ZN11RenderChunk5resetEv|
|MeshBuffer::reset|No|()|IDK|_ZN10MeshBuffer5resetEv|
|RenderChunk::setPos|No|(TilePos const&)|IDK|_ZN11RenderChunk6setPosERK7TilePos|
|AABB::AABB|No|(Vec3 const&, float)|IDK|_ZN4AABBC1ERK4Vec3f|
|RenderChunk::RenderChunk|No|(TilePos const&)|IDK|_ZN11RenderChunkC2ERK7TilePos|
|RenderChunk::RenderChunk|No|(TilePos const&)|IDK|_ZN11RenderChunkC1ERK7TilePos|
|RenderChunk::isDirty|No|() const|IDK|_ZNK11RenderChunk7isDirtyEv|
|RenderChunk::updateDistanceFromPlayer|No|(Vec3 const&)|IDK|_ZN11RenderChunk24updateDistanceFromPlayerERK4Vec3|
|RenderChunk::getFacing|No|(int) const|IDK|_ZNK11RenderChunk9getFacingEi|
|RenderChunk::_tryChangeState|No|(RenderChunk::State, RenderChunk::State)|IDK|_ZN11RenderChunk15_tryChangeStateENS_5StateES0_|
|RenderChunk::_changeState|No|(RenderChunk::State, RenderChunk::State)|IDK|_ZN11RenderChunk12_changeStateENS_5StateES0_|
|RenderChunk::endRebuild|No|()|IDK|_ZN11RenderChunk10endRebuildEv|
|ChunkViewSource::clear|No|()|IDK|_ZN15ChunkViewSource5clearEv|
|Tesselator::end|No|(char const*)|IDK|_ZN10Tesselator3endEPKc|
(null)
|Tesselator::setOffset|No|(float, float, float)|IDK|_ZN10Tesselator9setOffsetEfff|
|Tesselator::clear|No|()|IDK|_ZN10Tesselator5clearEv|
|VertexFormat::EMPTY|No|(undefined|IDK|_ZN12VertexFormat5EMPTYE|
|RenderChunk::makeReadyAsEmpty|No|()|IDK|_ZN11RenderChunk16makeReadyAsEmptyEv|
|RenderChunk::startRebuild|No|(std::unique_ptr<RenderChunk::Builder, std::default_delete<RenderChunk::Builder> >&)|IDK|_ZN11RenderChunk12startRebuildERSt10unique_ptrINS_7BuilderESt14default_deleteIS1_EE|
|ChunkViewSource::move|No|(TilePos const&, TilePos const&)|IDK|_ZN15ChunkViewSource4moveERK7TilePosS2_|
|RenderChunk::setDirty|No|()|IDK|_ZN11RenderChunk8setDirtyEv|
|RenderChunk::isPending|No|() const|IDK|_ZNK11RenderChunk9isPendingEv|
|RenderChunk::_checkRestart|No|()|IDK|_ZN11RenderChunk13_checkRestartEv|
|RenderChunk::Builder::_checkLighting|No|(TileSource&, TilePos const&)|IDK|_ZN11RenderChunk7Builder14_checkLightingER10TileSourceRK7TilePos|
|Screen::Screen|No|()|IDK|_ZN6ScreenC2Ev|
|Screen::Screen|No|()|IDK|_ZN6ScreenC1Ev|
|OptionsScreen::OptionsScreen|No|(bool)|IDK|_ZN13OptionsScreenC2Eb|
|OptionsScreen::OptionsScreen|No|(bool)|IDK|_ZN13OptionsScreenC1Eb|
|OptionsScreen::selectCategory|No|(int)|IDK|_ZN13OptionsScreen14selectCategoryEi|
|OptionsScreen::setupPositions|No|()|IDK|_ZN13OptionsScreen14setupPositionsEv|
|OptionsScreen::closeScreen|No|()|IDK|_ZN13OptionsScreen11closeScreenEv|
|Options::save|No|()|IDK|_ZN7Options4saveEv|
|PauseScreen::PauseScreen|No|(bool)|IDK|_ZN11PauseScreenC1Eb|
|OptionsScreen::handleBackEvent|No|(bool)|IDK|_ZN13OptionsScreen15handleBackEventEb|
|OptionsScreen::buttonClicked|No|(Button*)|IDK|_ZN13OptionsScreen13buttonClickedEP6Button|
|DownfallMixerLayer::DownfallMixerLayer|No|(std::shared_ptr<Layer>, std::shared_ptr<Layer>&, int)|IDK|_ZN18DownfallMixerLayerC2ESt10shared_ptrI5LayerERS2_i|
|DownfallMixerLayer::DownfallMixerLayer|No|(std::shared_ptr<Layer>, std::shared_ptr<Layer>&, int)|IDK|_ZN18DownfallMixerLayerC1ESt10shared_ptrI5LayerERS2_i|
|ProgressScreen::_loadingState|No|()|IDK|_ZN14ProgressScreen13_loadingStateEv|
|ProgressScreen::tick|No|()|IDK|_ZN14ProgressScreen4tickEv|
|ProgressScreen::exitScreen|No|()|IDK|_ZN14ProgressScreen10exitScreenEv|
|Touch::StartMenuScreen::StartMenuScreen|No|()|IDK|_ZN5Touch15StartMenuScreenC1Ev|
|BackgroundQueuePool::setMainThreadHasPriority|No|(bool)|IDK|_ZN19BackgroundQueuePool24setMainThreadHasPriorityEb|
|BackgroundQueuePool::instance|No|(undefined|IDK|_ZN19BackgroundQueuePool8instanceE|
|ProgressScreen::handleBackEvent|No|(bool)|IDK|_ZN14ProgressScreen15handleBackEventEb|
|ProgressScreen::buttonClicked|No|(Button*)|IDK|_ZN14ProgressScreen13buttonClickedEP6Button|
|ProgressScreen::getProgressMessage|No|()|IDK|_ZN14ProgressScreen18getProgressMessageEv|
|ProgressScreen::render|No|(int, int, float)|IDK|_ZN14ProgressScreen6renderEiif|
|Font::drawShadow|No|(char const*, float, float, int)|IDK|_ZN4Font10drawShadowEPKcffi|
|LocalPlayer::getPreloadingProgress|No|()|IDK|_ZN11LocalPlayer21getPreloadingProgressEv|
|Chicken::Chicken|No|(TileSource*)|IDK|_ZN7ChickenC2EP10TileSource|
|vtable for Chicken|No|(undefined|IDK|_ZTV7Chicken|
|Chicken::Chicken|No|(TileSource*)|IDK|_ZN7ChickenC1EP10TileSource|
|Chicken::getBreedOffspring|No|(Animal*)|IDK|_ZN7Chicken17getBreedOffspringEP6Animal|
|ChestModel::ChestModel|No|(bool)|IDK|_ZN10ChestModelC2Eb|
|ModelPart::ModelPart|No|(Model*, int, int, int, int)|IDK|_ZN9ModelPartC1EP5Modeliiii|
|ModelPart::setTexSize|No|(int, int)|IDK|_ZN9ModelPart10setTexSizeEii|
|ModelPart::operator=|No|(ModelPart const&)|IDK|_ZN9ModelPartaSERKS_|
|ChestModel::ChestModel|No|(bool)|IDK|_ZN10ChestModelC1Eb|
|SignModel::SignModel|No|()|IDK|_ZN9SignModelC2Ev|
|SignModel::SignModel|No|()|IDK|_ZN9SignModelC1Ev|
|TileEntityRenderDispatcher::setLevel|No|(Level*)|IDK|_ZN26TileEntityRenderDispatcher8setLevelEP5Level|
|TileEntityRenderDispatcher::prepare|No|(Level*, Textures*, Font*, Mob*, float)|IDK|_ZN26TileEntityRenderDispatcher7prepareEP5LevelP8TexturesP4FontP3Mobf|
|TileEntityRenderDispatcher::getFont|No|()|IDK|_ZN26TileEntityRenderDispatcher7getFontEv|
|TileEntityRenderDispatcher::getRenderer|No|(TileEntityRendererId)|IDK|_ZN26TileEntityRenderDispatcher11getRendererE20TileEntityRendererId|
|TileEntityRenderDispatcher::getRenderer|No|(TileEntity&)|IDK|_ZN26TileEntityRenderDispatcher11getRendererER10TileEntity|
|TileEntityRenderDispatcher::render|No|(TileEntity&, float)|IDK|_ZN26TileEntityRenderDispatcher6renderER10TileEntityf|
|TileEntity::distanceToSqr|No|(float, float, float)|IDK|_ZN10TileEntity13distanceToSqrEfff|
|TileEntityRenderDispatcher::off|No|(undefined|IDK|_ZN26TileEntityRenderDispatcher3offE|
|MultiPlayerLevel::ResetInfo::ResetInfo|No|(int, int, int, int, int)|IDK|_ZN16MultiPlayerLevel9ResetInfoC2Eiiiii|
|MultiPlayerLevel::ResetInfo::ResetInfo|No|(int, int, int, int, int)|IDK|_ZN16MultiPlayerLevel9ResetInfoC1Eiiiii|
|MultiPlayerLevel::MultiPlayerLevel|No|(Minecraft&, LevelStorage*, std::string const&, LevelSettings const&)|IDK|_ZN16MultiPlayerLevelC2ER9MinecraftP12LevelStorageRKSsRK13LevelSettings|
|Level::Level|No|(Minecraft&, LevelStorage*, std::string const&, LevelSettings const&, bool)|IDK|_ZN5LevelC2ER9MinecraftP12LevelStorageRKSsRK13LevelSettingsb|
|vtable for MultiPlayerLevel|No|(undefined|IDK|_ZTV16MultiPlayerLevel|
|MultiPlayerLevel::MultiPlayerLevel|No|(Minecraft&, LevelStorage*, std::string const&, LevelSettings const&)|IDK|_ZN16MultiPlayerLevelC1ER9MinecraftP12LevelStorageRKSsRK13LevelSettings|
|MultiPlayerLevel::clearResetRegion|No|(int, int, int, int, int, int)|IDK|_ZN16MultiPlayerLevel16clearResetRegionEiiiiii|
|MultiPlayerLevel::addToTickNextTick|No|(int, int, int, int, int)|IDK|_ZN16MultiPlayerLevel17addToTickNextTickEiiiii|
|MultiPlayerLevel::tickPendingTicks|No|(bool)|IDK|_ZN16MultiPlayerLevel16tickPendingTicksEb|
|MultiPlayerLevel::getEntity|No|(int, bool)|IDK|_ZN16MultiPlayerLevel9getEntityEib|
|MultiPlayerLevel::disconnect|No|()|IDK|_ZN16MultiPlayerLevel10disconnectEv|
|MesaBiome::MesaBiome|No|(int, bool, bool)|IDK|_ZN9MesaBiomeC2Eibb|
|Biome::setNoRain|No|()|IDK|_ZN5Biome9setNoRainEv|
|MesaBiome::MesaBiome|No|(int, bool, bool)|IDK|_ZN9MesaBiomeC1Eibb|
|MesaBiome::createMutatedCopy|No|(int)|IDK|_ZN9MesaBiome17createMutatedCopyEi|
|Biome::mesa|No|(undefined|IDK|_ZN5Biome4mesaE|
|Biome::HEIGHTS_MOUNTAINS|No|(undefined|IDK|_ZN5Biome17HEIGHTS_MOUNTAINSE|
|MesaBiome::generateBands|No|(long)|IDK|_ZN9MesaBiome13generateBandsEl|
|PerlinSimplexNoise::PerlinSimplexNoise|No|(Random&, int)|IDK|_ZN18PerlinSimplexNoiseC1ER6Randomi|
|MesaBiome::refreshBiome|No|(long)|IDK|_ZN9MesaBiome12refreshBiomeEl|
|MesaBiome::getBand|No|(int, int, int)|IDK|_ZN9MesaBiome7getBandEiii|
|MesaBiome::buildSurfaceAt|No|(Random&, LevelChunk&, TilePos const&, float)|IDK|_ZN9MesaBiome14buildSurfaceAtER6RandomR10LevelChunkRK7TilePosf|
|RemoveTooMuchOceanLayer::RemoveTooMuchOceanLayer|No|(long, std::shared_ptr<Layer>&)|IDK|_ZN23RemoveTooMuchOceanLayerC2ElRSt10shared_ptrI5LayerE|
|vtable for RemoveTooMuchOceanLayer|No|(undefined|IDK|_ZTV23RemoveTooMuchOceanLayer|
|RemoveTooMuchOceanLayer::RemoveTooMuchOceanLayer|No|(long, std::shared_ptr<Layer>&)|IDK|_ZN23RemoveTooMuchOceanLayerC1ElRSt10shared_ptrI5LayerE|
|MeleeAttackGoal::_init|No|(float, bool)|IDK|_ZN15MeleeAttackGoal5_initEfb|
|MeleeAttackGoal::MeleeAttackGoal|No|(Mob*, float, bool)|IDK|_ZN15MeleeAttackGoalC1EP3Mobfb|
|Cow::Cow|No|(TileSource*)|IDK|_ZN3CowC2EP10TileSource|
|vtable for Cow|No|(undefined|IDK|_ZTV3Cow|
|Cow::Cow|No|(TileSource*)|IDK|_ZN3CowC1EP10TileSource|
|Cow::getBreedOffspring|No|(Animal*)|IDK|_ZN3Cow17getBreedOffspringEP6Animal|
|MushroomCow::interactWithPlayer|No|(Player*)|IDK|_ZN11MushroomCow18interactWithPlayerEP6Player|
|Item::mushroomStew|No|(undefined|IDK|_ZN4Item12mushroomStewE|
|MushroomCow::MushroomCow|No|(TileSource*)|IDK|_ZN11MushroomCowC2EP10TileSource|
|vtable for MushroomCow|No|(undefined|IDK|_ZTV11MushroomCow|
|MushroomCow::MushroomCow|No|(TileSource*)|IDK|_ZN11MushroomCowC1EP10TileSource|
|MushroomCow::getBreedOffspring|No|(Animal*)|IDK|_ZN11MushroomCow17getBreedOffspringEP6Animal|
|WoolCarpetTile::WoolCarpetTile|No|(int)|IDK|_ZN14WoolCarpetTileC2Ei|
|vtable for WoolCarpetTile|No|(undefined|IDK|_ZTV14WoolCarpetTile|
|WoolCarpetTile::getTileDataForItemAuxValue|No|(int)|IDK|_ZN14WoolCarpetTile26getTileDataForItemAuxValueEi|
|WoolCarpetTile::getItemAuxValueForTileData|No|(int)|IDK|_ZN14WoolCarpetTile26getItemAuxValueForTileDataEi|
|Monster::Monster|No|(TileSource*)|IDK|_ZN7MonsterC1EP10TileSource|
|Zombie::Zombie|No|(TileSource*)|IDK|_ZN6ZombieC2EP10TileSource|
|BreakDoorGoal::BreakDoorGoal|No|(Mob*)|IDK|_ZN13BreakDoorGoalC1EP3Mob|
|vtable for Zombie|No|(undefined|IDK|_ZTV6Zombie|
|Zombie::Zombie|No|(TileSource*)|IDK|_ZN6ZombieC1EP10TileSource|
|Monster::setNightly|No|()|IDK|_ZN7Monster10setNightlyEv|
|AppPlatformListener::AppPlatformListener|No|(bool)|IDK|_ZN19AppPlatformListenerC2Eb|
|AppPlatformListener::AppPlatformListener|No|(bool)|IDK|_ZN19AppPlatformListenerC1Eb|
|AppPlatformListener::initListener|No|(float)|IDK|_ZN19AppPlatformListener12initListenerEf|
|AppPlatformListener::AppPlatformListener|No|()|IDK|_ZN19AppPlatformListenerC1Ev|
|NetworkChunkSource::NetworkChunkSource|No|(Level*)|IDK|_ZN18NetworkChunkSourceC2EP5Level|
|ChunkSource::ChunkSource|No|(Level*, int)|IDK|_ZN11ChunkSourceC2EP5Leveli|
|NetworkChunkSource::instance|No|(undefined|IDK|_ZN18NetworkChunkSource8instanceE|
|NetworkChunkSource::NetworkChunkSource|No|(Level*)|IDK|_ZN18NetworkChunkSourceC1EP5Level|
|LargeImageButton::LargeImageButton|No|(int, std::string const&)|IDK|_ZN16LargeImageButtonC2EiRKSs|
|vtable for LargeImageButton|No|(undefined|IDK|_ZTV16LargeImageButton|
|LargeImageButton::LargeImageButton|No|(int, std::string const&)|IDK|_ZN16LargeImageButtonC1EiRKSs|
|LargeImageButton::LargeImageButton|No|(int, std::string const&, ImageDef&)|IDK|_ZN16LargeImageButtonC2EiRKSsR8ImageDef|
|LargeImageButton::LargeImageButton|No|(int, std::string const&, ImageDef&)|IDK|_ZN16LargeImageButtonC1EiRKSsR8ImageDef|
|StoneSlabTile::StoneSlabTile|No|(int, bool)|IDK|_ZN13StoneSlabTileC2Eib|
|SlabTile::SlabTile|No|(int, std::string const&, bool, Material const*)|IDK|_ZN8SlabTileC2EiRKSsbPK8Material|
|vtable for StoneSlabTile|No|(undefined|IDK|_ZTV13StoneSlabTile|
|TileRenderer::TileRenderer|No|(Tesselator&, TileSource*)|IDK|_ZN12TileRendererC2ER10TesselatorP10TileSource|
|RenderChunk::Builder::Builder|No|(ChunkSource*, Tesselator*, MemoryTracker*)|IDK|_ZN11RenderChunk7BuilderC2EP11ChunkSourceP10TesselatorP13MemoryTracker|
|ChunkViewSource::ChunkViewSource|No|(ChunkSource*, ChunkSource::LoadMode)|IDK|_ZN15ChunkViewSourceC1EP11ChunkSourceNS0_8LoadModeE|
|Tesselator::Tesselator|No|(MemoryTracker*)|IDK|_ZN10TesselatorC1EP13MemoryTracker|
|RenderChunk::Builder::Builder|No|(ChunkSource*, Tesselator*, MemoryTracker*)|IDK|_ZN11RenderChunk7BuilderC1EP11ChunkSourceP10TesselatorP13MemoryTracker|
|TileRenderer::_shouldRenderFace|No|(Tile*, int, int, int, signed char)|IDK|_ZN12TileRenderer17_shouldRenderFaceEP4Tileiiia|
|TileRenderer::tesselateFireInWorld|No|(Tile*, int, int, int)|IDK|_ZN12TileRenderer20tesselateFireInWorldEP4Tileiii|
|FireTile::canBurn|No|(TileSource*, int, int, int)|IDK|_ZN8FireTile7canBurnEP10TileSourceiii|
|TileRenderer::tesselateTorch|No|(Tile*, float, float, float, float, float)|IDK|_ZN12TileRenderer14tesselateTorchEP4Tilefffff|
|TileRenderer::tesselateCrossTexture|No|(TextureUVCoordinateSet const&, float, float, float, bool)|IDK|_ZN12TileRenderer21tesselateCrossTextureERK22TextureUVCoordinateSetfffb|
|TileRenderer::tesselateCrossTexture|No|(Tile*, unsigned char, float, float, float, bool)|IDK|_ZN12TileRenderer21tesselateCrossTextureEP4Tilehfffb|
|TileRenderer::tesselateCrossPolyTexture|No|(TextureUVCoordinateSet const&, float, float, float, bool)|IDK|_ZN12TileRenderer25tesselateCrossPolyTextureERK22TextureUVCoordinateSetfffb|
|TileTextureTesselator::render|No|(Tesselator&, float, float, float, TextureUVCoordinateSet const&, bool, int, float, Vec3 const&, bool)|IDK|_ZN21TileTextureTesselator6renderER10TesselatorfffRK22TextureUVCoordinateSetbifRK4Vec3b|
|TileRenderer::tesselateStemTexture|No|(Tile*, unsigned char, float, float, float, float)|IDK|_ZN12TileRenderer20tesselateStemTextureEP4Tilehffff|
|TileRenderer::tesselateStemDirTexture|No|(Tile*, unsigned char, int, float, float, float, float)|IDK|_ZN12TileRenderer23tesselateStemDirTextureEP4Tilehiffff|
|TileRenderer::_randomizeFaceDirection|No|(Tile*, signed char, float, float, float)|IDK|_ZN12TileRenderer23_randomizeFaceDirectionEP4Tileafff|
|TileRenderer::renderFaceDown|No|(Tile*, float, float, float, TextureUVCoordinateSet const&)|IDK|_ZN12TileRenderer14renderFaceDownEP4TilefffRK22TextureUVCoordinateSet|
|TileRenderer::renderFaceUp|No|(Tile*, float, float, float, TextureUVCoordinateSet const&)|IDK|_ZN12TileRenderer12renderFaceUpEP4TilefffRK22TextureUVCoordinateSet|
|TileRenderer::renderNorth|No|(Tile*, float, float, float, TextureUVCoordinateSet const&)|IDK|_ZN12TileRenderer11renderNorthEP4TilefffRK22TextureUVCoordinateSet|
|TileRenderer::renderSouth|No|(Tile*, float, float, float, TextureUVCoordinateSet const&)|IDK|_ZN12TileRenderer11renderSouthEP4TilefffRK22TextureUVCoordinateSet|
|TileRenderer::renderWest|No|(Tile*, float, float, float, TextureUVCoordinateSet const&)|IDK|_ZN12TileRenderer10renderWestEP4TilefffRK22TextureUVCoordinateSet|
|TileRenderer::renderEast|No|(Tile*, float, float, float, TextureUVCoordinateSet const&)|IDK|_ZN12TileRenderer10renderEastEP4TilefffRK22TextureUVCoordinateSet|
|TileRenderer::tesselateRowTexture|No|(Tile*, unsigned char, float, float, float)|IDK|_ZN12TileRenderer19tesselateRowTextureEP4Tilehfff|
|TileRenderer::clearTileCache|No|()|IDK|_ZN12TileRenderer14clearTileCacheEv|
|TileRenderer::getBrightness|No|(int, int, int)|IDK|_ZN12TileRenderer13getBrightnessEiii|
|TileRenderer::tesselateLilypadInWorld|No|(Tile*, int, int, int)|IDK|_ZN12TileRenderer23tesselateLilypadInWorldEP4Tileiii|
|TileRenderer::_occlusion|No|(int, int, int)|IDK|_ZN12TileRenderer10_occlusionEiii|
|TileRenderer::getTexture|No|(Tile*, int, int, int, signed char) const|IDK|_ZNK12TileRenderer10getTextureEP4Tileiiia|
|TileRenderer::tesselateBlockInWorld|No|(Tile*, int, int, int, float, float, float)|IDK|_ZN12TileRenderer21tesselateBlockInWorldEP4Tileiiifff|
|TileRenderer::tesselateBlockInWorldWithAmbienceOcclusion|No|(Tile*, int, int, int, float, float, float)|IDK|_ZN12TileRenderer42tesselateBlockInWorldWithAmbienceOcclusionEP4Tileiiifff|
|TileRenderer::tesselateBlockInWorld|No|(Tile*, int, int, int)|IDK|_ZN12TileRenderer21tesselateBlockInWorldEP4Tileiii|
|TileRenderer::tesselateFenceInWorld|No|(FenceTile*, int, int, int)|IDK|_ZN12TileRenderer21tesselateFenceInWorldEP9FenceTileiii|
|FenceTile::connectsTo|No|(TileSource*, int, int, int)|IDK|_ZN9FenceTile10connectsToEP10TileSourceiii|
|TileRenderer::tesselateAirPortalFrameInWorld|No|(EndPortalFrameTile*, int, int, int, unsigned char)|IDK|_ZN12TileRenderer30tesselateAirPortalFrameInWorldEP18EndPortalFrameTileiiih|
|EndPortalFrameTile::getEyeTexture|No|()|IDK|_ZN18EndPortalFrameTile13getEyeTextureEv|
|Tesselator::begin|No|(int, int)|IDK|_ZN10Tesselator5beginEii|
|WallTile::POST_WIDTH|No|(undefined|IDK|_ZN8WallTile10POST_WIDTHE|
|WallTile::POST_HEIGHT|No|(undefined|IDK|_ZN8WallTile11POST_HEIGHTE|
|WallTile::WALL_WIDTH|No|(undefined|IDK|_ZN8WallTile10WALL_WIDTHE|
|WallTile::WALL_HEIGHT|No|(undefined|IDK|_ZN8WallTile11WALL_HEIGHTE|
|TileRenderer::tesselateStairsInWorld|No|(StairTile*, int, int, int)|IDK|_ZN12TileRenderer22tesselateStairsInWorldEP9StairTileiii|
|TileRenderer::tesselateWallInWorld|No|(WallTile*, int, int, int)|IDK|_ZN12TileRenderer20tesselateWallInWorldEP8WallTileiii|
|WallTile::connectsTo|No|(TileSource*, int, int, int)|IDK|_ZN8WallTile10connectsToEP10TileSourceiii|
|TileRenderer::tesselateCactusInWorld|No|(Tile*, int, int, int, float, float, float)|IDK|_ZN12TileRenderer22tesselateCactusInWorldEP4Tileiiifff|
|Tesselator::addOffset|No|(float, float, float)|IDK|_ZN10Tesselator9addOffsetEfff|
|TileRenderer::tesselateCactusInWorld|No|(Tile*, int, int, int)|IDK|_ZN12TileRenderer22tesselateCactusInWorldEP4Tileiii|
|TileRenderer::tesselateDoorInWorld|No|(Tile*, int, int, int)|IDK|_ZN12TileRenderer20tesselateDoorInWorldEP4Tileiii|
|DoorTile::getCompositeData|No|(TileSource*, TilePos const&)|IDK|_ZN8DoorTile16getCompositeDataEP10TileSourceRK7TilePos|
|DoorTile::isUpper|No|(unsigned char)|IDK|_ZN8DoorTile7isUpperEh|
|TileRenderer::getData|No|(int, int, int) const|IDK|_ZNK12TileRenderer7getDataEiii|
|TileRenderer::tesselateTorchInWorld|No|(Tile*, int, int, int)|IDK|_ZN12TileRenderer21tesselateTorchInWorldEP4Tileiii|
|TileRenderer::tesselateLadderInWorld|No|(Tile*, int, int, int)|IDK|_ZN12TileRenderer22tesselateLadderInWorldEP4Tileiii|
|TileRenderer::tesselateCrossInWorld|No|(Tile*, int, int, int, bool)|IDK|_ZN12TileRenderer21tesselateCrossInWorldEP4Tileiiib|
|TileRenderer::tesselateCrossPolyInWorld|No|(Tile*, int, int, int, bool)|IDK|_ZN12TileRenderer25tesselateCrossPolyInWorldEP4Tileiiib|
|TileRenderer::tesselateStemInWorld|No|(Tile*, int, int, int)|IDK|_ZN12TileRenderer20tesselateStemInWorldEP4Tileiii|
|TileRenderer::getWaterHeight|No|(int, int, int, Material const*)|IDK|_ZN12TileRenderer14getWaterHeightEiiiPK8Material|
|TileRenderer::tesselateWaterInWorld|No|(Tile*, int, int, int)|IDK|_ZN12TileRenderer21tesselateWaterInWorldEP4Tileiii|
|TileRenderer::tesselateBedInWorld|No|(Tile*, int, int, int)|IDK|_ZN12TileRenderer19tesselateBedInWorldEP4Tileiii|
|Direction::DIRECTION_FACING|No|(undefined|IDK|_ZN9Direction16DIRECTION_FACINGE|
|TileRenderer::tesselateVineInWorld|No|(Tile*, int, int, int)|IDK|_ZN12TileRenderer20tesselateVineInWorldEP4Tileiii|
|TileRenderer::tesselateRowInWorld|No|(Tile*, int, int, int)|IDK|_ZN12TileRenderer19tesselateRowInWorldEP4Tileiii|
|TileRenderer::tesselateThinFenceInWorld|No|(ThinFenceTile*, int, int, int)|IDK|_ZN12TileRenderer25tesselateThinFenceInWorldEP13ThinFenceTileiii|
|TileRenderer::tesselateTreeInWorld|No|(Tile*, int, int, int)|IDK|_ZN12TileRenderer20tesselateTreeInWorldEP4Tileiii|
|TileRenderer::tesselateRailInWorld|No|(BaseRailTile*, int, int, int)|IDK|_ZN12TileRenderer20tesselateRailInWorldEP12BaseRailTileiii|
|TileRenderer::tesselateCocoaInWorld|No|(CocoaTile*, int, int, int)|IDK|_ZN12TileRenderer21tesselateCocoaInWorldEP9CocoaTileiii|
|CocoaTile::getAge|No|(int)|IDK|_ZN9CocoaTile6getAgeEi|
|CocoaTile::getTextureForAge|No|(int)|IDK|_ZN9CocoaTile16getTextureForAgeEi|
|FenceGateTile::FenceGateTile|No|(int, std::string const&)|IDK|_ZN13FenceGateTileC2EiRKSs|
|vtable for FenceGateTile|No|(undefined|IDK|_ZTV13FenceGateTile|
|FenceGateTile::isOpen|No|(int)|IDK|_ZN13FenceGateTile6isOpenEi|
|FenceGateTile::getAABB|No|(TileSource*, int, int, int, AABB&, int, bool, int)|IDK|_ZN13FenceGateTile7getAABBEP10TileSourceiiiR4AABBibi|
|FenceGateTile::getDirection|No|(int)|IDK|_ZN13FenceGateTile12getDirectionEi|
|TileRenderer::tesselateFenceGateInWorld|No|(FenceGateTile*, int, int, int)|IDK|_ZN12TileRenderer25tesselateFenceGateInWorldEP13FenceGateTileiii|
|FenceGateTile::use|No|(Player*, int, int, int)|IDK|_ZN13FenceGateTile3useEP6Playeriii|
|Touch::TouchWorldSelectionList::TouchWorldSelectionList|No|(Minecraft*, int, int)|IDK|_ZN5Touch23TouchWorldSelectionListC2EP9Minecraftii|
|RolledSelectionListH::RolledSelectionListH|No|(Minecraft*, int, int, int, int, int, int, int)|IDK|_ZN20RolledSelectionListHC2EP9Minecraftiiiiiii|
|Touch::TouchWorldSelectionList::TouchWorldSelectionList|No|(Minecraft*, int, int)|IDK|_ZN5Touch23TouchWorldSelectionListC1EP9Minecraftii|
|Touch::TouchWorldSelectionList::tweenInited|No|()|IDK|_ZN5Touch23TouchWorldSelectionList11tweenInitedEv|
|Touch::TouchWorldSelectionList::stepLeft|No|()|IDK|_ZN5Touch23TouchWorldSelectionList8stepLeftEv|
|Touch::TouchWorldSelectionList::stepRight|No|()|IDK|_ZN5Touch23TouchWorldSelectionList9stepRightEv|
|Touch::SelectWorldScreen::keyPressed|No|(int)|IDK|_ZN5Touch17SelectWorldScreen10keyPressedEi|
|Touch::TouchWorldSelectionList::selectItem|No|(int, bool)|IDK|_ZN5Touch23TouchWorldSelectionList10selectItemEib|
|Touch::TouchWorldSelectionList::tick|No|()|IDK|_ZN5Touch23TouchWorldSelectionList4tickEv|
|RolledSelectionListH::tick|No|()|IDK|_ZN20RolledSelectionListH4tickEv|
|Mouse::isButtonDown|No|(int)|IDK|_ZN5Mouse12isButtonDownEi|
|RolledSelectionListH::getItemAtXPositionRaw|No|(int)|IDK|_ZN20RolledSelectionListH21getItemAtXPositionRawEi|
|Touch::SelectWorldScreen::SelectWorldScreen|No|()|IDK|_ZN5Touch17SelectWorldScreenC2Ev|
|Button::Button|No|(int, std::string const&, bool)|IDK|_ZN6ButtonC1EiRKSsb|
|vtable for Touch::SelectWorldScreen|No|(undefined|IDK|_ZTVN5Touch17SelectWorldScreenE|
|Touch::SelectWorldScreen::SelectWorldScreen|No|()|IDK|_ZN5Touch17SelectWorldScreenC1Ev|
|Touch::TouchDeleteWorldScreen::TouchDeleteWorldScreen|No|(LevelSummary const&)|IDK|_ZN5Touch22TouchDeleteWorldScreenC2ERK12LevelSummary|
|ConfirmScreen::ConfirmScreen|No|(Screen*, std::string const&, std::string const&, std::string const&, std::string const&, int)|IDK|_ZN13ConfirmScreenC2EP6ScreenRKSsS3_S3_S3_i|
|Touch::TouchDeleteWorldScreen::TouchDeleteWorldScreen|No|(LevelSummary const&)|IDK|_ZN5Touch22TouchDeleteWorldScreenC1ERK12LevelSummary|
|Touch::SelectWorldScreen::buttonClicked|No|(Button*)|IDK|_ZN5Touch17SelectWorldScreen13buttonClickedEP6Button|
|TextureAtlasTextureItem::TextureAtlasTextureItem|No|(std::string const&, std::vector<TextureUVCoordinateSet, std::allocator<TextureUVCoordinateSet> > const&)|IDK|_ZN23TextureAtlasTextureItemC2ERKSsRKSt6vectorI22TextureUVCoordinateSetSaIS3_EE|
|TextureAtlasTextureItem::TextureAtlasTextureItem|No|(std::string const&, std::vector<TextureUVCoordinateSet, std::allocator<TextureUVCoordinateSet> > const&)|IDK|_ZN23TextureAtlasTextureItemC1ERKSsRKSt6vectorI22TextureUVCoordinateSetSaIS3_EE|
|TextureAtlasTextureItem::TextureAtlasTextureItem|No|()|IDK|_ZN23TextureAtlasTextureItemC2Ev|
|TextureAtlasTextureItem::getName|No|() const|IDK|_ZNK23TextureAtlasTextureItem7getNameEv|
|BeetrootTile::getTexture|No|(signed char, int)|IDK|_ZN12BeetrootTile10getTextureEai|
|TileRenderer::tesselateDoublePlantInWorld|No|(DoublePlantTile*, int, int, int, bool, bool)|IDK|_ZN12TileRenderer27tesselateDoublePlantInWorldEP15DoublePlantTileiiibb|
|DoublePlantTile::isTop|No|(int)|IDK|_ZN15DoublePlantTile5isTopEi|
|DoublePlantTile::getType|No|(int)|IDK|_ZN15DoublePlantTile7getTypeEi|
|DoublePlantTile::getStemTexture|No|(bool, int)|IDK|_ZN15DoublePlantTile14getStemTextureEbi|
|TileRenderer::tesselateInWorld|No|(Tile*, int, int, int, bool)|IDK|_ZN12TileRenderer16tesselateInWorldEP4Tileiiib|
|TileRenderer::tesselateInWorld|No|(Tile*, int, int, int, TextureUVCoordinateSet const&)|IDK|_ZN12TileRenderer16tesselateInWorldEP4TileiiiRK22TextureUVCoordinateSet|
|TileRenderer::tesselateInWorldNoCulling|No|(Tile*, int, int, int)|IDK|_ZN12TileRenderer25tesselateInWorldNoCullingEP4Tileiii|
|PumpkinTile::PumpkinTile|No|(int, bool)|IDK|_ZN11PumpkinTileC2Eib|
|vtable for PumpkinTile|No|(undefined|IDK|_ZTV11PumpkinTile|
|vtable for TreeFeature|No|(undefined|IDK|_ZTV11TreeFeature|
|TreeFeature::TreeFeature|No|(bool, int, int, int, int, bool)|IDK|_ZN11TreeFeatureC1Ebiiiib|
|TreeFeature::_placeFallenTrunk|No|(TileSource*, int, int, int, Random&, int) const|IDK|_ZNK11TreeFeature17_placeFallenTrunkEP10TileSourceiiiR6Randomi|
|TreeFeature::addVine|No|(TileSource*, int, int, int, int) const|IDK|_ZNK11TreeFeature7addVineEP10TileSourceiiii|
|TreeFeature::place|No|(TileSource*, int, int, int, Random&) const|IDK|_ZNK11TreeFeature5placeEP10TileSourceiiiR6Random|
|ItemDiffer::ItemDiffer|No|(std::vector<ItemInstance const*, std::allocator<ItemInstance const*> > const&)|IDK|_ZN10ItemDifferC2ERKSt6vectorIPK12ItemInstanceSaIS3_EE|
|ItemDiffer::ItemDiffer|No|(std::vector<ItemInstance const*, std::allocator<ItemInstance const*> > const&)|IDK|_ZN10ItemDifferC1ERKSt6vectorIPK12ItemInstanceSaIS3_EE|
|ChestScreen::ChestScreen|No|(Player*, ChestTileEntity*)|IDK|_ZN11ChestScreenC2EP6PlayerP15ChestTileEntity|
|ContainerMenu::ContainerMenu|No|(Container*, int)|IDK|_ZN13ContainerMenuC2EP9Containeri|
|ChestScreen::ChestScreen|No|(Player*, ChestTileEntity*)|IDK|_ZN11ChestScreenC1EP6PlayerP15ChestTileEntity|
|ChestScreen::handleRenderPane|No|(Touch::InventoryPane*, Tesselator&, int, int, float)|IDK|_ZN11ChestScreen16handleRenderPaneEPN5Touch13InventoryPaneER10Tesselatoriif|
|ChestScreen::drawSlotItemAt|No|(Tesselator&, ItemInstance const*, int, int, bool)|IDK|_ZN11ChestScreen14drawSlotItemAtER10TesselatorPK12ItemInstanceiib|
|ItemInstance::isNull|No|() const|IDK|_ZNK12ItemInstance6isNullEv|
|Gui::renderSlotText|No|(ItemInstance const*, float, float, bool, bool, bool)|IDK|_ZN3Gui14renderSlotTextEPK12ItemInstanceffbbb|
|ChestScreen::updateSelectedIndexes|No|(Controller::StickDirection)|IDK|_ZN11ChestScreen21updateSelectedIndexesEN10Controller14StickDirectionE|
|ScrollingPane::getColumns|No|()|IDK|_ZN13ScrollingPane10getColumnsEv|
|ScrollingPane::setRenderSelected|No|(bool)|IDK|_ZN13ScrollingPane17setRenderSelectedEb|
|ScrollingPane::getNumItems|No|()|IDK|_ZN13ScrollingPane11getNumItemsEv|
|ScrollingPane::onNavigate|No|(int)|IDK|_ZN13ScrollingPane10onNavigateEi|
|ScrollingPane::getRows|No|()|IDK|_ZN13ScrollingPane7getRowsEv|
|ChestScreen::controllerDirectionChanged|No|(int, Controller::StickDirection)|IDK|_ZN11ChestScreen26controllerDirectionChangedEiN10Controller14StickDirectionE|
|ChestScreen::controllerDirectionHeld|No|(int, Controller::StickDirection)|IDK|_ZN11ChestScreen23controllerDirectionHeldEiN10Controller14StickDirectionE|
|_mkdir|No|(char const*)|IDK|_Z6_mkdirPKc|
|_access|No|(char const*, int)|IDK|_Z7_accessPKci|
|_errno|No|()|IDK|_Z6_errnov|
|exists|No|(char const*)|IDK|_Z6existsPKc|
|createFolderIfNotExists|No|(char const*)|IDK|_Z23createFolderIfNotExistsPKc|
|getRemainingFileSize|No|(__sFILE*)|IDK|_Z20getRemainingFileSizeP7__sFILE|
|AppPlatform::readAssetFile|No|(std::string const&)|IDK|_ZN11AppPlatform13readAssetFileERKSs|
|Util::EMPTY_STRING|No|(undefined|IDK|_ZN4Util12EMPTY_STRINGE|
|getFileSize|No|(char const*)|IDK|_Z11getFileSizePKc|
|createTree|No|(char const*, char const**, int)|IDK|_Z10createTreePKcPS0_i|
|GameMode::GameMode|No|(Minecraft*)|IDK|_ZN8GameModeC2EP9Minecraft|
|GameMode::GameMode|No|(Minecraft*)|IDK|_ZN8GameModeC1EP9Minecraft|
|SurvivalMode::SurvivalMode|No|(Minecraft*)|IDK|_ZN12SurvivalModeC2EP9Minecraft|
|vtable for SurvivalMode|No|(undefined|IDK|_ZTV12SurvivalMode|
|SurvivalMode::SurvivalMode|No|(Minecraft*)|IDK|_ZN12SurvivalModeC1EP9Minecraft|
|FlatLayer::FlatLayer|No|(int)|IDK|_ZN9FlatLayerC2Ei|
|vtable for FlatLayer|No|(undefined|IDK|_ZTV9FlatLayer|
|FlatLayer::FlatLayer|No|(int)|IDK|_ZN9FlatLayerC1Ei|
|NewLeafTile::NewLeafTile|No|(int, std::string const&)|IDK|_ZN11NewLeafTileC2EiRKSs|
|ChunkPos::ChunkPos|No|(TilePos const&)|IDK|_ZN8ChunkPosC2ERK7TilePos|
|Entity::_updateOwnerChunk|No|()|IDK|_ZN6Entity17_updateOwnerChunkEv|
|SynchedEntityData::SynchedEntityData|No|()|IDK|_ZN17SynchedEntityDataC1Ev|
|Entity::entityCounter|No|(undefined|IDK|_ZN6Entity13entityCounterE|
|Entity::Entity|No|(TileSource*)|IDK|_ZN6EntityC1EP10TileSource|
|Arrow::Arrow|No|(TileSource*)|IDK|_ZN5ArrowC2EP10TileSource|
|Arrow::Arrow|No|(TileSource*)|IDK|_ZN5ArrowC1EP10TileSource|
|Arrow::Arrow|No|(TileSource*, float, float, float)|IDK|_ZN5ArrowC2EP10TileSourcefff|
|Arrow::Arrow|No|(TileSource*, float, float, float)|IDK|_ZN5ArrowC1EP10TileSourcefff|
|Arrow::Arrow|No|(Mob*, float)|IDK|_ZN5ArrowC2EP3Mobf|
|Mth::DEGRAD|No|(undefined|IDK|_ZN3Mth6DEGRADE|
|Arrow::Arrow|No|(Mob*, float)|IDK|_ZN5ArrowC1EP3Mobf|
|Arrow::Arrow|No|(Mob*, Mob*, float, float)|IDK|_ZN5ArrowC2EP3MobS1_ff|
|Arrow::Arrow|No|(Mob*, Mob*, float, float)|IDK|_ZN5ArrowC1EP3MobS1_ff|
|Particle::Particle|No|(TileSource*, ParticleType, std::string const&)|IDK|_ZN8ParticleC1EP10TileSource12ParticleTypeRKSs|
|MultiPlayerLevel::directTickEntities|No|()|IDK|_ZN16MultiPlayerLevel18directTickEntitiesEv|
|ChunkPos::ChunkPos|No|(Vec3 const&)|IDK|_ZN8ChunkPosC2ERK4Vec3|
|ChunkPos::ChunkPos|No|(Vec3 const&)|IDK|_ZN8ChunkPosC1ERK4Vec3|
|ChunkPos::ChunkPos|No|(float, float, float)|IDK|_ZN8ChunkPosC2Efff|
|ChunkPos::ChunkPos|No|(float, float, float)|IDK|_ZN8ChunkPosC1Efff|
|ChunkPos::ChunkPos|No|(int, int, int)|IDK|_ZN8ChunkPosC2Eiii|
|ChunkPos::ChunkPos|No|(int, int, int)|IDK|_ZN8ChunkPosC1Eiii|
|ChunkPos::distanceToSqr|No|(Entity const*) const|IDK|_ZNK8ChunkPos13distanceToSqrEPK6Entity|
|ControllerMoveInput::ControllerMoveInput|No|(Options*)|IDK|_ZN19ControllerMoveInputC2EP7Options|
|KeyboardInput::KeyboardInput|No|(Options*)|IDK|_ZN13KeyboardInputC2EP7Options|
|vtable for ControllerMoveInput|No|(undefined|IDK|_ZTV19ControllerMoveInput|
|ControllerMoveInput::ControllerMoveInput|No|(Options*)|IDK|_ZN19ControllerMoveInputC1EP7Options|
|Label::Label|No|(std::string, Minecraft*, int, int, int, int, bool)|IDK|_ZN5LabelC2ESsP9Minecraftiiiib|
|Label::Label|No|(std::string, Minecraft*, int, int, int, int, bool)|IDK|_ZN5LabelC1ESsP9Minecraftiiiib|
|Label::setCentered|No|(bool)|IDK|_ZN5Label11setCenteredEb|
|std::vector<MobSpawnerData, std::allocator<MobSpawnerData> >::operator=|No|(std::vector<MobSpawnerData, std::allocator<MobSpawnerData> > const&)|IDK|_ZNSt6vectorI14MobSpawnerDataSaIS0_EEaSERKS2_|
|MutatedBiome::MutatedBiome|No|(int, Biome*)|IDK|_ZN12MutatedBiomeC2EiP5Biome|
|MutatedBiome::MutatedBiome|No|(int, Biome*)|IDK|_ZN12MutatedBiomeC1EiP5Biome|
|BeetrootTile::BeetrootTile|No|(int)|IDK|_ZN12BeetrootTileC2Ei|
|std::vector<AABB, std::allocator<AABB> >::operator=|No|(std::vector<AABB, std::allocator<AABB> > const&)|IDK|_ZNSt6vectorI4AABBSaIS0_EEaSERKS2_|
|AABB::clipYCollide|No|(AABB const&, float) const|IDK|_ZNK4AABB12clipYCollideERKS_f|
|AABB::clipXCollide|No|(AABB const&, float) const|IDK|_ZNK4AABB12clipXCollideERKS_f|
|AABB::clipZCollide|No|(AABB const&, float) const|IDK|_ZNK4AABB12clipZCollideERKS_f|
|AABB::set|No|(AABB const&)|IDK|_ZN4AABB3setERKS_|
|std::vector<Tile*, std::allocator<Tile*> >::operator=|No|(std::vector<Tile*, std::allocator<Tile*> > const&)|IDK|_ZNSt6vectorIP4TileSaIS1_EEaSERKS3_|
|std::vector<FlyingItem, std::allocator<FlyingItem> >::operator=|No|(std::vector<FlyingItem, std::allocator<FlyingItem> > const&)|IDK|_ZNSt6vectorI10FlyingItemSaIS0_EEaSERKS2_|
|PlayerActionPacket::read|No|(RakNet::BitStream*)|IDK|_ZN18PlayerActionPacket4readEPN6RakNet9BitStreamE|
|UseItemPacket::read|No|(RakNet::BitStream*)|IDK|_ZN13UseItemPacket4readEPN6RakNet9BitStreamE|
|ListTagFloatAdder::operator|No|()|IDK|_ZN17ListTagFloatAdderclEf|
|CompoundTag::getList|No|(std::string const&) const|IDK|_ZNK11CompoundTag7getListERKSs|
|CompoundTag::getCompound|No|(std::string const&) const|IDK|_ZNK11CompoundTag11getCompoundERKSs|
|SpawnData::SpawnData|No|(CompoundTag*)|IDK|_ZN9SpawnDataC2EP11CompoundTag|
|SpawnData::SpawnData|No|(CompoundTag*)|IDK|_ZN9SpawnDataC1EP11CompoundTag|
|Arrow::readAdditionalSaveData|No|(CompoundTag*)|IDK|_ZN5Arrow22readAdditionalSaveDataEP11CompoundTag|
|std::_Rb_tree<std::string, std::string, std::_Identity<std::string>, std::less<std::string>, std::allocator<std::string> >::_M_erase|No|(std::_Rb_tree_node<std::string>*)|IDK|_ZNSt8_Rb_treeISsSsSt9_IdentityISsESt4lessISsESaISsEE8_M_eraseEPSt13_Rb_tree_nodeISsE|
|Touch::SelectWorldScreen::getUniqueLevelName|No|(std::string const&)|IDK|_ZN5Touch17SelectWorldScreen18getUniqueLevelNameERKSs|
|std::_Rb_tree<float, std::pair<float const, AppPlatformListener*>, std::_Select1st<std::pair<float const, AppPlatformListener*> >, std::less<float>, std::allocator<std::pair<float const, AppPlatformListener*> > >::_M_erase|No|(std::_Rb_tree_node<std::pair<float const, AppPlatformListener*> >*)|IDK|_ZNSt8_Rb_treeIfSt4pairIKfP19AppPlatformListenerESt10_Select1stIS4_ESt4lessIfESaIS4_EE8_M_eraseEPSt13_Rb_tree_nodeIS4_E|
|AppPlatform::~AppPlatform|No|()|IDK|_ZN11AppPlatformD0Ev|
|AppPlatform::~AppPlatform|No|()|IDK|_ZN11AppPlatformD2Ev|
|AppPlatform::~AppPlatform|No|()|IDK|_ZN11AppPlatformD1Ev|
(null)
(null)
|DisconnectionScreen::init|No|()|IDK|_ZN19DisconnectionScreen4initEv|
(null)
(null)
|OptionsScreen::createCategoryButton|No|(int, int, ImageDef&, int, int, int, int)|IDK|_ZN13OptionsScreen20createCategoryButtonEiiR8ImageDefiiii|
|OptionsScreen::createCategoryButtons|No|()|IDK|_ZN13OptionsScreen21createCategoryButtonsEv|
|Mob::getLookControl|No|()|IDK|_ZN3Mob14getLookControlEv|
|LookControl::setLookAt|No|(Entity*, float, float)|IDK|_ZN11LookControl9setLookAtEP6Entityff|
(null)
(null)
|HatchetItem::HatchetItem|No|(int, Item::Tier const&)|IDK|_ZN11HatchetItemC2EiRKN4Item4TierE|
|Item::Item|No|(int)|IDK|_ZN4ItemC2Ei|
|vtable for HatchetItem|No|(undefined|IDK|_ZTV11HatchetItem|
|HatchetItem::HatchetItem|No|(int, Item::Tier const&)|IDK|_ZN11HatchetItemC1EiRKN4Item4TierE|
|std::_Rb_tree<TileEntityRendererId, std::pair<TileEntityRendererId const, TileEntityRenderer*>, std::_Select1st<std::pair<TileEntityRendererId const, TileEntityRenderer*> >, std::less<TileEntityRendererId>, std::allocator<std::pair<TileEntityRendererId const, TileEntityRenderer*> > >::_M_erase|No|(std::_Rb_tree_node<std::pair<TileEntityRendererId const, TileEntityRenderer*> >*)|IDK|_ZNSt8_Rb_treeI20TileEntityRendererIdSt4pairIKS0_P18TileEntityRendererESt10_Select1stIS5_ESt4lessIS0_ESaIS5_EE8_M_eraseEPSt13_Rb_tree_nodeIS5_E|
|std::_Rb_tree<TileEntityRenderer*, TileEntityRenderer*, std::_Identity<TileEntityRenderer*>, std::less<TileEntityRenderer*>, std::allocator<TileEntityRenderer*> >::_M_erase|No|(std::_Rb_tree_node<TileEntityRenderer*>*)|IDK|_ZNSt8_Rb_treeIP18TileEntityRendererS1_St9_IdentityIS1_ESt4lessIS1_ESaIS1_EE8_M_eraseEPSt13_Rb_tree_nodeIS1_E|
(null)
|TileEntityRenderDispatcher::~TileEntityRenderDispatcher|No|()|IDK|_ZN26TileEntityRenderDispatcherD2Ev|
|TileEntityRenderDispatcher::~TileEntityRenderDispatcher|No|()|IDK|_ZN26TileEntityRenderDispatcherD1Ev|
|TileEntityRenderDispatcher::destroy|No|()|IDK|_ZN26TileEntityRenderDispatcher7destroyEv|
|TileEntityRenderDispatcher::instance|No|(undefined|IDK|_ZN26TileEntityRenderDispatcher8instanceE|
(null)
(null)
(null)
|TileEntityRenderDispatcher::TileEntityRenderDispatcher|No|()|IDK|_ZN26TileEntityRenderDispatcherC2Ev|
|TileEntityRenderer::TileEntityRenderer|No|()|IDK|_ZN18TileEntityRendererC2Ev|
|TileEntityRenderer::init|No|(TileEntityRenderDispatcher*)|IDK|_ZN18TileEntityRenderer4initEP26TileEntityRenderDispatcher|
|vtable for ChestRenderer|No|(undefined|IDK|_ZTV13ChestRenderer|
|vtable for SignRenderer|No|(undefined|IDK|_ZTV12SignRenderer|
|vtable for MobSpawnerRenderer|No|(undefined|IDK|_ZTV18MobSpawnerRenderer|
|TileEntityRenderDispatcher::TileEntityRenderDispatcher|No|()|IDK|_ZN26TileEntityRenderDispatcherC1Ev|
|std::_Rb_tree<int, std::pair<int const, Entity*>, std::_Select1st<std::pair<int const, Entity*> >, std::less<int>, std::allocator<std::pair<int const, Entity*> > >::_M_erase|No|(std::_Rb_tree_node<std::pair<int const, Entity*> >*)|IDK|_ZNSt8_Rb_treeIiSt4pairIKiP6EntityESt10_Select1stIS4_ESt4lessIiESaIS4_EE8_M_eraseEPSt13_Rb_tree_nodeIS4_E|
|std::_Rb_tree<Entity*, Entity*, std::_Identity<Entity*>, std::less<Entity*>, std::allocator<Entity*> >::_M_erase|No|(std::_Rb_tree_node<Entity*>*)|IDK|_ZNSt8_Rb_treeIP6EntityS1_St9_IdentityIS1_ESt4lessIS1_ESaIS1_EE8_M_eraseEPSt13_Rb_tree_nodeIS1_E|
|MultiPlayerLevel::~MultiPlayerLevel|No|()|IDK|_ZN16MultiPlayerLevelD2Ev|
|Level::~Level|No|()|IDK|_ZN5LevelD2Ev|
|MultiPlayerLevel::~MultiPlayerLevel|No|()|IDK|_ZN16MultiPlayerLevelD1Ev|
|non-virtual thunk to MultiPlayerLevel::~MultiPlayerLevel|No|()|IDK|_ZThn4_N16MultiPlayerLevelD1Ev|
|MultiPlayerLevel::~MultiPlayerLevel|No|()|IDK|_ZN16MultiPlayerLevelD0Ev|
|non-virtual thunk to MultiPlayerLevel::~MultiPlayerLevel|No|()|IDK|_ZThn4_N16MultiPlayerLevelD0Ev|
(null)
(null)
|MultiPlayerLevel::putEntity|No|(int, Entity*)|IDK|_ZN16MultiPlayerLevel9putEntityEiP6Entity|
(null)
(null)
(null)
(null)
(null)
(null)
(null)
(null)
|ChestScreen::handleAddItem|No|(FillingContainer*, FillingContainer*, int)|IDK|_ZN11ChestScreen13handleAddItemEP16FillingContainerS1_i|
|ItemInstance::matchesNulls|No|(ItemInstance const*, ItemInstance const*)|IDK|_ZN12ItemInstance12matchesNullsEPKS_S1_|
|ScrollingPane::getGridItemFor_slow|No|(int, ScrollingPane::GridItem&)|IDK|_ZN13ScrollingPane19getGridItemFor_slowEiRNS_8GridItemE|
|vtable for ContainerSetSlotPacket|No|(undefined|IDK|_ZTV22ContainerSetSlotPacket|
|ChestScreen::addItem|No|(Touch::InventoryPane const*, int)|IDK|_ZN11ChestScreen7addItemEPKN5Touch13InventoryPaneEi|
|non-virtual thunk to ChestScreen::addItem|No|(Touch::InventoryPane const*, int)|IDK|_ZThn136_N11ChestScreen7addItemEPKN5Touch13InventoryPaneEi|
(null)
|CompoundTag::putShort|No|(std::string const&, short)|IDK|_ZN11CompoundTag8putShortERKSss|
|Arrow::addAdditionalSaveData|No|(CompoundTag*)|IDK|_ZN5Arrow21addAdditionalSaveDataEP11CompoundTag|
|Entity::saveAsMount|No|(CompoundTag&)|IDK|_ZN6Entity11saveAsMountER11CompoundTag|
|SpawnData::save|No|()|IDK|_ZN9SpawnData4saveEv|
(null)
|BaseMobSpawner::save|No|(CompoundTag*)|IDK|_ZN14BaseMobSpawner4saveEP11CompoundTag|
(null)
(null)
|ChestScreen::handleBulkItemMovementRequest|No|(Touch::InventoryPane*)|IDK|_ZN11ChestScreen29handleBulkItemMovementRequestEPN5Touch13InventoryPaneE|
|ScrollingPane::queryHoldTime|No|(int*, int*)|IDK|_ZN13ScrollingPane13queryHoldTimeEPiS0_|
|Keyboard::_inputs|No|(undefined|IDK|_ZN8Keyboard7_inputsE|
|ChestScreen::render|No|(int, int, float)|IDK|_ZN11ChestScreen6renderEiif|
|Tesselator::voidBeginAndEndCalls|No|(bool)|IDK|_ZN10Tesselator20voidBeginAndEndCallsEb|
|Gui::setScissorRect|No|(IntRectangle const&)|IDK|_ZN3Gui14setScissorRectERK12IntRectangle|
(null)
(null)
|BaseMobSpawner::load|No|(CompoundTag*)|IDK|_ZN14BaseMobSpawner4loadEP11CompoundTag|
|ProgressScreen::init|No|()|IDK|_ZN14ProgressScreen4initEv|
|Touch::StartMenuScreen::chooseRandomSplash|No|()|IDK|_ZN5Touch15StartMenuScreen18chooseRandomSplashEv|
|OptionsScreen::init|No|()|IDK|_ZN13OptionsScreen4initEv|
|ChestScreen::init|No|()|IDK|_ZN11ChestScreen4initEv|
|NinePatchLayer::exclude|No|(int)|IDK|_ZN14NinePatchLayer7excludeEi|
(null)
(null)
|OptionsScreen::generateOptionScreens|No|()|IDK|_ZN13OptionsScreen21generateOptionScreensEv|
|OptionsPane::OptionsPane|No|()|IDK|_ZN11OptionsPaneC1Ev|
|OptionsPane::createOptionsGroup|No|(std::string)|IDK|_ZN11OptionsPane18createOptionsGroupESs|
|Options::Option::NAME|No|(undefined|IDK|_ZN7Options6Option4NAMEE|
|Options::Option::DIFFICULTY|No|(undefined|IDK|_ZN7Options6Option10DIFFICULTYE|
|Options::Option::THIRD_PERSON|No|(undefined|IDK|_ZN7Options6Option12THIRD_PERSONE|
|Options::Option::SERVER_VISIBLE|No|(undefined|IDK|_ZN7Options6Option14SERVER_VISIBLEE|
|Options::Option::SENSITIVITY|No|(undefined|IDK|_ZN7Options6Option11SENSITIVITYE|
|Options::Option::INVERT_MOUSE|No|(undefined|IDK|_ZN7Options6Option12INVERT_MOUSEE|
|Options::Option::LEFT_HANDED|No|(undefined|IDK|_ZN7Options6Option11LEFT_HANDEDE|
|Options::Option::USE_TOUCHSCREEN|No|(undefined|IDK|_ZN7Options6Option15USE_TOUCHSCREENE|
|Options::Option::USE_TOUCH_JOYPAD|No|(undefined|IDK|_ZN7Options6Option16USE_TOUCH_JOYPADE|
|Options::Option::PIXELS_PER_MILLIMETER|No|(undefined|IDK|_ZN7Options6Option21PIXELS_PER_MILLIMETERE|
|Options::Option::VIEW_DISTANCE|No|(undefined|IDK|_ZN7Options6Option13VIEW_DISTANCEE|
|Options::Option::GRAPHICS|No|(undefined|IDK|_ZN7Options6Option8GRAPHICSE|
|Options::Option::FANCY_SKIES|No|(undefined|IDK|_ZN7Options6Option11FANCY_SKIESE|
|Options::Option::ANIMATE_TEXTURES|No|(undefined|IDK|_ZN7Options6Option16ANIMATE_TEXTURESE|
|Options::Option::HIDE_GUI|No|(undefined|IDK|_ZN7Options6Option8HIDE_GUIE|
|Options::Option::SOUND|No|(undefined|IDK|_ZN7Options6Option5SOUNDE|
|Options::Option::DESTROY_VIBRATION|No|(undefined|IDK|_ZN7Options6Option17DESTROY_VIBRATIONE|
|Options::Option::LIMIT_WORLD_SIZE|No|(undefined|IDK|_ZN7Options6Option16LIMIT_WORLD_SIZEE|
|NetworkChunkSource::requestChunk|No|(ChunkPos const&, ChunkSource::LoadMode)|IDK|_ZN18NetworkChunkSource12requestChunkERK8ChunkPosN11ChunkSource8LoadModeE|
|NetworkChunkSource::acquireDiscarded|No|(std::unique_ptr<LevelChunk, std::default_delete<LevelChunk> >&)|IDK|_ZN18NetworkChunkSource16acquireDiscardedERSt10unique_ptrI10LevelChunkSt14default_deleteIS1_EE|
|std::_Hashtable<ChunkPos, std::pair<ChunkPos const, std::unique_ptr<LevelChunk, std::default_delete<LevelChunk> > >, std::allocator<std::pair<ChunkPos const, std::unique_ptr<LevelChunk, std::default_delete<LevelChunk> > > >, std::__detail::_Select1st, std::equal_to<ChunkPos>, std::hash<ChunkPos>, std::__detail::_Mod_range_hashing, std::__detail::_Default_ranged_hash, std::__detail::_Prime_rehash_policy, std::__detail::_Hashtable_traits<true, false, true> >::_M_insert_unique_node|No|(unsigned int, unsigned int, std::__detail::_Hash_node<std::pair<ChunkPos const, std::unique_ptr<LevelChunk, std::default_delete<LevelChunk> > >, true>*)|IDK|_ZNSt10_HashtableI8ChunkPosSt4pairIKS0_St10unique_ptrI10LevelChunkSt14default_deleteIS4_EEESaIS8_ENSt8__detail10_Select1stESt8equal_toIS0_ESt4hashIS0_ENSA_18_Mod_range_hashingENSA_20_Default_ranged_hashENSA_20_Prime_rehash_policyENSA_17_Hashtable_traitsILb1ELb0ELb1EEEE21_M_insert_unique_nodeEjjPNSA_10_Hash_nodeIS8_Lb1EEE|
|NetworkChunkSource::getIncomingChunk|No|(ChunkPos const&)|IDK|_ZN18NetworkChunkSource16getIncomingChunkERK8ChunkPos|
(null)
(null)
|MushroomIslandBiome::MushroomIslandBiome|No|(int)|IDK|_ZN19MushroomIslandBiomeC2Ei|
|MushroomIslandBiome::MushroomIslandBiome|No|(int)|IDK|_ZN19MushroomIslandBiomeC1Ei|
|std::_Hashtable<int, std::pair<int const, Entity*>, std::allocator<std::pair<int const, Entity*> >, std::__detail::_Select1st, std::equal_to<int>, std::hash<int>, std::__detail::_Mod_range_hashing, std::__detail::_Default_ranged_hash, std::__detail::_Prime_rehash_policy, std::__detail::_Hashtable_traits<false, false, true> >::_M_insert_unique_node|No|(unsigned int, unsigned int, std::__detail::_Hash_node<std::pair<int const, Entity*>, false>*)|IDK|_ZNSt10_HashtableIiSt4pairIKiP6EntityESaIS4_ENSt8__detail10_Select1stESt8equal_toIiESt4hashIiENS6_18_Mod_range_hashingENS6_20_Default_ranged_hashENS6_20_Prime_rehash_policyENS6_17_Hashtable_traitsILb0ELb0ELb1EEEE21_M_insert_unique_nodeEjjPNS6_10_Hash_nodeIS4_Lb0EEE|
|MultiPlayerLevel::addEntity|No|(Entity*)|IDK|_ZN16MultiPlayerLevel9addEntityEP6Entity|
|std::_Hashtable<int, std::pair<int const, std::vector<Rect2D, std::allocator<Rect2D> > >, std::allocator<std::pair<int const, std::vector<Rect2D, std::allocator<Rect2D> > > >, std::__detail::_Select1st, std::equal_to<int>, std::hash<int>, std::__detail::_Mod_range_hashing, std::__detail::_Default_ranged_hash, std::__detail::_Prime_rehash_policy, std::__detail::_Hashtable_traits<false, false, true> >::_M_insert_unique_node|No|(unsigned int, unsigned int, std::__detail::_Hash_node<std::pair<int const, std::vector<Rect2D, std::allocator<Rect2D> > >, false>*)|IDK|_ZNSt10_HashtableIiSt4pairIKiSt6vectorI6Rect2DSaIS3_EEESaIS6_ENSt8__detail10_Select1stESt8equal_toIiESt4hashIiENS8_18_Mod_range_hashingENS8_20_Default_ranged_hashENS8_20_Prime_rehash_policyENS8_17_Hashtable_traitsILb0ELb0ELb1EEEE21_M_insert_unique_nodeEjjPNS8_10_Hash_nodeIS6_Lb0EEE|
(null)
|TileRenderer::drawTile|No|(FullTile const&)|IDK|_ZN12TileRenderer8drawTileERK8FullTile|
|Tesselator::normal|No|(float, float, float)|IDK|_ZN10Tesselator6normalEfff|
|TileTextureTesselator::_tesselatedTextures|No|(undefined|IDK|_ZN21TileTextureTesselator19_tesselatedTexturesE|
|std::_Hashtable<int, std::pair<int const, MeshBuffer>, std::allocator<std::pair<int const, MeshBuffer> >, std::__detail::_Select1st, std::equal_to<int>, std::hash<int>, std::__detail::_Mod_range_hashing, std::__detail::_Default_ranged_hash, std::__detail::_Prime_rehash_policy, std::__detail::_Hashtable_traits<false, false, true> >::_M_insert_unique_node|No|(unsigned int, unsigned int, std::__detail::_Hash_node<std::pair<int const, MeshBuffer>, false>*)|IDK|_ZNSt10_HashtableIiSt4pairIKi10MeshBufferESaIS3_ENSt8__detail10_Select1stESt8equal_toIiESt4hashIiENS5_18_Mod_range_hashingENS5_20_Default_ranged_hashENS5_20_Prime_rehash_policyENS5_17_Hashtable_traitsILb0ELb0ELb1EEEE21_M_insert_unique_nodeEjjPNS5_10_Hash_nodeIS3_Lb0EEE|
|TileRenderer::renderTile|No|(FullTile const&)|IDK|_ZN12TileRenderer10renderTileERK8FullTile|
(null)
(null)
|Touch::TouchWorldSelectionList::commit|No|()|IDK|_ZN5Touch23TouchWorldSelectionList6commitEv|
|ChestScreen::setupPane|No|()|IDK|_ZN11ChestScreen9setupPaneEv|
|ChestScreen::setupPositions|No|()|IDK|_ZN11ChestScreen14setupPositionsEv|
|ChestScreen::tick|No|()|IDK|_ZN11ChestScreen4tickEv|
|ArmorRecipes::addRecipes|No|(Recipes*)|IDK|_ZN12ArmorRecipes10addRecipesEP7Recipes|
|Recipes::Shape|No|(std::string const&, std::string const&)|IDK|_ZN7Recipes5ShapeERKSsS1_|
|Item::helmet_cloth|No|(undefined|IDK|_ZN4Item12helmet_clothE|
|Item::helmet_iron|No|(undefined|IDK|_ZN4Item11helmet_ironE|
|Item::helmet_diamond|No|(undefined|IDK|_ZN4Item14helmet_diamondE|
|Item::helmet_gold|No|(undefined|IDK|_ZN4Item11helmet_goldE|
|Item::chestplate_cloth|No|(undefined|IDK|_ZN4Item16chestplate_clothE|
|Item::chestplate_iron|No|(undefined|IDK|_ZN4Item15chestplate_ironE|
|Item::chestplate_diamond|No|(undefined|IDK|_ZN4Item18chestplate_diamondE|
|Item::chestplate_gold|No|(undefined|IDK|_ZN4Item15chestplate_goldE|
|Item::leggings_cloth|No|(undefined|IDK|_ZN4Item14leggings_clothE|
|Item::leggings_iron|No|(undefined|IDK|_ZN4Item13leggings_ironE|
|Item::leggings_diamond|No|(undefined|IDK|_ZN4Item16leggings_diamondE|
|Item::leggings_gold|No|(undefined|IDK|_ZN4Item13leggings_goldE|
|Item::boots_cloth|No|(undefined|IDK|_ZN4Item11boots_clothE|
|Item::boots_iron|No|(undefined|IDK|_ZN4Item10boots_ironE|
|Item::boots_diamond|No|(undefined|IDK|_ZN4Item13boots_diamondE|
|Item::boots_gold|No|(undefined|IDK|_ZN4Item10boots_goldE|
|void std::__unguarded_linear_insert<__gnu_cxx::__normal_iterator<LevelSummary*, std::vector<LevelSummary, std::allocator<LevelSummary> > > >|No|(__gnu_cxx::__normal_iterator<LevelSummary*, std::vector<LevelSummary, std::allocator<LevelSummary> > >)|IDK|_ZSt25__unguarded_linear_insertIN9__gnu_cxx17__normal_iteratorIP12LevelSummarySt6vectorIS2_SaIS2_EEEEEvT_|
|void std::__insertion_sort<__gnu_cxx::__normal_iterator<LevelSummary*, std::vector<LevelSummary, std::allocator<LevelSummary> > > >|No|(__gnu_cxx::__normal_iterator<LevelSummary*, std::vector<LevelSummary, std::allocator<LevelSummary> > >, __gnu_cxx::__normal_iterator<LevelSummary*, std::vector<LevelSummary, std::allocator<LevelSummary> > >)|IDK|_ZSt16__insertion_sortIN9__gnu_cxx17__normal_iteratorIP12LevelSummarySt6vectorIS2_SaIS2_EEEEEvT_S8_|
|std::_Hashtable<VisibilityExtimator*, VisibilityExtimator*, std::allocator<VisibilityExtimator*>, std::__detail::_Identity, std::equal_to<VisibilityExtimator*>, std::hash<VisibilityExtimator*>, std::__detail::_Mod_range_hashing, std::__detail::_Default_ranged_hash, std::__detail::_Prime_rehash_policy, std::__detail::_Hashtable_traits<false, true, true> >::_M_insert_unique_node|No|(unsigned int, unsigned int, std::__detail::_Hash_node<VisibilityExtimator*, false>*)|IDK|_ZNSt10_HashtableIP19VisibilityExtimatorS1_SaIS1_ENSt8__detail9_IdentityESt8equal_toIS1_ESt4hashIS1_ENS3_18_Mod_range_hashingENS3_20_Default_ranged_hashENS3_20_Prime_rehash_policyENS3_17_Hashtable_traitsILb0ELb1ELb1EEEE21_M_insert_unique_nodeEjjPNS3_10_Hash_nodeIS1_Lb0EEE|
|ThreadLocal<VisibilityExtimator>::getLocal|No|()|IDK|_ZN11ThreadLocalI19VisibilityExtimatorE8getLocalEv|
|void std::__adjust_heap<__gnu_cxx::__normal_iterator<LevelSummary*, std::vector<LevelSummary, std::allocator<LevelSummary> > >, int, LevelSummary>|No|(__gnu_cxx::__normal_iterator<LevelSummary*, std::vector<LevelSummary, std::allocator<LevelSummary> > >, int, int, LevelSummary)|IDK|_ZSt13__adjust_heapIN9__gnu_cxx17__normal_iteratorIP12LevelSummarySt6vectorIS2_SaIS2_EEEEiS2_EvT_T0_S9_T1_|
|void std::make_heap<__gnu_cxx::__normal_iterator<LevelSummary*, std::vector<LevelSummary, std::allocator<LevelSummary> > > >|No|(__gnu_cxx::__normal_iterator<LevelSummary*, std::vector<LevelSummary, std::allocator<LevelSummary> > >, __gnu_cxx::__normal_iterator<LevelSummary*, std::vector<LevelSummary, std::allocator<LevelSummary> > >)|IDK|_ZSt9make_heapIN9__gnu_cxx17__normal_iteratorIP12LevelSummarySt6vectorIS2_SaIS2_EEEEEvT_S8_|
|void std::__pop_heap<__gnu_cxx::__normal_iterator<LevelSummary*, std::vector<LevelSummary, std::allocator<LevelSummary> > > >|No|(__gnu_cxx::__normal_iterator<LevelSummary*, std::vector<LevelSummary, std::allocator<LevelSummary> > >, __gnu_cxx::__normal_iterator<LevelSummary*, std::vector<LevelSummary, std::allocator<LevelSummary> > >, __gnu_cxx::__normal_iterator<LevelSummary*, std::vector<LevelSummary, std::allocator<LevelSummary> > >)|IDK|_ZSt10__pop_heapIN9__gnu_cxx17__normal_iteratorIP12LevelSummarySt6vectorIS2_SaIS2_EEEEEvT_S8_S8_|
|void std::swap<LevelSummary>|No|(LevelSummary&, LevelSummary&)|IDK|_ZSt4swapI12LevelSummaryEvRT_S2_|
|void std::__introsort_loop<__gnu_cxx::__normal_iterator<LevelSummary*, std::vector<LevelSummary, std::allocator<LevelSummary> > >, int>|No|(__gnu_cxx::__normal_iterator<LevelSummary*, std::vector<LevelSummary, std::allocator<LevelSummary> > >, __gnu_cxx::__normal_iterator<LevelSummary*, std::vector<LevelSummary, std::allocator<LevelSummary> > >, int)|IDK|_ZSt16__introsort_loopIN9__gnu_cxx17__normal_iteratorIP12LevelSummarySt6vectorIS2_SaIS2_EEEEiEvT_S8_T0_|
|Touch::SelectWorldScreen::loadLevelSource|No|()|IDK|_ZN5Touch17SelectWorldScreen15loadLevelSourceEv|
|LevelStorageSource::TempLevelId|No|(undefined|IDK|_ZN18LevelStorageSource11TempLevelIdE|
|Touch::SelectWorldScreen::init|No|()|IDK|_ZN5Touch17SelectWorldScreen4initEv|
|RenderChunk::Builder::build|No|(RenderChunk&)|IDK|_ZN11RenderChunk7Builder5buildERS_|
|VisibilityExtimator::start|No|(RenderChunk&)|IDK|_ZN19VisibilityExtimator5startER11RenderChunk|
|VisibilityExtimator::setTile|No|(TilePos const&, Tile*)|IDK|_ZN19VisibilityExtimator7setTileERK7TilePosP4Tile|
|Tesselator::beginIndices|No|(int)|IDK|_ZN10Tesselator12beginIndicesEi|
|Tesselator::convertToTrilist|No|(bool)|IDK|_ZN10Tesselator16convertToTrilistEb|
|VisibilityExtimator::finish|No|()|IDK|_ZN19VisibilityExtimator6finishEv|
|VisibilityExtimator::pool|No|(undefined|IDK|_ZN19VisibilityExtimator4poolE|
|RenderChunk::rebuild|No|()|IDK|_ZN11RenderChunk7rebuildEv|
|MultiPlayerLevel::tick|No|()|IDK|_ZN16MultiPlayerLevel4tickEv|
|Level::tick|No|()|IDK|_ZN5Level4tickEv|
|Level::setTime|No|(long)|IDK|_ZN5Level7setTimeEl|
|Level::updateSkyDarken|No|()|IDK|_ZN5Level15updateSkyDarkenEv|
|Mob::updateAttackAnim|No|()|IDK|_ZN3Mob16updateAttackAnimEv|
|Zombie::aiStep|No|()|IDK|_ZN6Zombie6aiStepEv|
|Touch::SelectWorldScreen::~SelectWorldScreen|No|()|IDK|_ZN5Touch17SelectWorldScreenD2Ev|
|Touch::SelectWorldScreen::~SelectWorldScreen|No|()|IDK|_ZN5Touch17SelectWorldScreenD1Ev|
|Touch::SelectWorldScreen::~SelectWorldScreen|No|()|IDK|_ZN5Touch17SelectWorldScreenD0Ev|
|ChestMenu::setSlot|No|(int, ItemInstance*)|IDK|_ZN9ChestMenu7setSlotEiP12ItemInstance|
|ContainerMenu::setSlot|No|(int, ItemInstance*)|IDK|_ZN13ContainerMenu7setSlotEiP12ItemInstance|
|Screen::setupPositions|No|()|IDK|_ZN6Screen14setupPositionsEv|
|Item::getIcon|No|(int, int, bool) const|IDK|_ZNK4Item7getIconEiib|
|Item::useOn|No|(ItemInstance*, Player*, int, int, int, signed char, float, float, float)|IDK|_ZN4Item5useOnEP12ItemInstanceP6Playeriiiafff|
|Item::getDescriptionId|No|() const|IDK|_ZNK4Item16getDescriptionIdEv|
|Item::getDescriptionId|No|(ItemInstance const*) const|IDK|_ZNK4Item16getDescriptionIdEPK12ItemInstance|
|ContainerMenu::getItems|No|()|IDK|_ZN13ContainerMenu8getItemsEv|
|TextBox::numberChars|No|(undefined|IDK|_ZN7TextBox11numberCharsE|
|Controller::DIRECTION_Y_THRESHOLD|No|(undefined|IDK|_ZN10Controller21DIRECTION_Y_THRESHOLDE|
|Controller::DIRECTION_X_THRESHOLD|No|(undefined|IDK|_ZN10Controller21DIRECTION_X_THRESHOLDE|
|Arrow::ARROW_BASE_DAMAGE|No|(undefined|IDK|_ZN5Arrow17ARROW_BASE_DAMAGEE|
|Goal::canContinueToUse|No|()|IDK|_ZN4Goal16canContinueToUseEv|
|SlabTile::getShape|No|(unsigned char, AABB&, bool)|IDK|_ZN8SlabTile8getShapeEhR4AABBb|
|SlabTile::shouldRenderFace|No|(TileSource*, int, int, int, signed char, AABB const&)|IDK|_ZN8SlabTile16shouldRenderFaceEP10TileSourceiiiaRK4AABB|
|SlabTile::getResourceCount|No|(Random*)|IDK|_ZN8SlabTile16getResourceCountEP6Random|
|SlabTile::getPlacementDataValue|No|(Mob*, int, int, int, signed char, float, float, float, int)|IDK|_ZN8SlabTile21getPlacementDataValueEP3Mobiiiafffi|
|Level::onSourceCreated|No|(TileSource*)|IDK|_ZN5Level15onSourceCreatedEP10TileSource|
|Level::onSourceDestroyed|No|(TileSource*)|IDK|_ZN5Level17onSourceDestroyedEP10TileSource|
|Level::onTileChanged|No|(TileSource*, TilePos const&, FullTile, FullTile, int)|IDK|_ZN5Level13onTileChangedEP10TileSourceRK7TilePos8FullTileS5_i|
|Level::addPlayer|No|(Player*)|IDK|_ZN5Level9addPlayerEP6Player|
|Level::runLightUpdates|No|(TileSource*, LightLayer const&, TilePos const&, TilePos const&)|IDK|_ZN5Level15runLightUpdatesEP10TileSourceRK10LightLayerRK7TilePosS7_|
|Level::onNewChunkFor|No|(Player&, LevelChunk&)|IDK|_ZN5Level13onNewChunkForER6PlayerR10LevelChunk|
|Level::onChunkLoaded|No|(LevelChunk&)|IDK|_ZN5Level13onChunkLoadedER10LevelChunk|
|Level::onEntityRemoved|No|(std::unique_ptr<Entity, std::default_delete<Entity> >&)|IDK|_ZN5Level15onEntityRemovedERSt10unique_ptrI6EntitySt14default_deleteIS1_EE|
|Level::onEntityRemoved|No|(Entity&)|IDK|_ZN5Level15onEntityRemovedER6Entity|
|Level::onAppSuspended|No|()|IDK|_ZN5Level14onAppSuspendedEv|
|Level::onAppResumed|No|()|IDK|_ZN5Level12onAppResumedEv|
|non-virtual thunk to Level::onAppSuspended|No|()|IDK|_ZThn4_N5Level14onAppSuspendedEv|
|non-virtual thunk to Level::onAppResumed|No|()|IDK|_ZThn4_N5Level12onAppResumedEv|
|Animal::isFood|No|(ItemInstance const*) const|IDK|_ZNK6Animal6isFoodEPK12ItemInstance|
|RolledSelectionListH::getItemAtPosition|No|(int, int)|IDK|_ZN20RolledSelectionListH17getItemAtPositionEii|
|RolledSelectionListH::render|No|(int, int, float)|IDK|_ZN20RolledSelectionListH6renderEiif|
|RolledSelectionListH::renderHoleBackground|No|(float, float, int, int)|IDK|_ZN20RolledSelectionListH20renderHoleBackgroundEffii|
|RolledSelectionListH::setRenderSelection|No|(bool)|IDK|_ZN20RolledSelectionListH18setRenderSelectionEb|
|RolledSelectionListH::setComponentSelected|No|(bool)|IDK|_ZN20RolledSelectionListH20setComponentSelectedEb|
|RolledSelectionListH::getMaxPosition|No|()|IDK|_ZN20RolledSelectionListH14getMaxPositionEv|
|ConfirmScreen::render|No|(int, int, float)|IDK|_ZN13ConfirmScreen6renderEiif|
|ConfirmScreen::init|No|()|IDK|_ZN13ConfirmScreen4initEv|
|ConfirmScreen::setupPositions|No|()|IDK|_ZN13ConfirmScreen14setupPositionsEv|
|ConfirmScreen::handleBackEvent|No|(bool)|IDK|_ZN13ConfirmScreen15handleBackEventEb|
|ConfirmScreen::buttonClicked|No|(Button*)|IDK|_ZN13ConfirmScreen13buttonClickedEP6Button|
|ConfirmScreen::controllerDirectionChanged|No|(int, Controller::StickDirection)|IDK|_ZN13ConfirmScreen26controllerDirectionChangedEiN10Controller14StickDirectionE|
|BlockSelector::~BlockSelector|No|()|IDK|_ZN13BlockSelectorD2Ev|
|vtable for BlockSelector|No|(undefined|IDK|_ZTV13BlockSelector|
|BlockSelector::~BlockSelector|No|()|IDK|_ZN13BlockSelectorD1Ev|
|MineshaftStairs::addAdditionalSaveData|No|(CompoundTag*)|IDK|_ZN15MineshaftStairs21addAdditionalSaveDataEP11CompoundTag|
|MineshaftStairs::readAdditionalSaveData|No|(CompoundTag*)|IDK|_ZN15MineshaftStairs22readAdditionalSaveDataEP11CompoundTag|
|LongTag::write|No|(IDataOutput*)|IDK|_ZN7LongTag5writeEP11IDataOutput|
|LongTag::load|No|(IDataInput*)|IDK|_ZN7LongTag4loadEP10IDataInput|
|LongTag::getId|No|() const|IDK|_ZNK7LongTag5getIdEv|
|DoubleTag::write|No|(IDataOutput*)|IDK|_ZN9DoubleTag5writeEP11IDataOutput|
|DoubleTag::load|No|(IDataInput*)|IDK|_ZN9DoubleTag4loadEP10IDataInput|
|DoubleTag::getId|No|() const|IDK|_ZNK9DoubleTag5getIdEv|
|ByteArrayTag::getId|No|() const|IDK|_ZNK12ByteArrayTag5getIdEv|
|ByteArrayTag::write|No|(IDataOutput*)|IDK|_ZN12ByteArrayTag5writeEP11IDataOutput|
|IntArrayTag::getId|No|() const|IDK|_ZNK11IntArrayTag5getIdEv|
|IntArrayTag::write|No|(IDataOutput*)|IDK|_ZN11IntArrayTag5writeEP11IDataOutput|
|TileEntity::onUpdatePacket|No|(CompoundTag*)|IDK|_ZN10TileEntity14onUpdatePacketEP11CompoundTag|
|TileEntity::onNeighborChanged|No|(int, int, int)|IDK|_ZN10TileEntity17onNeighborChangedEiii|
|TileEntity::getShadowRadius|No|(TileSource&)|IDK|_ZN10TileEntity15getShadowRadiusER10TileSource|
|MineshaftPiece::~MineshaftPiece|No|()|IDK|_ZN14MineshaftPieceD2Ev|
|vtable for StructurePiece|No|(undefined|IDK|_ZTV14StructurePiece|
|MineshaftPiece::~MineshaftPiece|No|()|IDK|_ZN14MineshaftPieceD1Ev|
|CoalItem::getIcon|No|(int, int, bool) const|IDK|_ZNK8CoalItem7getIconEiib|
|Player::startDestroying|No|()|IDK|_ZN6Player15startDestroyingEv|
|Player::stopDestroying|No|()|IDK|_ZN6Player14stopDestroyingEv|
|Player::getEntityTypeId|No|() const|IDK|_ZNK6Player15getEntityTypeIdEv|
|Player::getBaseSpeed|No|()|IDK|_ZN6Player12getBaseSpeedEv|
|Player::DEFAULT_WALK_SPEED|No|(undefined|IDK|_ZN6Player18DEFAULT_WALK_SPEEDE|
|Player::useNewAi|No|()|IDK|_ZN6Player8useNewAiEv|
|ThrownEgg::getEntityTypeId|No|() const|IDK|_ZNK9ThrownEgg15getEntityTypeIdEv|
|Snowball::getEntityTypeId|No|() const|IDK|_ZNK8Snowball15getEntityTypeIdEv|
|SetHealthPacket::handle|No|(RakNet::RakNetGUID const&, NetEventCallback*)|IDK|_ZN15SetHealthPacket6handleERKN6RakNet10RakNetGUIDEP16NetEventCallback|
|FoodItem::isFood|No|() const|IDK|_ZNK8FoodItem6isFoodEv|
|FoodItem::getMaxUseDuration|No|() const|IDK|_ZNK8FoodItem17getMaxUseDurationEv|
|FoodItem::getUseAnimation|No|() const|IDK|_ZNK8FoodItem15getUseAnimationEv|
|ShearsItem::canDestroySpecial|No|(Tile const*) const|IDK|_ZNK10ShearsItem17canDestroySpecialEPK4Tile|
|WeaponItem::getDestroySpeed|No|(ItemInstance*, Tile*)|IDK|_ZN10WeaponItem15getDestroySpeedEP12ItemInstanceP4Tile|
|WeaponItem::getAttackDamage|No|(Entity*)|IDK|_ZN10WeaponItem15getAttackDamageEP6Entity|
|WeaponItem::isHandEquipped|No|() const|IDK|_ZNK10WeaponItem14isHandEquippedEv|
|WeaponItem::getMaxUseDuration|No|() const|IDK|_ZNK10WeaponItem17getMaxUseDurationEv|
|WeaponItem::use|No|(ItemInstance*, Level*, Player*)|IDK|_ZN10WeaponItem3useEP12ItemInstanceP5LevelP6Player|
|WeaponItem::canDestroySpecial|No|(Tile const*) const|IDK|_ZNK10WeaponItem17canDestroySpecialEPK4Tile|
|SaddleItem::interactEnemy|No|(ItemInstance*, Mob*, Player*)|IDK|_ZN10SaddleItem13interactEnemyEP12ItemInstanceP3MobP6Player|
|SeedItem::isSeed|No|() const|IDK|_ZNK8SeedItem6isSeedEv|
|ClockItem::getIcon|No|(int, int, bool) const|IDK|_ZNK9ClockItem7getIconEiib|
|CompassItem::getIcon|No|(int, int, bool) const|IDK|_ZNK11CompassItem7getIconEiib|
|ShearsItem::getDestroySpeed|No|(ItemInstance*, Tile*)|IDK|_ZN10ShearsItem15getDestroySpeedEP12ItemInstanceP4Tile|
|Mushroom::mayPlaceOn|No|(int)|IDK|_ZN8Mushroom10mayPlaceOnEi|
|SignTile::isPathfindable|No|(TileSource*, int, int, int)|IDK|_ZN8SignTile14isPathfindableEP10TileSourceiii|
|SignTile::getResource|No|(int, Random*)|IDK|_ZN8SignTile11getResourceEiP6Random|
|IConfigListener::~IConfigListener|No|()|IDK|_ZN15IConfigListenerD2Ev|
|vtable for IConfigListener|No|(undefined|IDK|_ZTV15IConfigListener|
|IConfigListener::~IConfigListener|No|()|IDK|_ZN15IConfigListenerD1Ev|
|App::destroy|No|()|IDK|_ZN3App7destroyEv|
|App::loadState|No|(void*, int)|IDK|_ZN3App9loadStateEPvi|
|App::saveState|No|(void**, int*)|IDK|_ZN3App9saveStateEPPvPi|
|App::draw|No|()|IDK|_ZN3App4drawEv|
|App::quit|No|()|IDK|_ZN3App4quitEv|
|App::wantToQuit|No|()|IDK|_ZN3App10wantToQuitEv|
|TilePlanterItem::isEmissive|No|(int) const|IDK|_ZNK15TilePlanterItem10isEmissiveEi|
|HeartParticle::init|No|(float, float, float, float, float, float, int)|IDK|_ZN13HeartParticle4initEffffffi|
|HeartParticle::normalTick|No|()|IDK|_ZN13HeartParticle10normalTickEv|
|TallGrass::getTexture|No|(signed char, int)|IDK|_ZN9TallGrass10getTextureEai|
|TallGrass::getCarriedTexture|No|(signed char, int)|IDK|_ZN9TallGrass17getCarriedTextureEai|
|TallGrass::getColor|No|(int)|IDK|_ZN9TallGrass8getColorEi|
|TallGrass::getColor|No|(TileSource*, int, int, int)|IDK|_ZN9TallGrass8getColorEP10TileSourceiii|
|TallGrass::onGraphicsModeChanged|No|(bool, bool)|IDK|_ZN9TallGrass21onGraphicsModeChangedEbb|
|IContainerListener::~IContainerListener|No|()|IDK|_ZN18IContainerListenerD2Ev|
|vtable for IContainerListener|No|(undefined|IDK|_ZTV18IContainerListener|
|IContainerListener::~IContainerListener|No|()|IDK|_ZN18IContainerListenerD1Ev|
|IContainerListener::refreshContainer|No|(BaseContainerMenu*, std::vector<ItemInstance, std::allocator<ItemInstance> > const&)|IDK|_ZN18IContainerListener16refreshContainerEP17BaseContainerMenuRKSt6vectorI12ItemInstanceSaIS3_EE|
|IContainerListener::slotChanged|No|(BaseContainerMenu*, int, ItemInstance const&, bool)|IDK|_ZN18IContainerListener11slotChangedEP17BaseContainerMenuiRK12ItemInstanceb|
|IContainerListener::setContainerData|No|(BaseContainerMenu*, int, int)|IDK|_ZN18IContainerListener16setContainerDataEP17BaseContainerMenuii|
|LocalPlayer::animateRespawn|No|()|IDK|_ZN11LocalPlayer14animateRespawnEv|
|IPosTranslator::~IPosTranslator|No|()|IDK|_ZN14IPosTranslatorD2Ev|
|vtable for IPosTranslator|No|(undefined|IDK|_ZTV14IPosTranslator|
|IPosTranslator::~IPosTranslator|No|()|IDK|_ZN14IPosTranslatorD1Ev|
|OffsetPosTranslator::to|No|(float&, float&, float&)|IDK|_ZN19OffsetPosTranslator2toERfS0_S0_|
|OffsetPosTranslator::to|No|(int&, int&, int&)|IDK|_ZN19OffsetPosTranslator2toERiS0_S0_|
|OffsetPosTranslator::from|No|(float&, float&, float&)|IDK|_ZN19OffsetPosTranslator4fromERfS0_S0_|
|OffsetPosTranslator::from|No|(int&, int&, int&)|IDK|_ZN19OffsetPosTranslator4fromERiS0_S0_|
|PodzolTile::getResource|No|(int, Random*)|IDK|_ZN10PodzolTile11getResourceEiP6Random|
|PodzolTile::getTexture|No|(signed char, int)|IDK|_ZN10PodzolTile10getTextureEai|
|PodzolTile::getMobToSpawn|No|(TileSource&, TilePos const&) const|IDK|_ZNK10PodzolTile13getMobToSpawnER10TileSourceRK7TilePos|
|BucketItem::getIcon|No|(int, int, bool) const|IDK|_ZNK10BucketItem7getIconEiib|
|BucketItem::isLiquidClipItem|No|(int) const|IDK|_ZNK10BucketItem16isLiquidClipItemEi|
|BucketItem::isEmissive|No|(int) const|IDK|_ZNK10BucketItem10isEmissiveEi|
|MobRenderer::getArmorTransparencyMode|No|() const|IDK|_ZNK11MobRenderer24getArmorTransparencyModeEv|
|IItemPaneCallback::~IItemPaneCallback|No|()|IDK|_ZN17IItemPaneCallbackD2Ev|
|vtable for IItemPaneCallback|No|(undefined|IDK|_ZTV17IItemPaneCallback|
|IItemPaneCallback::~IItemPaneCallback|No|()|IDK|_ZN17IItemPaneCallbackD1Ev|
|SurvivalInventoryScreen::renderGameBehind|No|()|IDK|_ZN23SurvivalInventoryScreen16renderGameBehindEv|
|SurvivalInventoryScreen::isAllowed|No|(int)|IDK|_ZN23SurvivalInventoryScreen9isAllowedEi|
|non-virtual thunk to SurvivalInventoryScreen::isAllowed|No|(int)|IDK|_ZThn132_N23SurvivalInventoryScreen9isAllowedEi|
|MonsterRoomFeature::~MonsterRoomFeature|No|()|IDK|_ZN18MonsterRoomFeatureD2Ev|
|MonsterRoomFeature::~MonsterRoomFeature|No|()|IDK|_ZN18MonsterRoomFeatureD1Ev|
|DefaultMobSpawner::getTileSource|No|()|IDK|_ZN17DefaultMobSpawner13getTileSourceEv|
|DefaultMobSpawner::getPos|No|()|IDK|_ZN17DefaultMobSpawner6getPosEv|
|Goal::~Goal|No|()|IDK|_ZN4GoalD2Ev|
|Goal::~Goal|No|()|IDK|_ZN4GoalD1Ev|
|std::function<void |No|()|IDK|_ZNSt8functionIFvvEED2Ev|
|std::function<void |No|()|IDK|_ZNSt8functionIFvvEED1Ev|
|StructureFeature::getStructureAt|No|(int, int, int)|IDK|_ZN16StructureFeature14getStructureAtEiii|
|VillagePiece::getVillagerProfession|No|(int)|IDK|_ZN12VillagePiece21getVillagerProfessionEi|
|VillagePiece::~VillagePiece|No|()|IDK|_ZN12VillagePieceD2Ev|
|VillagePiece::~VillagePiece|No|()|IDK|_ZN12VillagePieceD1Ev|
|Well::~Well|No|()|IDK|_ZN4WellD2Ev|
|Well::~Well|No|()|IDK|_ZN4WellD1Ev|
|SmallTemple::getVillagerProfession|No|(int)|IDK|_ZN11SmallTemple21getVillagerProfessionEi|
|BookHouse::getVillagerProfession|No|(int)|IDK|_ZN9BookHouse21getVillagerProfessionEi|
|PigHouse::getVillagerProfession|No|(int)|IDK|_ZN8PigHouse21getVillagerProfessionEi|
|Smithy::getVillagerProfession|No|(int)|IDK|_ZN6Smithy21getVillagerProfessionEi|
|StrongholdPiece::~StrongholdPiece|No|()|IDK|_ZN15StrongholdPieceD2Ev|
|StrongholdPiece::~StrongholdPiece|No|()|IDK|_ZN15StrongholdPieceD1Ev|
|SHStairsDown::~SHStairsDown|No|()|IDK|_ZN12SHStairsDownD2Ev|
|SHStairsDown::~SHStairsDown|No|()|IDK|_ZN12SHStairsDownD1Ev|
|SHFillerCorridor::postProcess|No|(TileSource*, Random&, BoundingBox const&)|IDK|_ZN16SHFillerCorridor11postProcessEP10TileSourceR6RandomRK11BoundingBox|
|SHFillerCorridor::addChildren|No|(StructurePiece*, std::vector<std::unique_ptr<StructurePiece, std::default_delete<StructurePiece> >, std::allocator<std::unique_ptr<StructurePiece, std::default_delete<StructurePiece> > > >&, Random&)|IDK|_ZN16SHFillerCorridor11addChildrenEP14StructurePieceRSt6vectorISt10unique_ptrIS0_St14default_deleteIS0_EESaIS6_EER6Random|
|SHLibrary::addChildren|No|(StructurePiece*, std::vector<std::unique_ptr<StructurePiece, std::default_delete<StructurePiece> >, std::allocator<std::unique_ptr<StructurePiece, std::default_delete<StructurePiece> > > >&, Random&)|IDK|_ZN9SHLibrary11addChildrenEP14StructurePieceRSt6vectorISt10unique_ptrIS0_St14default_deleteIS0_EESaIS6_EER6Random|
|SHPortalRoom::addChildren|No|(StructurePiece*, std::vector<std::unique_ptr<StructurePiece, std::default_delete<StructurePiece> >, std::allocator<std::unique_ptr<StructurePiece, std::default_delete<StructurePiece> > > >&, Random&)|IDK|_ZN12SHPortalRoom11addChildrenEP14StructurePieceRSt6vectorISt10unique_ptrIS0_St14default_deleteIS0_EESaIS6_EER6Random|
|PickaxeItem::getDestroySpeed|No|(ItemInstance*, Tile*)|IDK|_ZN11PickaxeItem15getDestroySpeedEP12ItemInstanceP4Tile|
|BaseRailTile::getResourceCount|No|(Random*)|IDK|_ZN12BaseRailTile16getResourceCountEP6Random|
|BaseRailTile::updateState|No|(TileSource*, int, int, int, int, int, int)|IDK|_ZN12BaseRailTile11updateStateEP10TileSourceiiiiii|
|ContainerClosePacket::handle|No|(RakNet::RakNetGUID const&, NetEventCallback*)|IDK|_ZN20ContainerClosePacket6handleERKN6RakNet10RakNetGUIDEP16NetEventCallback|
|MovePlayerPacket::handle|No|(RakNet::RakNetGUID const&, NetEventCallback*)|IDK|_ZN16MovePlayerPacket6handleERKN6RakNet10RakNetGUIDEP16NetEventCallback|
|PlayerEquipmentPacket::handle|No|(RakNet::RakNetGUID const&, NetEventCallback*)|IDK|_ZN21PlayerEquipmentPacket6handleERKN6RakNet10RakNetGUIDEP16NetEventCallback|
|DropItemPacket::handle|No|(RakNet::RakNetGUID const&, NetEventCallback*)|IDK|_ZN14DropItemPacket6handleERKN6RakNet10RakNetGUIDEP16NetEventCallback|
|EntityEventPacket::handle|No|(RakNet::RakNetGUID const&, NetEventCallback*)|IDK|_ZN17EntityEventPacket6handleERKN6RakNet10RakNetGUIDEP16NetEventCallback|
|AnimatePacket::handle|No|(RakNet::RakNetGUID const&, NetEventCallback*)|IDK|_ZN13AnimatePacket6handleERKN6RakNet10RakNetGUIDEP16NetEventCallback|
|PlayerInputPacket::handle|No|(RakNet::RakNetGUID const&, NetEventCallback*)|IDK|_ZN17PlayerInputPacket6handleERKN6RakNet10RakNetGUIDEP16NetEventCallback|
|LocalPlayer::take|No|(Entity*, int)|IDK|_ZN11LocalPlayer4takeEP6Entityi|
|LocalPlayer::isSneaking|No|()|IDK|_ZN11LocalPlayer10isSneakingEv|
|LocalPlayer::setPos|No|(Vec3 const&)|IDK|_ZN11LocalPlayer6setPosERK4Vec3|
|LocalPlayer::isLocalPlayer|No|()|IDK|_ZN11LocalPlayer13isLocalPlayerEv|
|LocalPlayer::refreshContainer|No|(BaseContainerMenu*, std::vector<ItemInstance, std::allocator<ItemInstance> > const&)|IDK|_ZN11LocalPlayer16refreshContainerEP17BaseContainerMenuRKSt6vectorI12ItemInstanceSaIS3_EE|
|non-virtual thunk to LocalPlayer::refreshContainer|No|(BaseContainerMenu*, std::vector<ItemInstance, std::allocator<ItemInstance> > const&)|IDK|_ZThn3384_N11LocalPlayer16refreshContainerEP17BaseContainerMenuRKSt6vectorI12ItemInstanceSaIS3_EE|
|EntityDataPacket::handle|No|(RakNet::RakNetGUID const&, NetEventCallback*)|IDK|_ZN16EntityDataPacket6handleERKN6RakNet10RakNetGUIDEP16NetEventCallback|
|ChestTileEntity::getContainerSize|No|() const|IDK|_ZNK15ChestTileEntity16getContainerSizeEv|
|non-virtual thunk to ChestTileEntity::getContainerSize|No|() const|IDK|_ZThn96_NK15ChestTileEntity16getContainerSizeEv|
|ChestTileEntity::getItem|No|(int)|IDK|_ZN15ChestTileEntity7getItemEi|
|non-virtual thunk to ChestTileEntity::getItem|No|(int)|IDK|_ZThn96_N15ChestTileEntity7getItemEi|
|ChestTileEntity::onUpdatePacket|No|(CompoundTag*)|IDK|_ZN15ChestTileEntity14onUpdatePacketEP11CompoundTag|
|ChestTileEntity::getMaxStackSize|No|() const|IDK|_ZNK15ChestTileEntity15getMaxStackSizeEv|
|non-virtual thunk to ChestTileEntity::getMaxStackSize|No|() const|IDK|_ZThn96_NK15ChestTileEntity15getMaxStackSizeEv|
|ChestTileEntity::triggerEvent|No|(int, int)|IDK|_ZN15ChestTileEntity12triggerEventEii|
|HugeMushroomTile::getResource|No|(int, Random*)|IDK|_ZN16HugeMushroomTile11getResourceEiP6Random|
|PigZombie::getBaseSpeed|No|()|IDK|_ZN9PigZombie12getBaseSpeedEv|
|PigZombie::useNewAi|No|()|IDK|_ZN9PigZombie8useNewAiEv|
|PigZombie::getAmbientSound|No|()|IDK|_ZN9PigZombie15getAmbientSoundEv|
|PigZombie::interactWithPlayer|No|(Player*)|IDK|_ZN9PigZombie18interactWithPlayerEP6Player|
|PigZombie::getDeathLoot|No|()|IDK|_ZN9PigZombie12getDeathLootEv|
|PigZombie::getCarriedItem|No|()|IDK|_ZN9PigZombie14getCarriedItemEv|
|PigZombie::getEntityTypeId|No|() const|IDK|_ZNK9PigZombie15getEntityTypeIdEv|
|PigZombie::getAttackTime|No|()|IDK|_ZN9PigZombie13getAttackTimeEv|
|TileEntityRenderer::onNewLevel|No|(Level*)|IDK|_ZN18TileEntityRenderer10onNewLevelEP5Level|
|EndTag::load|No|(IDataInput*)|IDK|_ZN6EndTag4loadEP10IDataInput|
|EndTag::write|No|(IDataOutput*)|IDK|_ZN6EndTag5writeEP11IDataOutput|
|EndTag::getId|No|() const|IDK|_ZNK6EndTag5getIdEv|
|CreeperModel::setupAnim|No|(float, float, float, float, float, float)|IDK|_ZN12CreeperModel9setupAnimEffffff|
|SpiderModel::Eyes::setupAnim|No|(float, float, float, float, float, float)|IDK|_ZN11SpiderModel4Eyes9setupAnimEffffff|
|SpiderModel::setupAnim|No|(float, float, float, float, float, float)|IDK|_ZN11SpiderModel9setupAnimEffffff|
|SpiderRenderer::getFlipDegrees|No|(Mob*)|IDK|_ZN14SpiderRenderer14getFlipDegreesEP3Mob|
|SilverfishModel::setupAnim|No|(float, float, float, float, float, float)|IDK|_ZN15SilverfishModel9setupAnimEffffff|
|SilverfishRenderer::getFlipDegrees|No|(Mob*)|IDK|_ZN18SilverfishRenderer14getFlipDegreesEP3Mob|
|SilverfishRenderer::prepareArmor|No|(Mob*, int, float)|IDK|_ZN18SilverfishRenderer12prepareArmorEP3Mobif|
|LoginOption::setupPositions|No|()|IDK|_ZN11LoginOption14setupPositionsEv|
|RandomLookAroundGoal::canContinueToUse|No|()|IDK|_ZN20RandomLookAroundGoal16canContinueToUseEv|
|ItemEntity::hurt|No|(Entity*, int)|IDK|_ZN10ItemEntity4hurtEP6Entityi|
|ItemEntity::burn|No|(int)|IDK|_ZN10ItemEntity4burnEi|
|ItemEntity::isItemEntity|No|()|IDK|_ZN10ItemEntity12isItemEntityEv|
|ItemEntity::getEntityTypeId|No|() const|IDK|_ZNK10ItemEntity15getEntityTypeIdEv|
|Sapling::getSpawnResourcesAuxValue|No|(int)|IDK|_ZN7Sapling25getSpawnResourcesAuxValueEi|
|Sapling::getTexture|No|(signed char, int)|IDK|_ZN7Sapling10getTextureEai|
|WallClimberPathNavigation::hasDestination|No|()|IDK|_ZN25WallClimberPathNavigation14hasDestinationEv|
|PaneCraftingScreen::renderGameBehind|No|()|IDK|_ZN18PaneCraftingScreen16renderGameBehindEv|
|PaneCraftingScreen::closeOnPlayerHurt|No|()|IDK|_ZN18PaneCraftingScreen17closeOnPlayerHurtEv|
|PaneCraftingScreen::getItems|No|(ItemPane const*)|IDK|_ZN18PaneCraftingScreen8getItemsEPK8ItemPane|
|non-virtual thunk to PaneCraftingScreen::getItems|No|(ItemPane const*)|IDK|_ZThn132_N18PaneCraftingScreen8getItemsEPK8ItemPane|
|VillagerModel::setupAnim|No|(float, float, float, float, float, float)|IDK|_ZN13VillagerModel9setupAnimEffffff|
|std::unique_ptr<EntityRenderDispatcher, std::default_delete<EntityRenderDispatcher> >::~unique_ptr|No|()|IDK|_ZNSt10unique_ptrI22EntityRenderDispatcherSt14default_deleteIS0_EED2Ev|
|std::unique_ptr<EntityRenderDispatcher, std::default_delete<EntityRenderDispatcher> >::~unique_ptr|No|()|IDK|_ZNSt10unique_ptrI22EntityRenderDispatcherSt14default_deleteIS0_EED1Ev|
|std::_Sp_counted_ptr<BaseRailTile::Rail*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIPN12BaseRailTile4RailELN9__gnu_cxx12_Lock_policyE2EED2Ev|
|std::_Sp_counted_ptr<BaseRailTile::Rail*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIPN12BaseRailTile4RailELN9__gnu_cxx12_Lock_policyE2EED1Ev|
|std::_Sp_counted_ptr<TextureAtlas*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP12TextureAtlasLN9__gnu_cxx12_Lock_policyE2EED2Ev|
|std::_Sp_counted_ptr<TextureAtlas*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP12TextureAtlasLN9__gnu_cxx12_Lock_policyE2EED1Ev|
|std::_Sp_counted_ptr<ItemInstance*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP12ItemInstanceLN9__gnu_cxx12_Lock_policyE2EED2Ev|
|std::_Sp_counted_ptr<ItemInstance*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP12ItemInstanceLN9__gnu_cxx12_Lock_policyE2EED1Ev|
|std::_Sp_counted_ptr<CItem*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP5CItemLN9__gnu_cxx12_Lock_policyE2EED2Ev|
|std::_Sp_counted_ptr<CItem*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP5CItemLN9__gnu_cxx12_Lock_policyE2EED1Ev|
|std::_Sp_counted_ptr<BlankButton*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP11BlankButtonLN9__gnu_cxx12_Lock_policyE2EED2Ev|
|std::_Sp_counted_ptr<BlankButton*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP11BlankButtonLN9__gnu_cxx12_Lock_policyE2EED1Ev|
|std::_Sp_counted_ptr<Label*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP5LabelLN9__gnu_cxx12_Lock_policyE2EED2Ev|
|std::_Sp_counted_ptr<Label*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP5LabelLN9__gnu_cxx12_Lock_policyE2EED1Ev|
|std::_Sp_counted_ptr<Touch::TButton*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIPN5Touch7TButtonELN9__gnu_cxx12_Lock_policyE2EED2Ev|
|std::_Sp_counted_ptr<Touch::TButton*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIPN5Touch7TButtonELN9__gnu_cxx12_Lock_policyE2EED1Ev|
|std::_Sp_counted_ptr<VoronoiZoom*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP11VoronoiZoomLN9__gnu_cxx12_Lock_policyE2EED2Ev|
|std::_Sp_counted_ptr<VoronoiZoom*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP11VoronoiZoomLN9__gnu_cxx12_Lock_policyE2EED1Ev|
|std::_Sp_counted_ptr<RiverMixerLayer*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP15RiverMixerLayerLN9__gnu_cxx12_Lock_policyE2EED2Ev|
|std::_Sp_counted_ptr<RiverMixerLayer*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP15RiverMixerLayerLN9__gnu_cxx12_Lock_policyE2EED1Ev|
|std::_Sp_counted_ptr<ShoreLayer*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP10ShoreLayerLN9__gnu_cxx12_Lock_policyE2EED2Ev|
|std::_Sp_counted_ptr<ShoreLayer*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP10ShoreLayerLN9__gnu_cxx12_Lock_policyE2EED1Ev|
|std::_Sp_counted_ptr<RareBiomeSpotLayer*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP18RareBiomeSpotLayerLN9__gnu_cxx12_Lock_policyE2EED2Ev|
|std::_Sp_counted_ptr<RareBiomeSpotLayer*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP18RareBiomeSpotLayerLN9__gnu_cxx12_Lock_policyE2EED1Ev|
|std::_Sp_counted_ptr<SmoothLayer*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP11SmoothLayerLN9__gnu_cxx12_Lock_policyE2EED2Ev|
|std::_Sp_counted_ptr<SmoothLayer*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP11SmoothLayerLN9__gnu_cxx12_Lock_policyE2EED1Ev|
|std::_Sp_counted_ptr<RiverLayer*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP10RiverLayerLN9__gnu_cxx12_Lock_policyE2EED2Ev|
|std::_Sp_counted_ptr<RiverLayer*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP10RiverLayerLN9__gnu_cxx12_Lock_policyE2EED1Ev|
|std::_Sp_counted_ptr<RegionHillsLayer*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP16RegionHillsLayerLN9__gnu_cxx12_Lock_policyE2EED2Ev|
|std::_Sp_counted_ptr<RegionHillsLayer*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP16RegionHillsLayerLN9__gnu_cxx12_Lock_policyE2EED1Ev|
|std::_Sp_counted_ptr<BiomeEdgeLayer*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP14BiomeEdgeLayerLN9__gnu_cxx12_Lock_policyE2EED2Ev|
|std::_Sp_counted_ptr<BiomeEdgeLayer*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP14BiomeEdgeLayerLN9__gnu_cxx12_Lock_policyE2EED1Ev|
|std::_Sp_counted_ptr<BiomeInitLayer*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP14BiomeInitLayerLN9__gnu_cxx12_Lock_policyE2EED2Ev|
|std::_Sp_counted_ptr<BiomeInitLayer*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP14BiomeInitLayerLN9__gnu_cxx12_Lock_policyE2EED1Ev|
|std::_Sp_counted_ptr<RiverInitLayer*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP14RiverInitLayerLN9__gnu_cxx12_Lock_policyE2EED2Ev|
|std::_Sp_counted_ptr<RiverInitLayer*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP14RiverInitLayerLN9__gnu_cxx12_Lock_policyE2EED1Ev|
|std::_Sp_counted_ptr<AddDeepOceanLayer*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP17AddDeepOceanLayerLN9__gnu_cxx12_Lock_policyE2EED2Ev|
|std::_Sp_counted_ptr<AddDeepOceanLayer*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP17AddDeepOceanLayerLN9__gnu_cxx12_Lock_policyE2EED1Ev|
|std::_Sp_counted_ptr<AddMushroomIslandLayer*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP22AddMushroomIslandLayerLN9__gnu_cxx12_Lock_policyE2EED2Ev|
|std::_Sp_counted_ptr<AddMushroomIslandLayer*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP22AddMushroomIslandLayerLN9__gnu_cxx12_Lock_policyE2EED1Ev|
|std::_Sp_counted_ptr<AddEdgeLayer*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP12AddEdgeLayerLN9__gnu_cxx12_Lock_policyE2EED2Ev|
|std::_Sp_counted_ptr<AddEdgeLayer*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP12AddEdgeLayerLN9__gnu_cxx12_Lock_policyE2EED1Ev|
|std::_Sp_counted_ptr<AddSnowLayer*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP12AddSnowLayerLN9__gnu_cxx12_Lock_policyE2EED2Ev|
|std::_Sp_counted_ptr<AddSnowLayer*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP12AddSnowLayerLN9__gnu_cxx12_Lock_policyE2EED1Ev|
|std::_Sp_counted_ptr<RemoveTooMuchOceanLayer*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP23RemoveTooMuchOceanLayerLN9__gnu_cxx12_Lock_policyE2EED2Ev|
|std::_Sp_counted_ptr<RemoveTooMuchOceanLayer*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP23RemoveTooMuchOceanLayerLN9__gnu_cxx12_Lock_policyE2EED1Ev|
|std::_Sp_counted_ptr<AddIslandLayer*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP14AddIslandLayerLN9__gnu_cxx12_Lock_policyE2EED2Ev|
|std::_Sp_counted_ptr<AddIslandLayer*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP14AddIslandLayerLN9__gnu_cxx12_Lock_policyE2EED1Ev|
|std::_Sp_counted_ptr<FuzzyZoomLayer*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP14FuzzyZoomLayerLN9__gnu_cxx12_Lock_policyE2EED2Ev|
|std::_Sp_counted_ptr<FuzzyZoomLayer*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP14FuzzyZoomLayerLN9__gnu_cxx12_Lock_policyE2EED1Ev|
|std::_Sp_counted_ptr<IslandLayer*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP11IslandLayerLN9__gnu_cxx12_Lock_policyE2EED2Ev|
|std::_Sp_counted_ptr<IslandLayer*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP11IslandLayerLN9__gnu_cxx12_Lock_policyE2EED1Ev|
|RandomLookAroundGoal::~RandomLookAroundGoal|No|()|IDK|_ZN20RandomLookAroundGoalD2Ev|
|RandomLookAroundGoal::~RandomLookAroundGoal|No|()|IDK|_ZN20RandomLookAroundGoalD1Ev|
|EntityDataPacket::~EntityDataPacket|No|()|IDK|_ZN16EntityDataPacketD2Ev|
|vtable for EntityDataPacket|No|(undefined|IDK|_ZTV16EntityDataPacket|
|EntityDataPacket::~EntityDataPacket|No|()|IDK|_ZN16EntityDataPacketD1Ev|
|PlayerInputPacket::~PlayerInputPacket|No|()|IDK|_ZN17PlayerInputPacketD2Ev|
|PlayerInputPacket::~PlayerInputPacket|No|()|IDK|_ZN17PlayerInputPacketD1Ev|
|AnimatePacket::~AnimatePacket|No|()|IDK|_ZN13AnimatePacketD2Ev|
|AnimatePacket::~AnimatePacket|No|()|IDK|_ZN13AnimatePacketD1Ev|
|EntityEventPacket::~EntityEventPacket|No|()|IDK|_ZN17EntityEventPacketD2Ev|
|EntityEventPacket::~EntityEventPacket|No|()|IDK|_ZN17EntityEventPacketD1Ev|
|DropItemPacket::~DropItemPacket|No|()|IDK|_ZN14DropItemPacketD2Ev|
|DropItemPacket::~DropItemPacket|No|()|IDK|_ZN14DropItemPacketD1Ev|
|PlayerEquipmentPacket::~PlayerEquipmentPacket|No|()|IDK|_ZN21PlayerEquipmentPacketD2Ev|
|PlayerEquipmentPacket::~PlayerEquipmentPacket|No|()|IDK|_ZN21PlayerEquipmentPacketD1Ev|
|MovePlayerPacket::~MovePlayerPacket|No|()|IDK|_ZN16MovePlayerPacketD2Ev|
|MovePlayerPacket::~MovePlayerPacket|No|()|IDK|_ZN16MovePlayerPacketD1Ev|
|ContainerClosePacket::~ContainerClosePacket|No|()|IDK|_ZN20ContainerClosePacketD2Ev|
|ContainerClosePacket::~ContainerClosePacket|No|()|IDK|_ZN20ContainerClosePacketD1Ev|
|SHStraightStairsDown::~SHStraightStairsDown|No|()|IDK|_ZN20SHStraightStairsDownD2Ev|
|SHStraightStairsDown::~SHStraightStairsDown|No|()|IDK|_ZN20SHStraightStairsDownD1Ev|
|SHStraight::~SHStraight|No|()|IDK|_ZN10SHStraightD2Ev|
|SHStraight::~SHStraight|No|()|IDK|_ZN10SHStraightD1Ev|
|SHRoomCrossing::~SHRoomCrossing|No|()|IDK|_ZN14SHRoomCrossingD2Ev|
|SHRoomCrossing::~SHRoomCrossing|No|()|IDK|_ZN14SHRoomCrossingD1Ev|
|SHPrisonHall::~SHPrisonHall|No|()|IDK|_ZN12SHPrisonHallD2Ev|
|SHPrisonHall::~SHPrisonHall|No|()|IDK|_ZN12SHPrisonHallD1Ev|
|SHPortalRoom::~SHPortalRoom|No|()|IDK|_ZN12SHPortalRoomD2Ev|
|SHPortalRoom::~SHPortalRoom|No|()|IDK|_ZN12SHPortalRoomD1Ev|
|SHLibrary::~SHLibrary|No|()|IDK|_ZN9SHLibraryD2Ev|
|SHLibrary::~SHLibrary|No|()|IDK|_ZN9SHLibraryD1Ev|
|SHRightTurn::~SHRightTurn|No|()|IDK|_ZN11SHRightTurnD2Ev|
|SHRightTurn::~SHRightTurn|No|()|IDK|_ZN11SHRightTurnD1Ev|
|SHLeftTurn::~SHLeftTurn|No|()|IDK|_ZN10SHLeftTurnD2Ev|
|SHLeftTurn::~SHLeftTurn|No|()|IDK|_ZN10SHLeftTurnD1Ev|
|SHFiveCrossing::~SHFiveCrossing|No|()|IDK|_ZN14SHFiveCrossingD2Ev|
|SHFiveCrossing::~SHFiveCrossing|No|()|IDK|_ZN14SHFiveCrossingD1Ev|
|SHFillerCorridor::~SHFillerCorridor|No|()|IDK|_ZN16SHFillerCorridorD2Ev|
|SHFillerCorridor::~SHFillerCorridor|No|()|IDK|_ZN16SHFillerCorridorD1Ev|
|SHChestCorridor::~SHChestCorridor|No|()|IDK|_ZN15SHChestCorridorD2Ev|
|SHChestCorridor::~SHChestCorridor|No|()|IDK|_ZN15SHChestCorridorD1Ev|
|SmoothStoneSelector::~SmoothStoneSelector|No|()|IDK|_ZN19SmoothStoneSelectorD2Ev|
|SmoothStoneSelector::~SmoothStoneSelector|No|()|IDK|_ZN19SmoothStoneSelectorD1Ev|
|StraightRoad::~StraightRoad|No|()|IDK|_ZN12StraightRoadD2Ev|
|StraightRoad::~StraightRoad|No|()|IDK|_ZN12StraightRoadD1Ev|
|LightPost::~LightPost|No|()|IDK|_ZN9LightPostD2Ev|
|LightPost::~LightPost|No|()|IDK|_ZN9LightPostD1Ev|
|TwoRoomHouse::~TwoRoomHouse|No|()|IDK|_ZN12TwoRoomHouseD2Ev|
|TwoRoomHouse::~TwoRoomHouse|No|()|IDK|_ZN12TwoRoomHouseD1Ev|
|Smithy::~Smithy|No|()|IDK|_ZN6SmithyD2Ev|
|Smithy::~Smithy|No|()|IDK|_ZN6SmithyD1Ev|
|Farmland::~Farmland|No|()|IDK|_ZN8FarmlandD2Ev|
|Farmland::~Farmland|No|()|IDK|_ZN8FarmlandD1Ev|
|DoubleFarmland::~DoubleFarmland|No|()|IDK|_ZN14DoubleFarmlandD2Ev|
|DoubleFarmland::~DoubleFarmland|No|()|IDK|_ZN14DoubleFarmlandD1Ev|
|PigHouse::~PigHouse|No|()|IDK|_ZN8PigHouseD2Ev|
|PigHouse::~PigHouse|No|()|IDK|_ZN8PigHouseD1Ev|
|SmallHut::~SmallHut|No|()|IDK|_ZN8SmallHutD2Ev|
|SmallHut::~SmallHut|No|()|IDK|_ZN8SmallHutD1Ev|
|BookHouse::~BookHouse|No|()|IDK|_ZN9BookHouseD2Ev|
|BookHouse::~BookHouse|No|()|IDK|_ZN9BookHouseD1Ev|
|SmallTemple::~SmallTemple|No|()|IDK|_ZN11SmallTempleD2Ev|
|SmallTemple::~SmallTemple|No|()|IDK|_ZN11SmallTempleD1Ev|
|SimpleHouse::~SimpleHouse|No|()|IDK|_ZN11SimpleHouseD2Ev|
|SimpleHouse::~SimpleHouse|No|()|IDK|_ZN11SimpleHouseD1Ev|
|HurtByTargetGoal::~HurtByTargetGoal|No|()|IDK|_ZN16HurtByTargetGoalD2Ev|
|HurtByTargetGoal::~HurtByTargetGoal|No|()|IDK|_ZN16HurtByTargetGoalD1Ev|
|DataItem2<TilePos>::~DataItem2|No|()|IDK|_ZN9DataItem2I7TilePosED2Ev|
|DataItem2<TilePos>::~DataItem2|No|()|IDK|_ZN9DataItem2I7TilePosED1Ev|
|DataItem2<ItemInstance>::~DataItem2|No|()|IDK|_ZN9DataItem2I12ItemInstanceED2Ev|
|DataItem2<ItemInstance>::~DataItem2|No|()|IDK|_ZN9DataItem2I12ItemInstanceED1Ev|
|DataItem2<short>::~DataItem2|No|()|IDK|_ZN9DataItem2IsED2Ev|
|DataItem2<short>::~DataItem2|No|()|IDK|_ZN9DataItem2IsED1Ev|
|OffsetPosTranslator::~OffsetPosTranslator|No|()|IDK|_ZN19OffsetPosTranslatorD2Ev|
|OffsetPosTranslator::~OffsetPosTranslator|No|()|IDK|_ZN19OffsetPosTranslatorD1Ev|
|SetHealthPacket::~SetHealthPacket|No|()|IDK|_ZN15SetHealthPacketD2Ev|
|SetHealthPacket::~SetHealthPacket|No|()|IDK|_ZN15SetHealthPacketD1Ev|
|MineshaftStairs::~MineshaftStairs|No|()|IDK|_ZN15MineshaftStairsD2Ev|
|MineshaftStairs::~MineshaftStairs|No|()|IDK|_ZN15MineshaftStairsD1Ev|
|MineshaftCrossing::~MineshaftCrossing|No|()|IDK|_ZN17MineshaftCrossingD2Ev|
|MineshaftCrossing::~MineshaftCrossing|No|()|IDK|_ZN17MineshaftCrossingD1Ev|
|MineshaftCorridor::~MineshaftCorridor|No|()|IDK|_ZN17MineshaftCorridorD2Ev|
|MineshaftCorridor::~MineshaftCorridor|No|()|IDK|_ZN17MineshaftCorridorD1Ev|
|std::_Sp_counted_ptr<BaseRailTile::Rail*, |No|(__gnu_cxx::_Lock_policy)2>::_M_get_deleter|IDK|_ZNSt15_Sp_counted_ptrIPN12BaseRailTile4RailELN9__gnu_cxx12_Lock_policyE2EE14_M_get_deleterERKSt9type_info|
|std::_Sp_counted_ptr<TextureAtlas*, |No|(__gnu_cxx::_Lock_policy)2>::_M_get_deleter|IDK|_ZNSt15_Sp_counted_ptrIP12TextureAtlasLN9__gnu_cxx12_Lock_policyE2EE14_M_get_deleterERKSt9type_info|
|std::_Sp_counted_ptr<ItemInstance*, |No|(__gnu_cxx::_Lock_policy)2>::_M_get_deleter|IDK|_ZNSt15_Sp_counted_ptrIP12ItemInstanceLN9__gnu_cxx12_Lock_policyE2EE14_M_get_deleterERKSt9type_info|
|std::_Sp_counted_ptr<CItem*, |No|(__gnu_cxx::_Lock_policy)2>::_M_get_deleter|IDK|_ZNSt15_Sp_counted_ptrIP5CItemLN9__gnu_cxx12_Lock_policyE2EE14_M_get_deleterERKSt9type_info|
|std::_Sp_counted_ptr<BlankButton*, |No|(__gnu_cxx::_Lock_policy)2>::_M_dispose|IDK|_ZNSt15_Sp_counted_ptrIP11BlankButtonLN9__gnu_cxx12_Lock_policyE2EE10_M_disposeEv|
|std::_Sp_counted_ptr<BlankButton*, |No|(__gnu_cxx::_Lock_policy)2>::_M_get_deleter|IDK|_ZNSt15_Sp_counted_ptrIP11BlankButtonLN9__gnu_cxx12_Lock_policyE2EE14_M_get_deleterERKSt9type_info|
|std::_Sp_counted_ptr<Label*, |No|(__gnu_cxx::_Lock_policy)2>::_M_dispose|IDK|_ZNSt15_Sp_counted_ptrIP5LabelLN9__gnu_cxx12_Lock_policyE2EE10_M_disposeEv|
|std::_Sp_counted_ptr<Label*, |No|(__gnu_cxx::_Lock_policy)2>::_M_get_deleter|IDK|_ZNSt15_Sp_counted_ptrIP5LabelLN9__gnu_cxx12_Lock_policyE2EE14_M_get_deleterERKSt9type_info|
|std::_Sp_counted_ptr<Touch::TButton*, |No|(__gnu_cxx::_Lock_policy)2>::_M_dispose|IDK|_ZNSt15_Sp_counted_ptrIPN5Touch7TButtonELN9__gnu_cxx12_Lock_policyE2EE10_M_disposeEv|
|std::_Sp_counted_ptr<Touch::TButton*, |No|(__gnu_cxx::_Lock_policy)2>::_M_get_deleter|IDK|_ZNSt15_Sp_counted_ptrIPN5Touch7TButtonELN9__gnu_cxx12_Lock_policyE2EE14_M_get_deleterERKSt9type_info|
|std::_Sp_counted_ptr<VoronoiZoom*, |No|(__gnu_cxx::_Lock_policy)2>::_M_dispose|IDK|_ZNSt15_Sp_counted_ptrIP11VoronoiZoomLN9__gnu_cxx12_Lock_policyE2EE10_M_disposeEv|
|std::_Sp_counted_ptr<VoronoiZoom*, |No|(__gnu_cxx::_Lock_policy)2>::_M_get_deleter|IDK|_ZNSt15_Sp_counted_ptrIP11VoronoiZoomLN9__gnu_cxx12_Lock_policyE2EE14_M_get_deleterERKSt9type_info|
|std::_Sp_counted_ptr<RiverMixerLayer*, |No|(__gnu_cxx::_Lock_policy)2>::_M_dispose|IDK|_ZNSt15_Sp_counted_ptrIP15RiverMixerLayerLN9__gnu_cxx12_Lock_policyE2EE10_M_disposeEv|
|std::_Sp_counted_ptr<RiverMixerLayer*, |No|(__gnu_cxx::_Lock_policy)2>::_M_get_deleter|IDK|_ZNSt15_Sp_counted_ptrIP15RiverMixerLayerLN9__gnu_cxx12_Lock_policyE2EE14_M_get_deleterERKSt9type_info|
|std::_Sp_counted_ptr<ShoreLayer*, |No|(__gnu_cxx::_Lock_policy)2>::_M_dispose|IDK|_ZNSt15_Sp_counted_ptrIP10ShoreLayerLN9__gnu_cxx12_Lock_policyE2EE10_M_disposeEv|
|std::_Sp_counted_ptr<ShoreLayer*, |No|(__gnu_cxx::_Lock_policy)2>::_M_get_deleter|IDK|_ZNSt15_Sp_counted_ptrIP10ShoreLayerLN9__gnu_cxx12_Lock_policyE2EE14_M_get_deleterERKSt9type_info|
|std::_Sp_counted_ptr<RareBiomeSpotLayer*, |No|(__gnu_cxx::_Lock_policy)2>::_M_dispose|IDK|_ZNSt15_Sp_counted_ptrIP18RareBiomeSpotLayerLN9__gnu_cxx12_Lock_policyE2EE10_M_disposeEv|
|std::_Sp_counted_ptr<RareBiomeSpotLayer*, |No|(__gnu_cxx::_Lock_policy)2>::_M_get_deleter|IDK|_ZNSt15_Sp_counted_ptrIP18RareBiomeSpotLayerLN9__gnu_cxx12_Lock_policyE2EE14_M_get_deleterERKSt9type_info|
|std::_Sp_counted_ptr<SmoothLayer*, |No|(__gnu_cxx::_Lock_policy)2>::_M_dispose|IDK|_ZNSt15_Sp_counted_ptrIP11SmoothLayerLN9__gnu_cxx12_Lock_policyE2EE10_M_disposeEv|
|std::_Sp_counted_ptr<SmoothLayer*, |No|(__gnu_cxx::_Lock_policy)2>::_M_get_deleter|IDK|_ZNSt15_Sp_counted_ptrIP11SmoothLayerLN9__gnu_cxx12_Lock_policyE2EE14_M_get_deleterERKSt9type_info|
|std::_Sp_counted_ptr<RiverLayer*, |No|(__gnu_cxx::_Lock_policy)2>::_M_dispose|IDK|_ZNSt15_Sp_counted_ptrIP10RiverLayerLN9__gnu_cxx12_Lock_policyE2EE10_M_disposeEv|
|std::_Sp_counted_ptr<RiverLayer*, |No|(__gnu_cxx::_Lock_policy)2>::_M_get_deleter|IDK|_ZNSt15_Sp_counted_ptrIP10RiverLayerLN9__gnu_cxx12_Lock_policyE2EE14_M_get_deleterERKSt9type_info|
|std::_Sp_counted_ptr<RegionHillsLayer*, |No|(__gnu_cxx::_Lock_policy)2>::_M_dispose|IDK|_ZNSt15_Sp_counted_ptrIP16RegionHillsLayerLN9__gnu_cxx12_Lock_policyE2EE10_M_disposeEv|
|std::_Sp_counted_ptr<RegionHillsLayer*, |No|(__gnu_cxx::_Lock_policy)2>::_M_get_deleter|IDK|_ZNSt15_Sp_counted_ptrIP16RegionHillsLayerLN9__gnu_cxx12_Lock_policyE2EE14_M_get_deleterERKSt9type_info|
|std::_Sp_counted_ptr<BiomeEdgeLayer*, |No|(__gnu_cxx::_Lock_policy)2>::_M_dispose|IDK|_ZNSt15_Sp_counted_ptrIP14BiomeEdgeLayerLN9__gnu_cxx12_Lock_policyE2EE10_M_disposeEv|
|std::_Sp_counted_ptr<BiomeEdgeLayer*, |No|(__gnu_cxx::_Lock_policy)2>::_M_get_deleter|IDK|_ZNSt15_Sp_counted_ptrIP14BiomeEdgeLayerLN9__gnu_cxx12_Lock_policyE2EE14_M_get_deleterERKSt9type_info|
|std::_Sp_counted_ptr<BiomeInitLayer*, |No|(__gnu_cxx::_Lock_policy)2>::_M_dispose|IDK|_ZNSt15_Sp_counted_ptrIP14BiomeInitLayerLN9__gnu_cxx12_Lock_policyE2EE10_M_disposeEv|
|std::_Sp_counted_ptr<BiomeInitLayer*, |No|(__gnu_cxx::_Lock_policy)2>::_M_get_deleter|IDK|_ZNSt15_Sp_counted_ptrIP14BiomeInitLayerLN9__gnu_cxx12_Lock_policyE2EE14_M_get_deleterERKSt9type_info|
|std::_Sp_counted_ptr<RiverInitLayer*, |No|(__gnu_cxx::_Lock_policy)2>::_M_dispose|IDK|_ZNSt15_Sp_counted_ptrIP14RiverInitLayerLN9__gnu_cxx12_Lock_policyE2EE10_M_disposeEv|
|std::_Sp_counted_ptr<RiverInitLayer*, |No|(__gnu_cxx::_Lock_policy)2>::_M_get_deleter|IDK|_ZNSt15_Sp_counted_ptrIP14RiverInitLayerLN9__gnu_cxx12_Lock_policyE2EE14_M_get_deleterERKSt9type_info|
|std::_Sp_counted_ptr<AddDeepOceanLayer*, |No|(__gnu_cxx::_Lock_policy)2>::_M_dispose|IDK|_ZNSt15_Sp_counted_ptrIP17AddDeepOceanLayerLN9__gnu_cxx12_Lock_policyE2EE10_M_disposeEv|
|std::_Sp_counted_ptr<AddDeepOceanLayer*, |No|(__gnu_cxx::_Lock_policy)2>::_M_get_deleter|IDK|_ZNSt15_Sp_counted_ptrIP17AddDeepOceanLayerLN9__gnu_cxx12_Lock_policyE2EE14_M_get_deleterERKSt9type_info|
|std::_Sp_counted_ptr<AddMushroomIslandLayer*, |No|(__gnu_cxx::_Lock_policy)2>::_M_dispose|IDK|_ZNSt15_Sp_counted_ptrIP22AddMushroomIslandLayerLN9__gnu_cxx12_Lock_policyE2EE10_M_disposeEv|
|std::_Sp_counted_ptr<AddMushroomIslandLayer*, |No|(__gnu_cxx::_Lock_policy)2>::_M_get_deleter|IDK|_ZNSt15_Sp_counted_ptrIP22AddMushroomIslandLayerLN9__gnu_cxx12_Lock_policyE2EE14_M_get_deleterERKSt9type_info|
|std::_Sp_counted_ptr<AddEdgeLayer*, |No|(__gnu_cxx::_Lock_policy)2>::_M_dispose|IDK|_ZNSt15_Sp_counted_ptrIP12AddEdgeLayerLN9__gnu_cxx12_Lock_policyE2EE10_M_disposeEv|
|std::_Sp_counted_ptr<AddEdgeLayer*, |No|(__gnu_cxx::_Lock_policy)2>::_M_get_deleter|IDK|_ZNSt15_Sp_counted_ptrIP12AddEdgeLayerLN9__gnu_cxx12_Lock_policyE2EE14_M_get_deleterERKSt9type_info|
|std::_Sp_counted_ptr<AddSnowLayer*, |No|(__gnu_cxx::_Lock_policy)2>::_M_dispose|IDK|_ZNSt15_Sp_counted_ptrIP12AddSnowLayerLN9__gnu_cxx12_Lock_policyE2EE10_M_disposeEv|
|std::_Sp_counted_ptr<AddSnowLayer*, |No|(__gnu_cxx::_Lock_policy)2>::_M_get_deleter|IDK|_ZNSt15_Sp_counted_ptrIP12AddSnowLayerLN9__gnu_cxx12_Lock_policyE2EE14_M_get_deleterERKSt9type_info|
|std::_Sp_counted_ptr<RemoveTooMuchOceanLayer*, |No|(__gnu_cxx::_Lock_policy)2>::_M_dispose|IDK|_ZNSt15_Sp_counted_ptrIP23RemoveTooMuchOceanLayerLN9__gnu_cxx12_Lock_policyE2EE10_M_disposeEv|
|std::_Sp_counted_ptr<RemoveTooMuchOceanLayer*, |No|(__gnu_cxx::_Lock_policy)2>::_M_get_deleter|IDK|_ZNSt15_Sp_counted_ptrIP23RemoveTooMuchOceanLayerLN9__gnu_cxx12_Lock_policyE2EE14_M_get_deleterERKSt9type_info|
|std::_Sp_counted_ptr<AddIslandLayer*, |No|(__gnu_cxx::_Lock_policy)2>::_M_dispose|IDK|_ZNSt15_Sp_counted_ptrIP14AddIslandLayerLN9__gnu_cxx12_Lock_policyE2EE10_M_disposeEv|
|std::_Sp_counted_ptr<AddIslandLayer*, |No|(__gnu_cxx::_Lock_policy)2>::_M_get_deleter|IDK|_ZNSt15_Sp_counted_ptrIP14AddIslandLayerLN9__gnu_cxx12_Lock_policyE2EE14_M_get_deleterERKSt9type_info|
|std::_Sp_counted_ptr<FuzzyZoomLayer*, |No|(__gnu_cxx::_Lock_policy)2>::_M_dispose|IDK|_ZNSt15_Sp_counted_ptrIP14FuzzyZoomLayerLN9__gnu_cxx12_Lock_policyE2EE10_M_disposeEv|
|std::_Sp_counted_ptr<FuzzyZoomLayer*, |No|(__gnu_cxx::_Lock_policy)2>::_M_get_deleter|IDK|_ZNSt15_Sp_counted_ptrIP14FuzzyZoomLayerLN9__gnu_cxx12_Lock_policyE2EE14_M_get_deleterERKSt9type_info|
|std::_Sp_counted_ptr<IslandLayer*, |No|(__gnu_cxx::_Lock_policy)2>::_M_dispose|IDK|_ZNSt15_Sp_counted_ptrIP11IslandLayerLN9__gnu_cxx12_Lock_policyE2EE10_M_disposeEv|
|std::_Sp_counted_ptr<IslandLayer*, |No|(__gnu_cxx::_Lock_policy)2>::_M_get_deleter|IDK|_ZNSt15_Sp_counted_ptrIP11IslandLayerLN9__gnu_cxx12_Lock_policyE2EE14_M_get_deleterERKSt9type_info|
|BlockSelector::~BlockSelector|No|()|IDK|_ZN13BlockSelectorD0Ev|
|MineshaftPiece::~MineshaftPiece|No|()|IDK|_ZN14MineshaftPieceD0Ev|
|IConfigListener::~IConfigListener|No|()|IDK|_ZN15IConfigListenerD0Ev|
|IContainerListener::~IContainerListener|No|()|IDK|_ZN18IContainerListenerD0Ev|
|IPosTranslator::~IPosTranslator|No|()|IDK|_ZN14IPosTranslatorD0Ev|
|IItemPaneCallback::~IItemPaneCallback|No|()|IDK|_ZN17IItemPaneCallbackD0Ev|
|MonsterRoomFeature::~MonsterRoomFeature|No|()|IDK|_ZN18MonsterRoomFeatureD0Ev|
|Goal::~Goal|No|()|IDK|_ZN4GoalD0Ev|
|VillagePiece::~VillagePiece|No|()|IDK|_ZN12VillagePieceD0Ev|
|Well::~Well|No|()|IDK|_ZN4WellD0Ev|
|StrongholdPiece::~StrongholdPiece|No|()|IDK|_ZN15StrongholdPieceD0Ev|
|SHStairsDown::~SHStairsDown|No|()|IDK|_ZN12SHStairsDownD0Ev|
|std::_Sp_counted_ptr<BaseRailTile::Rail*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIPN12BaseRailTile4RailELN9__gnu_cxx12_Lock_policyE2EED0Ev|
|std::_Sp_counted_ptr<BaseRailTile::Rail*, |No|(__gnu_cxx::_Lock_policy)2>::_M_destroy|IDK|_ZNSt15_Sp_counted_ptrIPN12BaseRailTile4RailELN9__gnu_cxx12_Lock_policyE2EE10_M_destroyEv|
|std::_Sp_counted_ptr<TextureAtlas*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP12TextureAtlasLN9__gnu_cxx12_Lock_policyE2EED0Ev|
|std::_Sp_counted_ptr<TextureAtlas*, |No|(__gnu_cxx::_Lock_policy)2>::_M_destroy|IDK|_ZNSt15_Sp_counted_ptrIP12TextureAtlasLN9__gnu_cxx12_Lock_policyE2EE10_M_destroyEv|
|std::_Sp_counted_ptr<ItemInstance*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP12ItemInstanceLN9__gnu_cxx12_Lock_policyE2EED0Ev|
|std::_Sp_counted_ptr<ItemInstance*, |No|(__gnu_cxx::_Lock_policy)2>::_M_destroy|IDK|_ZNSt15_Sp_counted_ptrIP12ItemInstanceLN9__gnu_cxx12_Lock_policyE2EE10_M_destroyEv|
|std::_Sp_counted_ptr<CItem*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP5CItemLN9__gnu_cxx12_Lock_policyE2EED0Ev|
|std::_Sp_counted_ptr<CItem*, |No|(__gnu_cxx::_Lock_policy)2>::_M_destroy|IDK|_ZNSt15_Sp_counted_ptrIP5CItemLN9__gnu_cxx12_Lock_policyE2EE10_M_destroyEv|
|std::_Sp_counted_ptr<BlankButton*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP11BlankButtonLN9__gnu_cxx12_Lock_policyE2EED0Ev|
|std::_Sp_counted_ptr<BlankButton*, |No|(__gnu_cxx::_Lock_policy)2>::_M_destroy|IDK|_ZNSt15_Sp_counted_ptrIP11BlankButtonLN9__gnu_cxx12_Lock_policyE2EE10_M_destroyEv|
|std::_Sp_counted_ptr<Label*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP5LabelLN9__gnu_cxx12_Lock_policyE2EED0Ev|
|std::_Sp_counted_ptr<Label*, |No|(__gnu_cxx::_Lock_policy)2>::_M_destroy|IDK|_ZNSt15_Sp_counted_ptrIP5LabelLN9__gnu_cxx12_Lock_policyE2EE10_M_destroyEv|
|std::_Sp_counted_ptr<Touch::TButton*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIPN5Touch7TButtonELN9__gnu_cxx12_Lock_policyE2EED0Ev|
|std::_Sp_counted_ptr<Touch::TButton*, |No|(__gnu_cxx::_Lock_policy)2>::_M_destroy|IDK|_ZNSt15_Sp_counted_ptrIPN5Touch7TButtonELN9__gnu_cxx12_Lock_policyE2EE10_M_destroyEv|
|std::_Sp_counted_ptr<VoronoiZoom*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP11VoronoiZoomLN9__gnu_cxx12_Lock_policyE2EED0Ev|
|std::_Sp_counted_ptr<VoronoiZoom*, |No|(__gnu_cxx::_Lock_policy)2>::_M_destroy|IDK|_ZNSt15_Sp_counted_ptrIP11VoronoiZoomLN9__gnu_cxx12_Lock_policyE2EE10_M_destroyEv|
|std::_Sp_counted_ptr<RiverMixerLayer*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP15RiverMixerLayerLN9__gnu_cxx12_Lock_policyE2EED0Ev|
|std::_Sp_counted_ptr<RiverMixerLayer*, |No|(__gnu_cxx::_Lock_policy)2>::_M_destroy|IDK|_ZNSt15_Sp_counted_ptrIP15RiverMixerLayerLN9__gnu_cxx12_Lock_policyE2EE10_M_destroyEv|
|std::_Sp_counted_ptr<ShoreLayer*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP10ShoreLayerLN9__gnu_cxx12_Lock_policyE2EED0Ev|
|std::_Sp_counted_ptr<ShoreLayer*, |No|(__gnu_cxx::_Lock_policy)2>::_M_destroy|IDK|_ZNSt15_Sp_counted_ptrIP10ShoreLayerLN9__gnu_cxx12_Lock_policyE2EE10_M_destroyEv|
|std::_Sp_counted_ptr<RareBiomeSpotLayer*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP18RareBiomeSpotLayerLN9__gnu_cxx12_Lock_policyE2EED0Ev|
|std::_Sp_counted_ptr<RareBiomeSpotLayer*, |No|(__gnu_cxx::_Lock_policy)2>::_M_destroy|IDK|_ZNSt15_Sp_counted_ptrIP18RareBiomeSpotLayerLN9__gnu_cxx12_Lock_policyE2EE10_M_destroyEv|
|std::_Sp_counted_ptr<SmoothLayer*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP11SmoothLayerLN9__gnu_cxx12_Lock_policyE2EED0Ev|
|std::_Sp_counted_ptr<SmoothLayer*, |No|(__gnu_cxx::_Lock_policy)2>::_M_destroy|IDK|_ZNSt15_Sp_counted_ptrIP11SmoothLayerLN9__gnu_cxx12_Lock_policyE2EE10_M_destroyEv|
|std::_Sp_counted_ptr<RiverLayer*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP10RiverLayerLN9__gnu_cxx12_Lock_policyE2EED0Ev|
|std::_Sp_counted_ptr<RiverLayer*, |No|(__gnu_cxx::_Lock_policy)2>::_M_destroy|IDK|_ZNSt15_Sp_counted_ptrIP10RiverLayerLN9__gnu_cxx12_Lock_policyE2EE10_M_destroyEv|
|std::_Sp_counted_ptr<RegionHillsLayer*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP16RegionHillsLayerLN9__gnu_cxx12_Lock_policyE2EED0Ev|
|std::_Sp_counted_ptr<RegionHillsLayer*, |No|(__gnu_cxx::_Lock_policy)2>::_M_destroy|IDK|_ZNSt15_Sp_counted_ptrIP16RegionHillsLayerLN9__gnu_cxx12_Lock_policyE2EE10_M_destroyEv|
|std::_Sp_counted_ptr<BiomeEdgeLayer*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP14BiomeEdgeLayerLN9__gnu_cxx12_Lock_policyE2EED0Ev|
|std::_Sp_counted_ptr<BiomeEdgeLayer*, |No|(__gnu_cxx::_Lock_policy)2>::_M_destroy|IDK|_ZNSt15_Sp_counted_ptrIP14BiomeEdgeLayerLN9__gnu_cxx12_Lock_policyE2EE10_M_destroyEv|
|std::_Sp_counted_ptr<BiomeInitLayer*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP14BiomeInitLayerLN9__gnu_cxx12_Lock_policyE2EED0Ev|
|std::_Sp_counted_ptr<BiomeInitLayer*, |No|(__gnu_cxx::_Lock_policy)2>::_M_destroy|IDK|_ZNSt15_Sp_counted_ptrIP14BiomeInitLayerLN9__gnu_cxx12_Lock_policyE2EE10_M_destroyEv|
|std::_Sp_counted_ptr<RiverInitLayer*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP14RiverInitLayerLN9__gnu_cxx12_Lock_policyE2EED0Ev|
|std::_Sp_counted_ptr<RiverInitLayer*, |No|(__gnu_cxx::_Lock_policy)2>::_M_destroy|IDK|_ZNSt15_Sp_counted_ptrIP14RiverInitLayerLN9__gnu_cxx12_Lock_policyE2EE10_M_destroyEv|
|std::_Sp_counted_ptr<AddDeepOceanLayer*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP17AddDeepOceanLayerLN9__gnu_cxx12_Lock_policyE2EED0Ev|
|std::_Sp_counted_ptr<AddDeepOceanLayer*, |No|(__gnu_cxx::_Lock_policy)2>::_M_destroy|IDK|_ZNSt15_Sp_counted_ptrIP17AddDeepOceanLayerLN9__gnu_cxx12_Lock_policyE2EE10_M_destroyEv|
|std::_Sp_counted_ptr<AddMushroomIslandLayer*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP22AddMushroomIslandLayerLN9__gnu_cxx12_Lock_policyE2EED0Ev|
|std::_Sp_counted_ptr<AddMushroomIslandLayer*, |No|(__gnu_cxx::_Lock_policy)2>::_M_destroy|IDK|_ZNSt15_Sp_counted_ptrIP22AddMushroomIslandLayerLN9__gnu_cxx12_Lock_policyE2EE10_M_destroyEv|
|std::_Sp_counted_ptr<AddEdgeLayer*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP12AddEdgeLayerLN9__gnu_cxx12_Lock_policyE2EED0Ev|
|std::_Sp_counted_ptr<AddEdgeLayer*, |No|(__gnu_cxx::_Lock_policy)2>::_M_destroy|IDK|_ZNSt15_Sp_counted_ptrIP12AddEdgeLayerLN9__gnu_cxx12_Lock_policyE2EE10_M_destroyEv|
|std::_Sp_counted_ptr<AddSnowLayer*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP12AddSnowLayerLN9__gnu_cxx12_Lock_policyE2EED0Ev|
|std::_Sp_counted_ptr<AddSnowLayer*, |No|(__gnu_cxx::_Lock_policy)2>::_M_destroy|IDK|_ZNSt15_Sp_counted_ptrIP12AddSnowLayerLN9__gnu_cxx12_Lock_policyE2EE10_M_destroyEv|
|std::_Sp_counted_ptr<RemoveTooMuchOceanLayer*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP23RemoveTooMuchOceanLayerLN9__gnu_cxx12_Lock_policyE2EED0Ev|
|std::_Sp_counted_ptr<RemoveTooMuchOceanLayer*, |No|(__gnu_cxx::_Lock_policy)2>::_M_destroy|IDK|_ZNSt15_Sp_counted_ptrIP23RemoveTooMuchOceanLayerLN9__gnu_cxx12_Lock_policyE2EE10_M_destroyEv|
|std::_Sp_counted_ptr<AddIslandLayer*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP14AddIslandLayerLN9__gnu_cxx12_Lock_policyE2EED0Ev|
|std::_Sp_counted_ptr<AddIslandLayer*, |No|(__gnu_cxx::_Lock_policy)2>::_M_destroy|IDK|_ZNSt15_Sp_counted_ptrIP14AddIslandLayerLN9__gnu_cxx12_Lock_policyE2EE10_M_destroyEv|
|std::_Sp_counted_ptr<FuzzyZoomLayer*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP14FuzzyZoomLayerLN9__gnu_cxx12_Lock_policyE2EED0Ev|
|std::_Sp_counted_ptr<FuzzyZoomLayer*, |No|(__gnu_cxx::_Lock_policy)2>::_M_destroy|IDK|_ZNSt15_Sp_counted_ptrIP14FuzzyZoomLayerLN9__gnu_cxx12_Lock_policyE2EE10_M_destroyEv|
|std::_Sp_counted_ptr<IslandLayer*, |No|(__gnu_cxx::_Lock_policy)2>::~_Sp_counted_ptr|IDK|_ZNSt15_Sp_counted_ptrIP11IslandLayerLN9__gnu_cxx12_Lock_policyE2EED0Ev|
|std::_Sp_counted_ptr<IslandLayer*, |No|(__gnu_cxx::_Lock_policy)2>::_M_destroy|IDK|_ZNSt15_Sp_counted_ptrIP11IslandLayerLN9__gnu_cxx12_Lock_policyE2EE10_M_destroyEv|
|RandomLookAroundGoal::~RandomLookAroundGoal|No|()|IDK|_ZN20RandomLookAroundGoalD0Ev|
|PlayerInputPacket::~PlayerInputPacket|No|()|IDK|_ZN17PlayerInputPacketD0Ev|
|AnimatePacket::~AnimatePacket|No|()|IDK|_ZN13AnimatePacketD0Ev|
|EntityEventPacket::~EntityEventPacket|No|()|IDK|_ZN17EntityEventPacketD0Ev|
|DropItemPacket::~DropItemPacket|No|()|IDK|_ZN14DropItemPacketD0Ev|
|PlayerEquipmentPacket::~PlayerEquipmentPacket|No|()|IDK|_ZN21PlayerEquipmentPacketD0Ev|
|MovePlayerPacket::~MovePlayerPacket|No|()|IDK|_ZN16MovePlayerPacketD0Ev|
|ContainerClosePacket::~ContainerClosePacket|No|()|IDK|_ZN20ContainerClosePacketD0Ev|
|SHStraightStairsDown::~SHStraightStairsDown|No|()|IDK|_ZN20SHStraightStairsDownD0Ev|
|SHStraight::~SHStraight|No|()|IDK|_ZN10SHStraightD0Ev|
|SHRoomCrossing::~SHRoomCrossing|No|()|IDK|_ZN14SHRoomCrossingD0Ev|
|SHPrisonHall::~SHPrisonHall|No|()|IDK|_ZN12SHPrisonHallD0Ev|
|SHPortalRoom::~SHPortalRoom|No|()|IDK|_ZN12SHPortalRoomD0Ev|
|SHLibrary::~SHLibrary|No|()|IDK|_ZN9SHLibraryD0Ev|
|SHRightTurn::~SHRightTurn|No|()|IDK|_ZN11SHRightTurnD0Ev|
|SHLeftTurn::~SHLeftTurn|No|()|IDK|_ZN10SHLeftTurnD0Ev|
|SHFiveCrossing::~SHFiveCrossing|No|()|IDK|_ZN14SHFiveCrossingD0Ev|
|SHFillerCorridor::~SHFillerCorridor|No|()|IDK|_ZN16SHFillerCorridorD0Ev|
|SHChestCorridor::~SHChestCorridor|No|()|IDK|_ZN15SHChestCorridorD0Ev|
|SmoothStoneSelector::~SmoothStoneSelector|No|()|IDK|_ZN19SmoothStoneSelectorD0Ev|
|StraightRoad::~StraightRoad|No|()|IDK|_ZN12StraightRoadD0Ev|
|LightPost::~LightPost|No|()|IDK|_ZN9LightPostD0Ev|
|TwoRoomHouse::~TwoRoomHouse|No|()|IDK|_ZN12TwoRoomHouseD0Ev|
|Smithy::~Smithy|No|()|IDK|_ZN6SmithyD0Ev|
|Farmland::~Farmland|No|()|IDK|_ZN8FarmlandD0Ev|
|DoubleFarmland::~DoubleFarmland|No|()|IDK|_ZN14DoubleFarmlandD0Ev|
|PigHouse::~PigHouse|No|()|IDK|_ZN8PigHouseD0Ev|
|SmallHut::~SmallHut|No|()|IDK|_ZN8SmallHutD0Ev|
|BookHouse::~BookHouse|No|()|IDK|_ZN9BookHouseD0Ev|
|SmallTemple::~SmallTemple|No|()|IDK|_ZN11SmallTempleD0Ev|
|SimpleHouse::~SimpleHouse|No|()|IDK|_ZN11SimpleHouseD0Ev|
|HurtByTargetGoal::~HurtByTargetGoal|No|()|IDK|_ZN16HurtByTargetGoalD0Ev|
|DataItem2<TilePos>::~DataItem2|No|()|IDK|_ZN9DataItem2I7TilePosED0Ev|
|DataItem2<ItemInstance>::~DataItem2|No|()|IDK|_ZN9DataItem2I12ItemInstanceED0Ev|
|DataItem2<short>::~DataItem2|No|()|IDK|_ZN9DataItem2IsED0Ev|
|OffsetPosTranslator::~OffsetPosTranslator|No|()|IDK|_ZN19OffsetPosTranslatorD0Ev|
|SetHealthPacket::~SetHealthPacket|No|()|IDK|_ZN15SetHealthPacketD0Ev|
|MineshaftStairs::~MineshaftStairs|No|()|IDK|_ZN15MineshaftStairsD0Ev|
|MineshaftCrossing::~MineshaftCrossing|No|()|IDK|_ZN17MineshaftCrossingD0Ev|
|MineshaftCorridor::~MineshaftCorridor|No|()|IDK|_ZN17MineshaftCorridorD0Ev|
|std::_Sp_counted_ptr<ItemInstance*, |No|(__gnu_cxx::_Lock_policy)2>::_M_dispose|IDK|_ZNSt15_Sp_counted_ptrIP12ItemInstanceLN9__gnu_cxx12_Lock_policyE2EE10_M_disposeEv|
|EntityDataPacket::~EntityDataPacket|No|()|IDK|_ZN16EntityDataPacketD0Ev|
|MineshaftRoom::~MineshaftRoom|No|()|IDK|_ZN13MineshaftRoomD2Ev|
|vtable for MineshaftRoom|No|(undefined|IDK|_ZTV13MineshaftRoom|
|MineshaftRoom::~MineshaftRoom|No|()|IDK|_ZN13MineshaftRoomD1Ev|
|MineshaftRoom::~MineshaftRoom|No|()|IDK|_ZN13MineshaftRoomD0Ev|
|MouseDevice::~MouseDevice|No|()|IDK|_ZN11MouseDeviceD2Ev|
|MouseDevice::~MouseDevice|No|()|IDK|_ZN11MouseDeviceD1Ev|
|std::vector<int, std::allocator<int> >::~vector|No|()|IDK|_ZNSt6vectorIiSaIiEED2Ev|
|std::vector<int, std::allocator<int> >::~vector|No|()|IDK|_ZNSt6vectorIiSaIiEED1Ev|
|std::_Sp_counted_ptr<BaseRailTile::Rail*, |No|(__gnu_cxx::_Lock_policy)2>::_M_dispose|IDK|_ZNSt15_Sp_counted_ptrIPN12BaseRailTile4RailELN9__gnu_cxx12_Lock_policyE2EE10_M_disposeEv|
|std::vector<CullingStep, std::allocator<CullingStep> >::~vector|No|()|IDK|_ZNSt6vectorI11CullingStepSaIS0_EED2Ev|
|std::vector<CullingStep, std::allocator<CullingStep> >::~vector|No|()|IDK|_ZNSt6vectorI11CullingStepSaIS0_EED1Ev|
|NinecraftApp::getTextureAtlas|No|(TextureAtlasId)|IDK|_ZN12NinecraftApp15getTextureAtlasE14TextureAtlasId|
|NinecraftApp::_terrainTextureAtlas|No|(undefined|IDK|_ZN12NinecraftApp20_terrainTextureAtlasE|
|NinecraftApp::_itemsTextureAtlas|No|(undefined|IDK|_ZN12NinecraftApp18_itemsTextureAtlasE|
|PaneCraftingScreen::filterRecipes|No|(std::vector<Recipe*, std::allocator<Recipe*> >&)|IDK|_ZN18PaneCraftingScreen13filterRecipesERSt6vectorIP6RecipeSaIS2_EE|
|PodzolTile::getTypeDescriptionId|No|(int)|IDK|_ZN10PodzolTile20getTypeDescriptionIdEi|
|ChestTileEntity::getName|No|() const|IDK|_ZNK15ChestTileEntity7getNameEv|
|non-virtual thunk to ChestTileEntity::getName|No|() const|IDK|_ZThn96_NK15ChestTileEntity7getNameEv|
|PigZombie::getHurtSound|No|()|IDK|_ZN9PigZombie12getHurtSoundEv|
|PigZombie::getDeathSound|No|()|IDK|_ZN9PigZombie13getDeathSoundEv|
|EndTag::toString|No|() const|IDK|_ZNK6EndTag8toStringEv|
|ByteArrayTag::load|No|(IDataInput*)|IDK|_ZN12ByteArrayTag4loadEP10IDataInput|
|IntArrayTag::load|No|(IDataInput*)|IDK|_ZN11IntArrayTag4loadEP10IDataInput|
|DefaultMobSpawner::~DefaultMobSpawner|No|()|IDK|_ZN17DefaultMobSpawnerD2Ev|
|vtable for DefaultMobSpawner|No|(undefined|IDK|_ZTV17DefaultMobSpawner|
|DefaultMobSpawner::~DefaultMobSpawner|No|()|IDK|_ZN17DefaultMobSpawnerD1Ev|
|DefaultMobSpawner::~DefaultMobSpawner|No|()|IDK|_ZN17DefaultMobSpawnerD0Ev|
|MineshaftStairs::postProcess|No|(TileSource*, Random&, BoundingBox const&)|IDK|_ZN15MineshaftStairs11postProcessEP10TileSourceR6RandomRK11BoundingBox|
|StructurePiece::edgesLiquid|No|(TileSource*, BoundingBox const&)|IDK|_ZN14StructurePiece11edgesLiquidEP10TileSourceRK11BoundingBox|
|MineshaftRoom::postProcess|No|(TileSource*, Random&, BoundingBox const&)|IDK|_ZN13MineshaftRoom11postProcessEP10TileSourceR6RandomRK11BoundingBox|
|StructurePiece::generateUpperHalfSphere|No|(TileSource*, BoundingBox const&, int, int, int, int, int, int, int, bool)|IDK|_ZN14StructurePiece23generateUpperHalfSphereEP10TileSourceRK11BoundingBoxiiiiiiib|
|MineshaftCrossing::postProcess|No|(TileSource*, Random&, BoundingBox const&)|IDK|_ZN17MineshaftCrossing11postProcessEP10TileSourceR6RandomRK11BoundingBox|
|StructurePiece::getBlock|No|(TileSource*, int, int, int, BoundingBox const&)|IDK|_ZN14StructurePiece8getBlockEP10TileSourceiiiRK11BoundingBox|
|Snowball::~Snowball|No|()|IDK|_ZN8SnowballD2Ev|
|vtable for Throwable|No|(undefined|IDK|_ZTV9Throwable|
|Snowball::~Snowball|No|()|IDK|_ZN8SnowballD1Ev|
|Snowball::~Snowball|No|()|IDK|_ZN8SnowballD0Ev|
|ThrownEgg::~ThrownEgg|No|()|IDK|_ZN9ThrownEggD2Ev|
|ThrownEgg::~ThrownEgg|No|()|IDK|_ZN9ThrownEggD1Ev|
|ThrownEgg::~ThrownEgg|No|()|IDK|_ZN9ThrownEggD0Ev|
|HeartParticle::~HeartParticle|No|()|IDK|_ZN13HeartParticleD2Ev|
|HeartParticle::~HeartParticle|No|()|IDK|_ZN13HeartParticleD1Ev|
|HeartParticle::~HeartParticle|No|()|IDK|_ZN13HeartParticleD0Ev|
|ItemEntity::~ItemEntity|No|()|IDK|_ZN10ItemEntityD2Ev|
|vtable for ItemEntity|No|(undefined|IDK|_ZTV10ItemEntity|
|ItemEntity::~ItemEntity|No|()|IDK|_ZN10ItemEntityD1Ev|
|ItemEntity::~ItemEntity|No|()|IDK|_ZN10ItemEntityD0Ev|
|Snowball::onHit|No|(HitResult const&)|IDK|_ZN8Snowball5onHitERK9HitResult|
|ContainerClosePacket::write|No|(RakNet::BitStream*)|IDK|_ZN20ContainerClosePacket5writeEPN6RakNet9BitStreamE|
|SetHealthPacket::write|No|(RakNet::BitStream*)|IDK|_ZN15SetHealthPacket5writeEPN6RakNet9BitStreamE|
|ContainerClosePacket::read|No|(RakNet::BitStream*)|IDK|_ZN20ContainerClosePacket4readEPN6RakNet9BitStreamE|
|SetHealthPacket::read|No|(RakNet::BitStream*)|IDK|_ZN15SetHealthPacket4readEPN6RakNet9BitStreamE|
|TallGrass::canSurvive|No|(TileSource*, int, int, int)|IDK|_ZN9TallGrass10canSurviveEP10TileSourceiii|
|ClockItem::getAnimationFrameFor|No|(Mob*) const|IDK|_ZNK9ClockItem20getAnimationFrameForEP3Mob|
|Level::getTimeOfDay|No|(float)|IDK|_ZN5Level12getTimeOfDayEf|
|SignTile::neighborChanged|No|(TileSource*, int, int, int, int, int, int)|IDK|_ZN8SignTile15neighborChangedEP10TileSourceiiiiii|
|HeartParticle::render|No|(Tesselator&, float, float, float, float, float, float)|IDK|_ZN13HeartParticle6renderER10Tesselatorffffff|
|SheepModel::prepareMobModel|No|(Mob*, float, float, float)|IDK|_ZN10SheepModel15prepareMobModelEP3Mobfff|
|Sheep::getHeadEatPositionScale|No|(float)|IDK|_ZN5Sheep23getHeadEatPositionScaleEf|
|Sheep::getHeadEatAngleScale|No|(float)|IDK|_ZN5Sheep20getHeadEatAngleScaleEf|
|Spinner::~Spinner|No|()|IDK|_ZN7SpinnerD2Ev|
|vtable for Spinner|No|(undefined|IDK|_ZTV7Spinner|
|Spinner::~Spinner|No|()|IDK|_ZN7SpinnerD1Ev|
|Spinner::~Spinner|No|()|IDK|_ZN7SpinnerD0Ev|
|VillagerRenderer::scale|No|(Mob*, float)|IDK|_ZN16VillagerRenderer5scaleEP3Mobf|
|Sapling::getTypeDescriptionId|No|(int)|IDK|_ZN7Sapling20getTypeDescriptionIdEi|
|std::array<std::string, 6u>::~array|No|()|IDK|_ZNSt5arrayISsLj6EED1Ev|
|SurvivalInventoryScreen::mouseReleased|No|(int, int, int)|IDK|_ZN23SurvivalInventoryScreen13mouseReleasedEiii|
|PaneCraftingScreen::keyPressed|No|(int)|IDK|_ZN18PaneCraftingScreen10keyPressedEi|
|Screen::tabNext|No|()|IDK|_ZN6Screen7tabNextEv|
|Screen::tabPrev|No|()|IDK|_ZN6Screen7tabPrevEv|
|CraftButton::renderBg|No|(Minecraft*, int, int)|IDK|_ZN11CraftButton8renderBgEP9Minecraftii|
|SurvivalInventoryScreen::updateTabButtonSelection|No|()|IDK|_ZN23SurvivalInventoryScreen24updateTabButtonSelectionEv|
|DefaultMobSpawner::broadcastEvent|No|(int)|IDK|_ZN17DefaultMobSpawner14broadcastEventEi|
|ChestTileEntity::startOpen|No|()|IDK|_ZN15ChestTileEntity9startOpenEv|
|non-virtual thunk to ChestTileEntity::startOpen|No|()|IDK|_ZThn96_N15ChestTileEntity9startOpenEv|
|NinecraftApp::onLowMemory|No|()|IDK|_ZN12NinecraftApp11onLowMemoryEv|
|GLBuffer::Pool::trim|No|()|IDK|_ZN8GLBuffer4Pool4trimEv|
|GLBuffer::glBufferPool|No|(undefined|IDK|_ZN8GLBuffer12glBufferPoolE|
|TaigaBiome::buildSurfaceAt|No|(Random&, LevelChunk&, TilePos const&, float)|IDK|_ZN10TaigaBiome14buildSurfaceAtER6RandomR10LevelChunkRK7TilePosf|
|Biome::buildSurfaceAtDefault|No|(Random&, LevelChunk&, TilePos const&, float)|IDK|_ZN5Biome21buildSurfaceAtDefaultER6RandomR10LevelChunkRK7TilePosf|
|DirtyChunkManager::queue|No|(Boxed<RenderChunk>&, bool)|IDK|_ZN17DirtyChunkManager5queueER5BoxedI11RenderChunkEb|
|DirtyChunkManager::sort|No|(Vec3 const&)|IDK|_ZN17DirtyChunkManager4sortERK4Vec3|
|DirtyChunkManager::process|No|(int, bool)|IDK|_ZN17DirtyChunkManager7processEib|
|TextureTessellator::end|No|()|IDK|_ZN18TextureTessellator3endEv|
|LevelRenderer::addParticle|No|(ParticleType, float, float, float, float, float, float, int)|IDK|_ZN13LevelRenderer11addParticleE12ParticleTypeffffffi|
|LevelRenderer::onAppSuspended|No|()|IDK|_ZN13LevelRenderer14onAppSuspendedEv|
|Boxed<RenderChunk>::Base::allocator|No|(undefined|IDK|_ZN5BoxedI11RenderChunkE4Base9allocatorE|
|non-virtual thunk to LevelRenderer::onAppSuspended|No|()|IDK|_ZThn4_N13LevelRenderer14onAppSuspendedEv|
|ForestBiome::setColor|No|(int)|IDK|_ZN11ForestBiome8setColorEi|
|ForestBiome::setColor|No|(int, bool)|IDK|_ZN11ForestBiome8setColorEib|
|ForestBiome::isHumid|No|()|IDK|_ZN11ForestBiome7isHumidEv|
|Semaphore::notify|No|()|IDK|_ZN9Semaphore6notifyEv|
|BaseRailTile::mayPlace|No|(TileSource*, int, int, int)|IDK|_ZN12BaseRailTile8mayPlaceEP10TileSourceiii|
|BaseRailTile::onRemove|No|(TileSource*, int, int, int)|IDK|_ZN12BaseRailTile8onRemoveEP10TileSourceiii|
|LocalPlayer::~LocalPlayer|No|()|IDK|_ZN11LocalPlayerD2Ev|
|Player::~Player|No|()|IDK|_ZN6PlayerD2Ev|
|vtable for LocalPlayer|No|(undefined|IDK|_ZTV11LocalPlayer|
|LocalPlayer::~LocalPlayer|No|()|IDK|_ZN11LocalPlayerD1Ev|
|non-virtual thunk to LocalPlayer::~LocalPlayer|No|()|IDK|_ZThn3384_N11LocalPlayerD1Ev|
|LocalPlayer::~LocalPlayer|No|()|IDK|_ZN11LocalPlayerD0Ev|
|non-virtual thunk to LocalPlayer::~LocalPlayer|No|()|IDK|_ZThn3384_N11LocalPlayerD0Ev|
|LocalPlayer::actuallyHurt|No|(int)|IDK|_ZN11LocalPlayer12actuallyHurtEi|
|LocalPlayer::respawn|No|()|IDK|_ZN11LocalPlayer7respawnEv|
|Minecraft::respawnPlayer|No|()|IDK|_ZN9Minecraft13respawnPlayerEv|
|LocalPlayer::causeFallDamage|No|(float)|IDK|_ZN11LocalPlayer15causeFallDamageEf|
|vtable for SetHealthPacket|No|(undefined|IDK|_ZTV15SetHealthPacket|
|ChestTileEntity::~ChestTileEntity|No|()|IDK|_ZN15ChestTileEntityD2Ev|
|FillingContainer::~FillingContainer|No|()|IDK|_ZN16FillingContainerD2Ev|
|TileEntity::~TileEntity|No|()|IDK|_ZN10TileEntityD2Ev|
|vtable for ChestTileEntity|No|(undefined|IDK|_ZTV15ChestTileEntity|
|ChestTileEntity::~ChestTileEntity|No|()|IDK|_ZN15ChestTileEntityD1Ev|
|non-virtual thunk to ChestTileEntity::~ChestTileEntity|No|()|IDK|_ZThn96_N15ChestTileEntityD1Ev|
|ChestTileEntity::~ChestTileEntity|No|()|IDK|_ZN15ChestTileEntityD0Ev|
|non-virtual thunk to ChestTileEntity::~ChestTileEntity|No|()|IDK|_ZThn96_N15ChestTileEntityD0Ev|
|MobSpawnerTileEntity::~MobSpawnerTileEntity|No|()|IDK|_ZN20MobSpawnerTileEntityD2Ev|
|vtable for MobSpawnerTileEntity|No|(undefined|IDK|_ZTV20MobSpawnerTileEntity|
|MobSpawnerTileEntity::~MobSpawnerTileEntity|No|()|IDK|_ZN20MobSpawnerTileEntityD1Ev|
|ChestTileEntity::stillValid|No|(Player*)|IDK|_ZN15ChestTileEntity10stillValidEP6Player|
|non-virtual thunk to ChestTileEntity::stillValid|No|(Player*)|IDK|_ZThn96_N15ChestTileEntity10stillValidEP6Player|
|ChestTileEntity::clearCache|No|()|IDK|_ZN15ChestTileEntity10clearCacheEv|
|TileEntity::clearCache|No|()|IDK|_ZN10TileEntity10clearCacheEv|
|ChestTileEntity::setRemoved|No|()|IDK|_ZN15ChestTileEntity10setRemovedEv|
|TileEntity::setRemoved|No|()|IDK|_ZN10TileEntity10setRemovedEv|
|LiquidTileDynamic::onPlace|No|(TileSource*, int, int, int)|IDK|_ZN17LiquidTileDynamic7onPlaceEP10TileSourceiii|
|LiquidTileStatic::tick|No|(TileSource*, int, int, int, Random*)|IDK|_ZN16LiquidTileStatic4tickEP10TileSourceiiiP6Random|
|CreeperModel::render|No|(Entity*, float, float, float, float, float, float)|IDK|_ZN12CreeperModel6renderEP6Entityffffff|
|SpiderModel::render|No|(Entity*, float, float, float, float, float, float)|IDK|_ZN11SpiderModel6renderEP6Entityffffff|
|SpiderModel::Eyes::render|No|(Entity*, float, float, float, float, float, float)|IDK|_ZN11SpiderModel4Eyes6renderEP6Entityffffff|
|VillagerModel::render|No|(Entity*, float, float, float, float, float, float)|IDK|_ZN13VillagerModel6renderEP6Entityffffff|
|LoginOption::tick|No|(Minecraft*)|IDK|_ZN11LoginOption4tickEP9Minecraft|
|MojangConnector::getConnectionStatus|No|()|IDK|_ZN15MojangConnector19getConnectionStatusEv|
|SlimeModel::~SlimeModel|No|()|IDK|_ZN10SlimeModelD2Ev|
|vtable for SlimeModel|No|(undefined|IDK|_ZTV10SlimeModel|
|SlimeModel::~SlimeModel|No|()|IDK|_ZN10SlimeModelD1Ev|
|SilverfishModel::~SilverfishModel|No|()|IDK|_ZN15SilverfishModelD2Ev|
|vtable for SilverfishModel|No|(undefined|IDK|_ZTV15SilverfishModel|
|SilverfishModel::~SilverfishModel|No|()|IDK|_ZN15SilverfishModelD1Ev|
|VillagerModel::~VillagerModel|No|()|IDK|_ZN13VillagerModelD2Ev|
|vtable for VillagerModel|No|(undefined|IDK|_ZTV13VillagerModel|
|VillagerModel::~VillagerModel|No|()|IDK|_ZN13VillagerModelD1Ev|
|SpiderModel::~SpiderModel|No|()|IDK|_ZN11SpiderModelD2Ev|
|vtable for SpiderModel|No|(undefined|IDK|_ZTV11SpiderModel|
|SpiderModel::~SpiderModel|No|()|IDK|_ZN11SpiderModelD1Ev|
|SpiderModel::Eyes::~Eyes|No|()|IDK|_ZN11SpiderModel4EyesD2Ev|
|vtable for SpiderModel::Eyes|No|(undefined|IDK|_ZTVN11SpiderModel4EyesE|
|SpiderModel::Eyes::~Eyes|No|()|IDK|_ZN11SpiderModel4EyesD1Ev|
|SpiderModel::Eyes::~Eyes|No|()|IDK|_ZN11SpiderModel4EyesD0Ev|
|CreeperModel::~CreeperModel|No|()|IDK|_ZN12CreeperModelD2Ev|
|vtable for CreeperModel|No|(undefined|IDK|_ZTV12CreeperModel|
|CreeperModel::~CreeperModel|No|()|IDK|_ZN12CreeperModelD1Ev|
|PigRenderer::~PigRenderer|No|()|IDK|_ZN11PigRendererD2Ev|
|MobRenderer::getArmor|No|()|IDK|_ZN11MobRenderer8getArmorEv|
|MobRenderer::~MobRenderer|No|()|IDK|_ZN11MobRendererD2Ev|
|vtable for PigRenderer|No|(undefined|IDK|_ZTV11PigRenderer|
|PigRenderer::~PigRenderer|No|()|IDK|_ZN11PigRendererD1Ev|
|MushroomCowRenderer::~MushroomCowRenderer|No|()|IDK|_ZN19MushroomCowRendererD2Ev|
|vtable for MushroomCowRenderer|No|(undefined|IDK|_ZTV19MushroomCowRenderer|
|MushroomCowRenderer::~MushroomCowRenderer|No|()|IDK|_ZN19MushroomCowRendererD1Ev|
|MushroomCowRenderer::~MushroomCowRenderer|No|()|IDK|_ZN19MushroomCowRendererD0Ev|
|CreeperRenderer::~CreeperRenderer|No|()|IDK|_ZN15CreeperRendererD2Ev|
|vtable for CreeperRenderer|No|(undefined|IDK|_ZTV15CreeperRenderer|
|CreeperRenderer::~CreeperRenderer|No|()|IDK|_ZN15CreeperRendererD1Ev|
|CreeperRenderer::~CreeperRenderer|No|()|IDK|_ZN15CreeperRendererD0Ev|
|SpiderRenderer::~SpiderRenderer|No|()|IDK|_ZN14SpiderRendererD2Ev|
|vtable for SpiderRenderer|No|(undefined|IDK|_ZTV14SpiderRenderer|
|SpiderRenderer::~SpiderRenderer|No|()|IDK|_ZN14SpiderRendererD1Ev|
|WolfRenderer::~WolfRenderer|No|()|IDK|_ZN12WolfRendererD2Ev|
|vtable for WolfRenderer|No|(undefined|IDK|_ZTV12WolfRenderer|
|WolfRenderer::~WolfRenderer|No|()|IDK|_ZN12WolfRendererD1Ev|
|WolfRenderer::~WolfRenderer|No|()|IDK|_ZN12WolfRendererD0Ev|
|VillagerRenderer::~VillagerRenderer|No|()|IDK|_ZN16VillagerRendererD2Ev|
|vtable for VillagerRenderer|No|(undefined|IDK|_ZTV16VillagerRenderer|
|VillagerRenderer::~VillagerRenderer|No|()|IDK|_ZN16VillagerRendererD1Ev|
|VillagerRenderer::~VillagerRenderer|No|()|IDK|_ZN16VillagerRendererD0Ev|
|SilverfishRenderer::~SilverfishRenderer|No|()|IDK|_ZN18SilverfishRendererD2Ev|
|vtable for SilverfishRenderer|No|(undefined|IDK|_ZTV18SilverfishRenderer|
|SilverfishRenderer::~SilverfishRenderer|No|()|IDK|_ZN18SilverfishRendererD1Ev|
|SilverfishRenderer::~SilverfishRenderer|No|()|IDK|_ZN18SilverfishRendererD0Ev|
|SlimeRenderer::~SlimeRenderer|No|()|IDK|_ZN13SlimeRendererD2Ev|
|vtable for SlimeRenderer|No|(undefined|IDK|_ZTV13SlimeRenderer|
|SlimeRenderer::~SlimeRenderer|No|()|IDK|_ZN13SlimeRendererD1Ev|
|SlimeRenderer::render|No|(Entity*, float, float, float, float, float)|IDK|_ZN13SlimeRenderer6renderEP6Entityfffff|
|MobRenderer::render|No|(Entity*, float, float, float, float, float)|IDK|_ZN11MobRenderer6renderEP6Entityfffff|
|CreeperRenderer::scale|No|(Mob*, float)|IDK|_ZN15CreeperRenderer5scaleEP3Mobf|
|Creeper::getSwelling|No|(float)|IDK|_ZN7Creeper11getSwellingEf|
|SpiderRenderer::scale|No|(Mob*, float)|IDK|_ZN14SpiderRenderer5scaleEP3Mobf|
|SlimeRenderer::scale|No|(Mob*, float)|IDK|_ZN13SlimeRenderer5scaleEP3Mobf|
|Slime::getSlimeSize|No|()|IDK|_ZN5Slime12getSlimeSizeEv|
|WolfRenderer::getBob|No|(Mob*, float)|IDK|_ZN12WolfRenderer6getBobEP3Mobf|
|Wolf::getTailAngle|No|(float)|IDK|_ZN4Wolf12getTailAngleEf|
|EntityRenderDispatcher::onAppSuspended|No|()|IDK|_ZN22EntityRenderDispatcher14onAppSuspendedEv|
|RandomLookAroundGoal::tick|No|()|IDK|_ZN20RandomLookAroundGoal4tickEv|
|LookControl::setLookAt|No|(float, float, float, float, float)|IDK|_ZN11LookControl9setLookAtEfffff|
|Player::onChunkRemoved|No|(LevelChunk&)|IDK|_ZN6Player14onChunkRemovedER10LevelChunk|
|PaneCraftingScreen::tick|No|()|IDK|_ZN18PaneCraftingScreen4tickEv|
|ScrollingPane::tick|No|()|IDK|_ZN13ScrollingPane4tickEv|
|PaneCraftingScreen::controllerDirectionChanged|No|(int, Controller::StickDirection)|IDK|_ZN18PaneCraftingScreen26controllerDirectionChangedEiN10Controller14StickDirectionE|
|ItemPane::setControllerDirection|No|(Controller::StickDirection)|IDK|_ZN8ItemPane22setControllerDirectionEN10Controller14StickDirectionE|
|PaneCraftingScreen::controllerDirectionHeld|No|(int, Controller::StickDirection)|IDK|_ZN18PaneCraftingScreen23controllerDirectionHeldEiN10Controller14StickDirectionE|
|PaneCraftingScreen::updateTabButtonSelection|No|()|IDK|_ZN18PaneCraftingScreen24updateTabButtonSelectionEv|
|WallClimberPathNavigation::~WallClimberPathNavigation|No|()|IDK|_ZN25WallClimberPathNavigationD2Ev|
|PathNavigation::~PathNavigation|No|()|IDK|_ZN14PathNavigationD2Ev|
|WallClimberPathNavigation::~WallClimberPathNavigation|No|()|IDK|_ZN25WallClimberPathNavigationD1Ev|
|WallClimberPathNavigation::~WallClimberPathNavigation|No|()|IDK|_ZN25WallClimberPathNavigationD0Ev|
|ForestBiome::~ForestBiome|No|()|IDK|_ZN11ForestBiomeD2Ev|
|vtable for ForestBiome|No|(undefined|IDK|_ZTV11ForestBiome|
|ForestBiome::~ForestBiome|No|()|IDK|_ZN11ForestBiomeD1Ev|
|ForestBiome::~ForestBiome|No|()|IDK|_ZN11ForestBiomeD0Ev|
|BeachBiome::~BeachBiome|No|()|IDK|_ZN10BeachBiomeD2Ev|
|vtable for BeachBiome|No|(undefined|IDK|_ZTV10BeachBiome|
|BeachBiome::~BeachBiome|No|()|IDK|_ZN10BeachBiomeD1Ev|
|BeachBiome::~BeachBiome|No|()|IDK|_ZN10BeachBiomeD0Ev|
|TaigaBiome::~TaigaBiome|No|()|IDK|_ZN10TaigaBiomeD2Ev|
|vtable for TaigaBiome|No|(undefined|IDK|_ZTV10TaigaBiome|
|TaigaBiome::~TaigaBiome|No|()|IDK|_ZN10TaigaBiomeD1Ev|
|TaigaBiome::~TaigaBiome|No|()|IDK|_ZN10TaigaBiomeD0Ev|
|PigZombie::~PigZombie|No|()|IDK|_ZN9PigZombieD2Ev|
|vtable for PigZombie|No|(undefined|IDK|_ZTV9PigZombie|
|PigZombie::~PigZombie|No|()|IDK|_ZN9PigZombieD1Ev|
|PigZombie::~PigZombie|No|()|IDK|_ZN9PigZombieD0Ev|
|SheepModel::~SheepModel|No|()|IDK|_ZN10SheepModelD2Ev|
|QuadrupedModel::~QuadrupedModel|No|()|IDK|_ZN14QuadrupedModelD2Ev|
|vtable for SheepModel|No|(undefined|IDK|_ZTV10SheepModel|
|SheepModel::~SheepModel|No|()|IDK|_ZN10SheepModelD1Ev|
|SheepModel::~SheepModel|No|()|IDK|_ZN10SheepModelD0Ev|
|HugeMushroomTile::getTexture|No|(signed char, int)|IDK|_ZN16HugeMushroomTile10getTextureEai|
|Mushroom::mayPlace|No|(TileSource*, int, int, int, signed char)|IDK|_ZN8Mushroom8mayPlaceEP10TileSourceiiia|
|Mushroom::canSurvive|No|(TileSource*, int, int, int)|IDK|_ZN8Mushroom10canSurviveEP10TileSourceiii|
|BaseRailTile::getShape|No|(unsigned char, AABB&, bool)|IDK|_ZN12BaseRailTile8getShapeEhR4AABBb|
|SignTile::getAABB|No|(TileSource*, int, int, int, AABB&, int, bool, int)|IDK|_ZN8SignTile7getAABBEP10TileSourceiiiR4AABBibi|
|ChestTileEntity::stopOpen|No|()|IDK|_ZN15ChestTileEntity8stopOpenEv|
|non-virtual thunk to ChestTileEntity::stopOpen|No|()|IDK|_ZThn96_N15ChestTileEntity8stopOpenEv|
|LevelRenderer::playSound|No|(std::string const&, float, float, float, float, float)|IDK|_ZN13LevelRenderer9playSoundERKSsfffff|
|LocalPlayer::openFurnace|No|(FurnaceTileEntity*)|IDK|_ZN11LocalPlayer11openFurnaceEP17FurnaceTileEntity|
|FurnaceScreen::FurnaceScreen|No|(Player*, FurnaceTileEntity*)|IDK|_ZN13FurnaceScreenC1EP6PlayerP17FurnaceTileEntity|
|LocalPlayer::openContainer|No|(ChestTileEntity*)|IDK|_ZN11LocalPlayer13openContainerEP15ChestTileEntity|
|LocalPlayer::openTextEdit|No|(TileEntity*)|IDK|_ZN11LocalPlayer12openTextEditEP10TileEntity|
|TextEditScreen::TextEditScreen|No|(SignTileEntity*)|IDK|_ZN14TextEditScreenC1EP14SignTileEntity|
|SlimeModel::render|No|(Entity*, float, float, float, float, float, float)|IDK|_ZN10SlimeModel6renderEP6Entityffffff|
|ZombieModel::setupAnim|No|(float, float, float, float, float, float)|IDK|_ZN11ZombieModel9setupAnimEffffff|
|HumanoidModel::setupAnim|No|(float, float, float, float, float, float)|IDK|_ZN13HumanoidModel9setupAnimEffffff|
|WallClimberPathNavigation::moveTo|No|(Mob*, float)|IDK|_ZN25WallClimberPathNavigation6moveToEP3Mobf|
|PathNavigation::moveTo|No|(Path*, float)|IDK|_ZN14PathNavigation6moveToEP4Pathf|
|BaseRailTile::getAABB|No|(TileSource*, int, int, int, AABB&, int, bool, int)|IDK|_ZN12BaseRailTile7getAABBEP10TileSourceiiiR4AABBibi|
|CreeperRenderer::getOverlayColor|No|(Mob*, float, float)|IDK|_ZN15CreeperRenderer15getOverlayColorEP3Mobff|
|Color4::NIL|No|(undefined|IDK|_ZN6Color43NILE|
|PickaxeItem::canDestroySpecial|No|(Tile const*) const|IDK|_ZNK11PickaxeItem17canDestroySpecialEPK4Tile|
|SeedItem::useOn|No|(ItemInstance*, Player*, int, int, int, signed char, float, float, float)|IDK|_ZN8SeedItem5useOnEP12ItemInstanceP6Playeriiiafff|
|SeedFoodItem::useOn|No|(ItemInstance*, Player*, int, int, int, signed char, float, float, float)|IDK|_ZN12SeedFoodItem5useOnEP12ItemInstanceP6Playeriiiafff|
|SaddleItem::hurtEnemy|No|(ItemInstance*, Mob*, Mob*)|IDK|_ZN10SaddleItem9hurtEnemyEP12ItemInstanceP3MobS3_|
|BedItem::useOn|No|(ItemInstance*, Player*, int, int, int, signed char, float, float, float)|IDK|_ZN7BedItem5useOnEP12ItemInstanceP6Playeriiiafff|
|SignItem::useOn|No|(ItemInstance*, Player*, int, int, int, signed char, float, float, float)|IDK|_ZN8SignItem5useOnEP12ItemInstanceP6Playeriiiafff|
|LoginOption::mouseClicked|No|(Minecraft*, int, int, int)|IDK|_ZN11LoginOption12mouseClickedEP9Minecraftiii|
|SurvivalInventoryScreen::controllerDirectionHeld|No|(int, Controller::StickDirection)|IDK|_ZN23SurvivalInventoryScreen23controllerDirectionHeldEiN10Controller14StickDirectionE|
|NinecraftApp::handleBack|No|(bool)|IDK|_ZN12NinecraftApp10handleBackEb|
|SlimeRenderer::prepareArmor|No|(Mob*, int, float)|IDK|_ZN13SlimeRenderer12prepareArmorEP3Mobif|
|MobRenderer::setArmor|No|(Model*)|IDK|_ZN11MobRenderer8setArmorEP5Model|
|PigZombie::getTexture|No|()|IDK|_ZN9PigZombie10getTextureEv|
|LocalPlayer::swing|No|()|IDK|_ZN11LocalPlayer5swingEv|
|vtable for AnimatePacket|No|(undefined|IDK|_ZTV13AnimatePacket|
|ForestBiome::getRandomFlowerTypeAndData|No|(Random&, TilePos const&)|IDK|_ZN11ForestBiome26getRandomFlowerTypeAndDataER6RandomRK7TilePos|
|PigZombie::canSpawn|No|()|IDK|_ZN9PigZombie8canSpawnEv|
|SilverfishModel::render|No|(Entity*, float, float, float, float, float, float)|IDK|_ZN15SilverfishModel6renderEP6Entityffffff|
|SpiderRenderer::~SpiderRenderer|No|()|IDK|_ZN14SpiderRendererD0Ev|
|SignRenderer::~SignRenderer|No|()|IDK|_ZN12SignRendererD2Ev|
|TileEntityRenderer::~TileEntityRenderer|No|()|IDK|_ZN18TileEntityRendererD2Ev|
|SignRenderer::~SignRenderer|No|()|IDK|_ZN12SignRendererD1Ev|
|SignRenderer::~SignRenderer|No|()|IDK|_ZN12SignRendererD0Ev|
|SlimeModel::~SlimeModel|No|()|IDK|_ZN10SlimeModelD0Ev|
|SlimeRenderer::~SlimeRenderer|No|()|IDK|_ZN13SlimeRendererD0Ev|
|MobSpawnerTileEntity::~MobSpawnerTileEntity|No|()|IDK|_ZN20MobSpawnerTileEntityD0Ev|
|PigRenderer::~PigRenderer|No|()|IDK|_ZN11PigRendererD0Ev|
|SkeletonModel::setupAnim|No|(float, float, float, float, float, float)|IDK|_ZN13SkeletonModel9setupAnimEffffff|
|TextureTessellator::tesselate|No|(TextureData const&, int, int, int, int)|IDK|_ZN18TextureTessellator9tesselateERK11TextureDataiiii|
|VillagerModel::~VillagerModel|No|()|IDK|_ZN13VillagerModelD0Ev|
|CreeperModel::~CreeperModel|No|()|IDK|_ZN12CreeperModelD0Ev|
|MinecartRenderer::~MinecartRenderer|No|()|IDK|_ZN16MinecartRendererD2Ev|
|vtable for MinecartRenderer|No|(undefined|IDK|_ZTV16MinecartRenderer|
|vtable for MinecartModel|No|(undefined|IDK|_ZTV13MinecartModel|
|MinecartRenderer::~MinecartRenderer|No|()|IDK|_ZN16MinecartRendererD1Ev|
|ChunkViewSource::getExistingChunk|No|(ChunkPos const&)|IDK|_ZN15ChunkViewSource16getExistingChunkERK8ChunkPos|
|MinecartRenderer::~MinecartRenderer|No|()|IDK|_ZN16MinecartRendererD0Ev|
|CompassItem::getAnimationFrameFor|No|(Mob*) const|IDK|_ZNK11CompassItem20getAnimationFrameForEP3Mob|
|Level::getSharedSpawnPos|No|()|IDK|_ZN5Level17getSharedSpawnPosEv|
|LongTag::equals|No|(Tag const&) const|IDK|_ZNK7LongTag6equalsERK3Tag|
|DoubleTag::equals|No|(Tag const&) const|IDK|_ZNK9DoubleTag6equalsERK3Tag|
|ByteArrayTag::equals|No|(Tag const&) const|IDK|_ZNK12ByteArrayTag6equalsERK3Tag|
|IntArrayTag::equals|No|(Tag const&) const|IDK|_ZNK11IntArrayTag6equalsERK3Tag|
|EndTag::equals|No|(Tag const&) const|IDK|_ZNK6EndTag6equalsERK3Tag|
|SilverfishModel::~SilverfishModel|No|()|IDK|_ZN15SilverfishModelD0Ev|
|SpiderModel::~SpiderModel|No|()|IDK|_ZN11SpiderModelD0Ev|
|ZombieModel::~ZombieModel|No|()|IDK|_ZN11ZombieModelD2Ev|
|vtable for HumanoidModel|No|(undefined|IDK|_ZTV13HumanoidModel|
|ZombieModel::~ZombieModel|No|()|IDK|_ZN11ZombieModelD1Ev|
|SkeletonModel::~SkeletonModel|No|()|IDK|_ZN13SkeletonModelD2Ev|
|SkeletonModel::~SkeletonModel|No|()|IDK|_ZN13SkeletonModelD1Ev|
|ZombieModel::~ZombieModel|No|()|IDK|_ZN11ZombieModelD0Ev|
|SkeletonModel::~SkeletonModel|No|()|IDK|_ZN13SkeletonModelD0Ev|
|Boxed<RenderChunk>::~Boxed|No|()|IDK|_ZN5BoxedI11RenderChunkED2Ev|
|Boxed<RenderChunk>::~Boxed|No|()|IDK|_ZN5BoxedI11RenderChunkED1Ev|
|PlayerInputPacket::write|No|(RakNet::BitStream*)|IDK|_ZN17PlayerInputPacket5writeEPN6RakNet9BitStreamE|
|PlayerInputPacket::read|No|(RakNet::BitStream*)|IDK|_ZN17PlayerInputPacket4readEPN6RakNet9BitStreamE|
|EntityRenderDispatcher::~EntityRenderDispatcher|No|()|IDK|_ZN22EntityRenderDispatcherD2Ev|
|vtable for EntityRenderDispatcher|No|(undefined|IDK|_ZTV22EntityRenderDispatcher|
|EntityRenderDispatcher::~EntityRenderDispatcher|No|()|IDK|_ZN22EntityRenderDispatcherD1Ev|
|EntityRenderDispatcher::~EntityRenderDispatcher|No|()|IDK|_ZN22EntityRenderDispatcherD0Ev|
|EntityEventPacket::write|No|(RakNet::BitStream*)|IDK|_ZN17EntityEventPacket5writeEPN6RakNet9BitStreamE|
|AnimatePacket::write|No|(RakNet::BitStream*)|IDK|_ZN13AnimatePacket5writeEPN6RakNet9BitStreamE|
|AnimatePacket::read|No|(RakNet::BitStream*)|IDK|_ZN13AnimatePacket4readEPN6RakNet9BitStreamE|
|EntityEventPacket::read|No|(RakNet::BitStream*)|IDK|_ZN17EntityEventPacket4readEPN6RakNet9BitStreamE|
|DropItemPacket::write|No|(RakNet::BitStream*)|IDK|_ZN14DropItemPacket5writeEPN6RakNet9BitStreamE|
|DropItemPacket::read|No|(RakNet::BitStream*)|IDK|_ZN14DropItemPacket4readEPN6RakNet9BitStreamE|
|PlayerEquipmentPacket::write|No|(RakNet::BitStream*)|IDK|_ZN21PlayerEquipmentPacket5writeEPN6RakNet9BitStreamE|
|PlayerEquipmentPacket::read|No|(RakNet::BitStream*)|IDK|_ZN21PlayerEquipmentPacket4readEPN6RakNet9BitStreamE|
|MovePlayerPacket::write|No|(RakNet::BitStream*)|IDK|_ZN16MovePlayerPacket5writeEPN6RakNet9BitStreamE|
|Options::Option::~Option|No|()|IDK|_ZN7Options6OptionD2Ev|
|Options::Option::~Option|No|()|IDK|_ZN7Options6OptionD1Ev|
|std::array<std::string, 6u>::~array|No|()|IDK|_ZNSt5arrayISsLj6EED2Ev|
|Tag::~Tag|No|()|IDK|_ZN3TagD2Ev|
|Tag::~Tag|No|()|IDK|_ZN3TagD1Ev|
|Bush::~Bush|No|()|IDK|_ZN4BushD2Ev|
|Bush::~Bush|No|()|IDK|_ZN4BushD1Ev|
|PodzolTile::~PodzolTile|No|()|IDK|_ZN10PodzolTileD2Ev|
|PodzolTile::~PodzolTile|No|()|IDK|_ZN10PodzolTileD1Ev|
|BaseRailTile::~BaseRailTile|No|()|IDK|_ZN12BaseRailTileD2Ev|
|BaseRailTile::~BaseRailTile|No|()|IDK|_ZN12BaseRailTileD1Ev|
|HugeMushroomTile::~HugeMushroomTile|No|()|IDK|_ZN16HugeMushroomTileD2Ev|
|HugeMushroomTile::~HugeMushroomTile|No|()|IDK|_ZN16HugeMushroomTileD1Ev|
|DataItem2<std::string>::~DataItem2|No|()|IDK|_ZN9DataItem2ISsED2Ev|
|vtable for DataItem2<std::string>|No|(undefined|IDK|_ZTV9DataItem2ISsE|
|DataItem2<std::string>::~DataItem2|No|()|IDK|_ZN9DataItem2ISsED1Ev|
|EndTag::~EndTag|No|()|IDK|_ZN6EndTagD2Ev|
|EndTag::~EndTag|No|()|IDK|_ZN6EndTagD1Ev|
|IntArrayTag::~IntArrayTag|No|()|IDK|_ZN11IntArrayTagD2Ev|
|IntArrayTag::~IntArrayTag|No|()|IDK|_ZN11IntArrayTagD1Ev|
|ByteArrayTag::~ByteArrayTag|No|()|IDK|_ZN12ByteArrayTagD2Ev|
|ByteArrayTag::~ByteArrayTag|No|()|IDK|_ZN12ByteArrayTagD1Ev|
|DoubleTag::~DoubleTag|No|()|IDK|_ZN9DoubleTagD2Ev|
|DoubleTag::~DoubleTag|No|()|IDK|_ZN9DoubleTagD1Ev|
|LongTag::~LongTag|No|()|IDK|_ZN7LongTagD2Ev|
|LongTag::~LongTag|No|()|IDK|_ZN7LongTagD1Ev|
|Sapling::~Sapling|No|()|IDK|_ZN7SaplingD2Ev|
|Sapling::~Sapling|No|()|IDK|_ZN7SaplingD1Ev|
|TallGrass::~TallGrass|No|()|IDK|_ZN9TallGrassD2Ev|
|TallGrass::~TallGrass|No|()|IDK|_ZN9TallGrassD1Ev|
|Mushroom::~Mushroom|No|()|IDK|_ZN8MushroomD2Ev|
|Mushroom::~Mushroom|No|()|IDK|_ZN8MushroomD1Ev|
|SignTile::~SignTile|No|()|IDK|_ZN8SignTileD2Ev|
|SignTile::~SignTile|No|()|IDK|_ZN8SignTileD1Ev|
|Tag::~Tag|No|()|IDK|_ZN3TagD0Ev|
|LongTag::~LongTag|No|()|IDK|_ZN7LongTagD0Ev|
|EndTag::~EndTag|No|()|IDK|_ZN6EndTagD0Ev|
|IntArrayTag::~IntArrayTag|No|()|IDK|_ZN11IntArrayTagD0Ev|
|ByteArrayTag::~ByteArrayTag|No|()|IDK|_ZN12ByteArrayTagD0Ev|
|DoubleTag::~DoubleTag|No|()|IDK|_ZN9DoubleTagD0Ev|
|DataItem2<std::string>::~DataItem2|No|()|IDK|_ZN9DataItem2ISsED0Ev|
|HugeMushroomTile::~HugeMushroomTile|No|()|IDK|_ZN16HugeMushroomTileD0Ev|
|Bush::~Bush|No|()|IDK|_ZN4BushD0Ev|
|BaseRailTile::~BaseRailTile|No|()|IDK|_ZN12BaseRailTileD0Ev|
|PodzolTile::~PodzolTile|No|()|IDK|_ZN10PodzolTileD0Ev|
|Sapling::~Sapling|No|()|IDK|_ZN7SaplingD0Ev|
|WeaponItem::~WeaponItem|No|()|IDK|_ZN10WeaponItemD2Ev|
|WeaponItem::~WeaponItem|No|()|IDK|_ZN10WeaponItemD1Ev|
|BedItem::~BedItem|No|()|IDK|_ZN7BedItemD2Ev|
|BedItem::~BedItem|No|()|IDK|_ZN7BedItemD1Ev|
|TilePlanterItem::~TilePlanterItem|No|()|IDK|_ZN15TilePlanterItemD2Ev|
|TilePlanterItem::~TilePlanterItem|No|()|IDK|_ZN15TilePlanterItemD1Ev|
|ShearsItem::~ShearsItem|No|()|IDK|_ZN10ShearsItemD2Ev|
|ShearsItem::~ShearsItem|No|()|IDK|_ZN10ShearsItemD1Ev|
|FoodItem::~FoodItem|No|()|IDK|_ZN8FoodItemD2Ev|
|FoodItem::~FoodItem|No|()|IDK|_ZN8FoodItemD1Ev|
|EggItem::~EggItem|No|()|IDK|_ZN7EggItemD2Ev|
|EggItem::~EggItem|No|()|IDK|_ZN7EggItemD1Ev|
|CompassItem::~CompassItem|No|()|IDK|_ZN11CompassItemD2Ev|
|CompassItem::~CompassItem|No|()|IDK|_ZN11CompassItemD1Ev|
|SignItem::~SignItem|No|()|IDK|_ZN8SignItemD2Ev|
|SignItem::~SignItem|No|()|IDK|_ZN8SignItemD1Ev|
|ClockItem::~ClockItem|No|()|IDK|_ZN9ClockItemD2Ev|
|ClockItem::~ClockItem|No|()|IDK|_ZN9ClockItemD1Ev|
|CoalItem::~CoalItem|No|()|IDK|_ZN8CoalItemD2Ev|
|CoalItem::~CoalItem|No|()|IDK|_ZN8CoalItemD1Ev|
|BucketItem::~BucketItem|No|()|IDK|_ZN10BucketItemD2Ev|
|BucketItem::~BucketItem|No|()|IDK|_ZN10BucketItemD1Ev|
|SaddleItem::~SaddleItem|No|()|IDK|_ZN10SaddleItemD2Ev|
|SaddleItem::~SaddleItem|No|()|IDK|_ZN10SaddleItemD1Ev|
|SeedItem::~SeedItem|No|()|IDK|_ZN8SeedItemD2Ev|
|SeedItem::~SeedItem|No|()|IDK|_ZN8SeedItemD1Ev|
|Item::~Item|No|()|IDK|_ZN4ItemD2Ev|
|Item::~Item|No|()|IDK|_ZN4ItemD1Ev|
|Mushroom::~Mushroom|No|()|IDK|_ZN8MushroomD0Ev|
|SignTile::~SignTile|No|()|IDK|_ZN8SignTileD0Ev|
|TallGrass::~TallGrass|No|()|IDK|_ZN9TallGrassD0Ev|
|SnowballItem::~SnowballItem|No|()|IDK|_ZN12SnowballItemD2Ev|
|SnowballItem::~SnowballItem|No|()|IDK|_ZN12SnowballItemD1Ev|
|SeedFoodItem::~SeedFoodItem|No|()|IDK|_ZN12SeedFoodItemD2Ev|
|SeedFoodItem::~SeedFoodItem|No|()|IDK|_ZN12SeedFoodItemD1Ev|
|BowlFoodItem::~BowlFoodItem|No|()|IDK|_ZN12BowlFoodItemD2Ev|
|BowlFoodItem::~BowlFoodItem|No|()|IDK|_ZN12BowlFoodItemD1Ev|
|Item::~Item|No|()|IDK|_ZN4ItemD0Ev|
|LiquidTileStatic::~LiquidTileStatic|No|()|IDK|_ZN16LiquidTileStaticD2Ev|
|LiquidTileStatic::~LiquidTileStatic|No|()|IDK|_ZN16LiquidTileStaticD1Ev|
|LiquidTileDynamic::~LiquidTileDynamic|No|()|IDK|_ZN17LiquidTileDynamicD2Ev|
|LiquidTileDynamic::~LiquidTileDynamic|No|()|IDK|_ZN17LiquidTileDynamicD1Ev|
|WeaponItem::~WeaponItem|No|()|IDK|_ZN10WeaponItemD0Ev|
|ShearsItem::~ShearsItem|No|()|IDK|_ZN10ShearsItemD0Ev|
|EggItem::~EggItem|No|()|IDK|_ZN7EggItemD0Ev|
|BedItem::~BedItem|No|()|IDK|_ZN7BedItemD0Ev|
|SnowballItem::~SnowballItem|No|()|IDK|_ZN12SnowballItemD0Ev|
|FoodItem::~FoodItem|No|()|IDK|_ZN8FoodItemD0Ev|
|TilePlanterItem::~TilePlanterItem|No|()|IDK|_ZN15TilePlanterItemD0Ev|
|SeedItem::~SeedItem|No|()|IDK|_ZN8SeedItemD0Ev|
|SaddleItem::~SaddleItem|No|()|IDK|_ZN10SaddleItemD0Ev|
