PATH_TO_FX="/home/tiger/lib/javafx-sdk-11.0.2/lib"
modules=javafx.controls,javafx.base,javafx.fxml,javafx.graphics,javafx.media,javafx.web
all:
	javac --module-path $(PATH_TO_FX) --add-modules $(modules) hello/HelloFX.java
	java  --module-path $(PATH_TO_FX) --add-modules $(modules) hello.HelloFX
	rm hello/*.class