# HodoscopioConCilindro
1)   Modificación del framework Meiga introduciendo una torre catalítica representada por un cilindro de 7 materiales
1.1)  G4Models se sustituye en:
/opt/meiga/src
1.2)  G4HodoscopeSimulator se sustituye en:
/opt/meiga/src/Applications
2)   En el archivo G4HodoscopeDetectorConstruction.cc se agregaron dos variables "Y_centro_panelI" y "Z_centro_panelI" para ubicar las coordenadas del blindaje del Hodoscopio y se agregaron 7 rutas para definir las porciones del cilindro (con variables editables )
