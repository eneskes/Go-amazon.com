# Go-amazon.com
import org.openqa.selenium.WebDriver;
import org.openqa.selenium.chrome.ChromeDriver;

public class C01_IlkClass {
    public static void main(String[] args) {

        System.setProperty("webdriver.chrome.driver","src/resources/driver/chromedriver.exe");
        WebDriver driver=new ChromeDriver();
        driver.get("https:techproeducation.com");
        
        driver.get("https://www.amazon.com");

        driver.close();


    }
}
