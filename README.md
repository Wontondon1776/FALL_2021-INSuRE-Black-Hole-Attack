# FALL_2021-INSuRE-Black-Hole-Attack

Many of these files allow changes to the map within sumo and VEINS. However in order to launch a simulated black hole attack you must make neccessary configurations to the .cc file locared under veins_inet

// Black hole attack simulation:
//Specify which vehicle with the index
if (getParentModule() ->getIndex()== 1) {
  return;
  }
  
  
