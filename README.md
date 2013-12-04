(defmacro forever [& body] 
  `(while true ~@body))
  
  (forever (print "hi "))
