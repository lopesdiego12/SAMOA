# SAMOA

`bin/samoa local target/SAMOA-Local-0.5.0-incubating-SNAPSHOT.jar "PrequentialEvaluation -f 10000 -s (ArffFileStream -f rtg_1m.arff) -d rtg_VHT.txt" `

`bin/samoa local target/SAMOA-Local-0.5.0-incubating-SNAPSHOT.jar "PrequentialEvaluation -f 000 -s (ArffFileStream -f rtg_1m.arff) -d rtg_AdaptiveBagging.txt -l (classifiers.ensemble.AdaptiveBagging)"`


# VerticalHoeffdingTree
`bin/samoa local target/SAMOA-Local-0.5.0-incubating-SNAPSHOT.jar "PrequentialEvaluation -f 1000 -s (ArffFileStream -f database/input/exe_agra.arff) -d database/output/exe_agra_VHT.txt -l (classifiers.trees.VerticalHoeffdingTree)"`

`bin/samoa local target/SAMOA-Local-0.5.0-incubating-SNAPSHOT.jar "PrequentialEvaluation -f 1000 -s (ArffFileStream -f database/input/exe_sea.arff) -d database/output/exe_sea_VHT.txt -l (classifiers.trees.VerticalHoeffdingTree)"`

# AdaptiveBagging
`bin/samoa local target/SAMOA-Local-0.5.0-incubating-SNAPSHOT.jar "PrequentialEvaluation -f 1000 -s (ArffFileStream -f database/input/exe_agra.arff) -d database/output/exe_agra_AB.txt -l (classifiers.ensemble.AdaptiveBagging)"`

`bin/samoa local target/SAMOA-Local-0.5.0-incubating-SNAPSHOT.jar "PrequentialEvaluation -f 1000 -s (ArffFileStream -f database/input/exe_sea.arff) -d database/output/exe_sea_AB.txt -l (classifiers.ensemble.AdaptiveBagging)"`