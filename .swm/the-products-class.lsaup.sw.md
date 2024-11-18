---
title: The Products class
---
This document will provide an overview of the `Products` class. We will cover:

1. What `Products` is.
2. Variables and functions defined in `Products`.

# What is Products

The `Products` class in `src/main/java/com/Maven/web/HibernateEcommerceWebApp/entities/Products.java` represents a product entity in the e-commerce web application. It is used to store and manage information about products available in the online store. This class is annotated with `@Entity`, indicating that it is a JPA entity and will be mapped to a database table.

<SwmSnippet path="/src/main/java/com/Maven/web/HibernateEcommerceWebApp/entities/Products.java" line="27" repo-id="Z2l0aHViJTNBJTNBZWNvbW1lcmNlLXdlYmFwcC1oaWJlcm5hdGUtc2VydmxldCUzQSUzQVN3aW1tLURlbW8=">

---

# Variables and functions

The default constructor `Products` is used to create an instance of the `Products` class without setting any initial values.

```java
	public Products() {
		super();
	}
```

---

</SwmSnippet>

<SwmSnippet path="/src/main/java/com/Maven/web/HibernateEcommerceWebApp/entities/Products.java" line="34" repo-id="Z2l0aHViJTNBJTNBZWNvbW1lcmNlLXdlYmFwcC1oaWJlcm5hdGUtc2VydmxldCUzQSUzQVN3aW1tLURlbW8=">

---

The parameterized constructor `Products` is used to create an instance of the `Products` class with specified values for `productName`, `productDiscription`, `productPic`, `productPrice`, `category`, `productDiscount`, and `productQuantity`.

```java
	public Products(String productName, String productDiscription, String productPic, int productPrice ,Category category,
			int productDiscount, int productQuantity) {
		super();
		this.productName = productName;
		this.productDiscription = productDiscription;
		this.productPic = productPic;
		this.productPrice = productPrice;
		this.productDiscount = productDiscount;
		this.productQuantity = productQuantity;
		this.category=category;
	}
```

---

</SwmSnippet>

<SwmSnippet path="/src/main/java/com/Maven/web/HibernateEcommerceWebApp/entities/Products.java" line="46" repo-id="Z2l0aHViJTNBJTNBZWNvbW1lcmNlLXdlYmFwcC1oaWJlcm5hdGUtc2VydmxldCUzQSUzQVN3aW1tLURlbW8=">

---

The function `getProductId` returns the ID of the product.

```java
	public int getProductId() {
		return productId;
	}
```

---

</SwmSnippet>

<SwmSnippet path="/src/main/java/com/Maven/web/HibernateEcommerceWebApp/entities/Products.java" line="50" repo-id="Z2l0aHViJTNBJTNBZWNvbW1lcmNlLXdlYmFwcC1oaWJlcm5hdGUtc2VydmxldCUzQSUzQVN3aW1tLURlbW8=">

---

The function `setProductId` sets the ID of the product.

```java
	public void setProductId(int productId) {
		this.productId = productId;
	}
```

---

</SwmSnippet>

<SwmSnippet path="/src/main/java/com/Maven/web/HibernateEcommerceWebApp/entities/Products.java" line="54" repo-id="Z2l0aHViJTNBJTNBZWNvbW1lcmNlLXdlYmFwcC1oaWJlcm5hdGUtc2VydmxldCUzQSUzQVN3aW1tLURlbW8=">

---

The function `getProductName` returns the name of the product.

```java
	public String getProductName() {
		return productName;
	}
```

---

</SwmSnippet>

<SwmSnippet path="/src/main/java/com/Maven/web/HibernateEcommerceWebApp/entities/Products.java" line="58" repo-id="Z2l0aHViJTNBJTNBZWNvbW1lcmNlLXdlYmFwcC1oaWJlcm5hdGUtc2VydmxldCUzQSUzQVN3aW1tLURlbW8=">

---

The function `setProductName` sets the name of the product.

```java
	public void setProductName(String productName) {
		this.productName = productName;
	}
```

---

</SwmSnippet>

<SwmSnippet path="/src/main/java/com/Maven/web/HibernateEcommerceWebApp/entities/Products.java" line="62" repo-id="Z2l0aHViJTNBJTNBZWNvbW1lcmNlLXdlYmFwcC1oaWJlcm5hdGUtc2VydmxldCUzQSUzQVN3aW1tLURlbW8=">

---

The function `getProductDiscription` returns the description of the product.

```java
	public String getProductDiscription() {
		return productDiscription;
	}
```

---

</SwmSnippet>

<SwmSnippet path="/src/main/java/com/Maven/web/HibernateEcommerceWebApp/entities/Products.java" line="66" repo-id="Z2l0aHViJTNBJTNBZWNvbW1lcmNlLXdlYmFwcC1oaWJlcm5hdGUtc2VydmxldCUzQSUzQVN3aW1tLURlbW8=">

---

The function `setProductDiscription` sets the description of the product.

```java
	public void setProductDiscription(String productDiscription) {
		this.productDiscription = productDiscription;
	}
```

---

</SwmSnippet>

<SwmSnippet path="/src/main/java/com/Maven/web/HibernateEcommerceWebApp/entities/Products.java" line="70" repo-id="Z2l0aHViJTNBJTNBZWNvbW1lcmNlLXdlYmFwcC1oaWJlcm5hdGUtc2VydmxldCUzQSUzQVN3aW1tLURlbW8=">

---

The function `getProductPic` returns the picture URL of the product.

```java
	public String getProductPic() {
		return productPic;
	}
```

---

</SwmSnippet>

<SwmSnippet path="/src/main/java/com/Maven/web/HibernateEcommerceWebApp/entities/Products.java" line="74" repo-id="Z2l0aHViJTNBJTNBZWNvbW1lcmNlLXdlYmFwcC1oaWJlcm5hdGUtc2VydmxldCUzQSUzQVN3aW1tLURlbW8=">

---

The function `setProductPic` sets the picture URL of the product.

```java
	public void setProductPic(String productPic) {
		this.productPic = productPic;
	}
```

---

</SwmSnippet>

<SwmSnippet path="/src/main/java/com/Maven/web/HibernateEcommerceWebApp/entities/Products.java" line="78" repo-id="Z2l0aHViJTNBJTNBZWNvbW1lcmNlLXdlYmFwcC1oaWJlcm5hdGUtc2VydmxldCUzQSUzQVN3aW1tLURlbW8=">

---

The function `getProductPrice` returns the price of the product.

```java
	public int getProductPrice() {
		return productPrice;
	}
```

---

</SwmSnippet>

<SwmSnippet path="/src/main/java/com/Maven/web/HibernateEcommerceWebApp/entities/Products.java" line="82" repo-id="Z2l0aHViJTNBJTNBZWNvbW1lcmNlLXdlYmFwcC1oaWJlcm5hdGUtc2VydmxldCUzQSUzQVN3aW1tLURlbW8=">

---

The function `setProductPrice` sets the price of the product.

```java
	public void setProductPrice(int productPrice) {
		this.productPrice = productPrice;
	}
```

---

</SwmSnippet>

<SwmSnippet path="/src/main/java/com/Maven/web/HibernateEcommerceWebApp/entities/Products.java" line="86" repo-id="Z2l0aHViJTNBJTNBZWNvbW1lcmNlLXdlYmFwcC1oaWJlcm5hdGUtc2VydmxldCUzQSUzQVN3aW1tLURlbW8=">

---

The function `getProductDiscount` returns the discount percentage of the product.

```java
	public int getProductDiscount() {
		return productDiscount;
	}
```

---

</SwmSnippet>

<SwmSnippet path="/src/main/java/com/Maven/web/HibernateEcommerceWebApp/entities/Products.java" line="90" repo-id="Z2l0aHViJTNBJTNBZWNvbW1lcmNlLXdlYmFwcC1oaWJlcm5hdGUtc2VydmxldCUzQSUzQVN3aW1tLURlbW8=">

---

The function `setProductDiscount` sets the discount percentage of the product.

```java
	public void setProductDiscount(int productDiscount) {
		this.productDiscount = productDiscount;
	}
```

---

</SwmSnippet>

<SwmSnippet path="/src/main/java/com/Maven/web/HibernateEcommerceWebApp/entities/Products.java" line="94" repo-id="Z2l0aHViJTNBJTNBZWNvbW1lcmNlLXdlYmFwcC1oaWJlcm5hdGUtc2VydmxldCUzQSUzQVN3aW1tLURlbW8=">

---

The function `getProductQuantity` returns the quantity of the product available in stock.

```java
	public int getProductQuantity() {
		return productQuantity;
	}
```

---

</SwmSnippet>

<SwmSnippet path="/src/main/java/com/Maven/web/HibernateEcommerceWebApp/entities/Products.java" line="98" repo-id="Z2l0aHViJTNBJTNBZWNvbW1lcmNlLXdlYmFwcC1oaWJlcm5hdGUtc2VydmxldCUzQSUzQVN3aW1tLURlbW8=">

---

The function `setProductQuantity` sets the quantity of the product available in stock.

```java
	public void setProductQuantity(int productQuantity) {
		this.productQuantity = productQuantity;
	}
```

---

</SwmSnippet>

<SwmSnippet path="/src/main/java/com/Maven/web/HibernateEcommerceWebApp/entities/Products.java" line="102" repo-id="Z2l0aHViJTNBJTNBZWNvbW1lcmNlLXdlYmFwcC1oaWJlcm5hdGUtc2VydmxldCUzQSUzQVN3aW1tLURlbW8=">

---

The function `getCategory` returns the category of the product.

```java
	public Category getCategory() {
		return category;
	}
```

---

</SwmSnippet>

<SwmSnippet path="/src/main/java/com/Maven/web/HibernateEcommerceWebApp/entities/Products.java" line="106" repo-id="Z2l0aHViJTNBJTNBZWNvbW1lcmNlLXdlYmFwcC1oaWJlcm5hdGUtc2VydmxldCUzQSUzQVN3aW1tLURlbW8=">

---

The function `setCategory` sets the category of the product.

```java
	public void setCategory(Category category) {
		this.category = category;
	}
```

---

</SwmSnippet>

<SwmSnippet path="/src/main/java/com/Maven/web/HibernateEcommerceWebApp/entities/Products.java" line="110" repo-id="Z2l0aHViJTNBJTNBZWNvbW1lcmNlLXdlYmFwcC1oaWJlcm5hdGUtc2VydmxldCUzQSUzQVN3aW1tLURlbW8=">

---

The function `getPriceDiscount` calculates and returns the price of the product after applying the discount.

```java
	public int getPriceDiscount()
	{
		int discount=(int)((this.getProductDiscount()/100.0)*this.getProductPrice());
		
		return this.getProductPrice()-discount;
	}
```

---

</SwmSnippet>

&nbsp;

*This is an auto-generated document by Swimm 🌊 and has not yet been verified by a human*

<SwmMeta version="3.0.0" repo-id="Z2l0aHViJTNBJTNBZWNvbW1lcmNlLXdlYmFwcC1oaWJlcm5hdGUtc2VydmxldCUzQSUzQVN3aW1tLURlbW8=" repo-name="ecommerce-webapp-hibernate-servlet"><sup>Powered by [Swimm](https://staging.swimm.cloud/)</sup></SwmMeta>
