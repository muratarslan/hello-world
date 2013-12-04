(defmacro foreva [& bud] 
  `(while true ~@bud))
  
  (foreva (println "hi!"))
