![image](https://github.com/JohannUG76/DEBER2JOHANN/assets/169223501/f1262fff-9499-46a8-a318-4707908502b5)package application;

import javafx.application.Application; import javafx.scene.Scene; import javafx.scene.control.*; import javafx.scene.layout.GridPane; import javafx.stage.Stage;

public class Main extends Application { @Override public void start(Stage primaryStage) { try { // Crear el GridPane GridPane root = new GridPane(); root.setHgap(12); root.setVgap(12);

        // Crear los elementos
        Label buttonLabel = new Label("Button:");
        Button button = new Button("Button");

        Label checkBoxLabel = new Label("CheckBox:");
        CheckBox checkBox = new CheckBox("CheckBox");

        Label hyperlinkLabel = new Label("Hyperlink:");
        Hyperlink hyperlink = new Hyperlink("Hyperlink");

        Label toggleButtonLabel = new Label("ToggleButton:");
        ToggleButton toggleButton = new ToggleButton("ToggleButton");

        Label radioButtonLabel = new Label("RadioButton:");
        RadioButton radioButton = new RadioButton("RadioButton");

        Label labelLabel = new Label("Label:");
        Label label = new Label("Label");

        Label textFieldLabel = new Label("TextField:");
        TextField textField = new TextField("some text...");

        Label passwordFieldLabel = new Label("PasswordField:");
        PasswordField passwordField = new PasswordField();
        passwordField.setText("danieljaya");

        Label textAreaLabel = new Label("TextArea:");
        TextArea textArea = new TextArea("This is very long text that will wrap to several lines.");

        Label progressIndicatorLabel = new Label("ProgressIndicator:");
        ProgressIndicator progressIndicator = new ProgressIndicator(0.49);

        Label progressBarLabel = new Label("ProgressBar:");
        ProgressBar progressBar = new ProgressBar(0.49);

        Label sliderLabel = new Label("Slider:");
        Slider slider = new Slider();

        // Agregar los elementos
        root.add(buttonLabel, 0, 0);
        root.add(button, 1, 0);

        root.add(checkBoxLabel, 0, 1);
        root.add(checkBox, 1, 1);

        root.add(hyperlinkLabel, 0, 2);
        root.add(hyperlink, 1, 2);

        root.add(toggleButtonLabel, 0, 3);
        root.add(toggleButton, 1, 3);

        root.add(radioButtonLabel, 0, 4);
        root.add(radioButton, 1, 4);

        root.add(labelLabel, 0, 5);
        root.add(label, 1, 5);

        root.add(textFieldLabel, 0, 6);
        root.add(textField, 1, 6);

        root.add(passwordFieldLabel, 0, 7);
        root.add(passwordField, 1, 7);

        root.add(textAreaLabel, 0, 8);
        root.add(textArea, 1, 8, 2, 1); 

        root.add(progressIndicatorLabel, 0, 9);
        root.add(progressIndicator, 1, 9);

        root.add(progressBarLabel, 0, 10);
        root.add(progressBar, 1, 10);

        root.add(sliderLabel, 0, 11);
        root.add(slider, 1, 11);

        // Crear la escena
        Scene scene = new Scene(root, 500, 500);


        // Configurar el Stage
        primaryStage.setScene(scene);
        primaryStage.setTitle("allcontrols.fxml");
        primaryStage.show();
    } catch (Exception e) {
        e.printStackTrace();
    }
}

public static void main(String[] args) {
    launch(args);
}
}
![Captura de pantalla 2024-06-11 203217](https://github.com/JohannUG76/DEBER2JOHANN/assets/169223501/96bcc2bd-14ac-4b4b-981a-b4db9e9acad2)
