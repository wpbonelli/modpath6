sources = files(
  'MOD_GLOBAL.for',
  'MOD_MPBAS.for',
  'MOD_MPDATA.for',
  'MOD_PARTICLEDATA.for',
  'MP6.for',
  'MP6Budgetrd.for',
  'MP6Flowdata.for',
  'MP6MPBAS1.for',
  'MP6ParticleMgr.for',
  'MP6PrecisionCheck.for',
  'MP6TrackParticles.for',
  'MP6Util.for',
  'Writpts0.for',
)

exe = executable(
                 'mp6',
                 sources,
                 dependencies: extra_deps,
                 install: true
                )
