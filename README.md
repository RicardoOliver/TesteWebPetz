# Desafio de automação WEB PETZ

## Detalhes do projeto

Foi realizada a automação web utilizando PageObject + Maven + Java + JUnit + Cucumber + Extent Report + Selenium Webdriver + Gherkin.

## Para abrir AutomacaoWeb.html na pasta evidência de report de execução indico utilizar a IDE Intellij.


## Report de execução
Report armazenado na pasta target/evidencia/
![Image description](src/test/java/resources/total_evidencias_report.png)
![Image description](src/test/java/resources/EVIDENCIA_1.png)
![Image description](src/test/java/resources/EVIDENCIA_2.png)
![Image description](src/test/java/resources/EVIDENCIA_3.png)
![Image description](src/test/java/resources/EVIDENCIA_4.png)
![Image description](src/test/java/resources/EVIDENCIA_5.png)


## Deve adcionar o tilulo no método validarTextoBlog no xpath dentro de object.
# Markdown

public Boolean validarTextoBlog(){
WebElement element = driver.findElement(By.xpath("//span[contains(text(),'Quanto tempo leva e como é a recuperação da castra')]"));
Actions actions = new Actions(driver);
actions.moveToElement(element);
actions.perform();
return validarBlog.isDisplayed();
}