import javafx.application.Application;
import javafx.scene.Scene;
import javafx.scene.layout.StackPane;
import javafx.scene.paint.Color;
import javafx.stage.Stage;

public class RedColorChange extends Application {

    @Override
    public void start(Stage primaryStage) {
        // Create a StackPane as the root node
        StackPane root = new StackPane();
        
        // Set the background color to red
        root.setStyle("-fx-background-color: red;");
        
        // Create a Scene with the StackPane as the root
        Scene scene = new Scene(root, 300, 200, Color.RED);
        
        // Set the scene for the stage
        primaryStage.setScene(scene);
        
        // Set the title of the stage
        primaryStage.setTitle("Red Color Change Example");
        
        // Show the stage
        primaryStage.show();
    }

    public static void main(String[] args) {
        launch(args);
    }
}
