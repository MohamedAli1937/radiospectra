Fix lowercase instrument check in ``SWAVESSpectrogram.is_datasource_for``. 
The class checked for ``"swaves"`` but the factory instantiates metadata with ``"SWAVES"``, consistent with other instruments.
