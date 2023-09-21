# Qt
self.checkOne = QtWidgets.QCheckBox('one')    self.checkTwo = QtWidgets.QCheckBox('two') self.vlayout.addWidget(self.checkTwo) def selectBooks2(self, toggle):         if toggle == QtCore.Qt.Checked:             print('checked 2')             self.checkOne.setEnabled(False)
