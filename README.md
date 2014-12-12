
public class Currency {

	// private variable
	private String currencyName;
	private double currencyConv;

	// Constructor method for the Currency class
    public Currency(String currName, double convRate) {
		currencyName = currName;
		currencyConv = convRate;
	}
	
	// constructor method for the 
	public Currency
	
	
	// A method to return a converted amount
	public double convert(double amount) {
		double convertedAmount = amount * currencyConv;
		return (convertedAmount);
	}
	
	
	
	
}
