# Schleife
for i in 1 2 3; do

  echo "Nummer: $i"

done


i=1

    while [ $i -le 5 ]; do
    
      echo "Die Schleife läuft $i Mal."
      
      i=$(($i+1))
      
    done
