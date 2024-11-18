---
title: The Category class
---
This document will cover the `Category` class. We will explain:

1. What `Category` is.
2. The variables and functions defined in `Category`.

# What is Category

The `Category` class in `src/main/java/com/Maven/web/HibernateEcommerceWebApp/entities/Category.java` represents a category of products in the e-commerce application. It is used to store information about different product categories, such as the category ID, title, and description. This class is also responsible for maintaining a list of products that belong to the category.

<SwmSnippet path="/src/main/java/com/Maven/web/HibernateEcommerceWebApp/entities/Category.java" line="26" repo-id="Z2l0aHViJTNBJTNBZWNvbW1lcmNlLXdlYmFwcC1oaWJlcm5hdGUtc2VydmxldCUzQSUzQVN3aW1tLURlbW8=">

---

# Variables and functions

The default constructor `Category()` initializes a new instance of the `Category` class without setting any properties.

```java
	public Category() {
		super();
	}
```

---

</SwmSnippet>

<SwmSnippet path="/src/main/java/com/Maven/web/HibernateEcommerceWebApp/entities/Category.java" line="30" repo-id="Z2l0aHViJTNBJTNBZWNvbW1lcmNlLXdlYmFwcC1oaWJlcm5hdGUtc2VydmxldCUzQSUzQVN3aW1tLURlbW8=">

---

The constructor `Category(List<Products> products)` initializes a new instance of the `Category` class and sets the `products` property.

```java
	public Category(List<Products> products) {
		super();
		this.products = products;
	}
```

---

</SwmSnippet>

<SwmSnippet path="/src/main/java/com/Maven/web/HibernateEcommerceWebApp/entities/Category.java" line="35" repo-id="Z2l0aHViJTNBJTNBZWNvbW1lcmNlLXdlYmFwcC1oaWJlcm5hdGUtc2VydmxldCUzQSUzQVN3aW1tLURlbW8=">

---

The constructor `Category(int categoryId, String categoryTitle, String categoryDiscription)` initializes a new instance of the `Category` class and sets the `categoryId`, `categoryTitle`, and `categoryDiscription` properties.

```java
	public Category(int categoryId, String categoryTitle, String categoryDiscription) {
		super();
		this.categoryId = categoryId;
		this.categoryTitle = categoryTitle;
		this.categoryDiscription = categoryDiscription;
	}
```

---

</SwmSnippet>

<SwmSnippet path="/src/main/java/com/Maven/web/HibernateEcommerceWebApp/entities/Category.java" line="42" repo-id="Z2l0aHViJTNBJTNBZWNvbW1lcmNlLXdlYmFwcC1oaWJlcm5hdGUtc2VydmxldCUzQSUzQVN3aW1tLURlbW8=">

---

The function `getCategoryId()` returns the ID of the category.

```java
	public int getCategoryId() {
		return categoryId;
	}
```

---

</SwmSnippet>

<SwmSnippet path="/src/main/java/com/Maven/web/HibernateEcommerceWebApp/entities/Category.java" line="46" repo-id="Z2l0aHViJTNBJTNBZWNvbW1lcmNlLXdlYmFwcC1oaWJlcm5hdGUtc2VydmxldCUzQSUzQVN3aW1tLURlbW8=">

---

The function `setCategoryId(int categoryId)` sets the ID of the category.

```java
	public void setCategoryId(int categoryId) {
		this.categoryId = categoryId;
	}
```

---

</SwmSnippet>

<SwmSnippet path="/src/main/java/com/Maven/web/HibernateEcommerceWebApp/entities/Category.java" line="50" repo-id="Z2l0aHViJTNBJTNBZWNvbW1lcmNlLXdlYmFwcC1oaWJlcm5hdGUtc2VydmxldCUzQSUzQVN3aW1tLURlbW8=">

---

The function `getCategoryTitle()` returns the title of the category.

```java
	public String getCategoryTitle() {
		return categoryTitle;
	}
```

---

</SwmSnippet>

<SwmSnippet path="/src/main/java/com/Maven/web/HibernateEcommerceWebApp/entities/Category.java" line="54" repo-id="Z2l0aHViJTNBJTNBZWNvbW1lcmNlLXdlYmFwcC1oaWJlcm5hdGUtc2VydmxldCUzQSUzQVN3aW1tLURlbW8=">

---

The function `setCategoryTitle(String categoryTitle)` sets the title of the category.

```java
	public void setCategoryTitle(String categoryTitle) {
		this.categoryTitle = categoryTitle;
	}
```

---

</SwmSnippet>

<SwmSnippet path="/src/main/java/com/Maven/web/HibernateEcommerceWebApp/entities/Category.java" line="58" repo-id="Z2l0aHViJTNBJTNBZWNvbW1lcmNlLXdlYmFwcC1oaWJlcm5hdGUtc2VydmxldCUzQSUzQVN3aW1tLURlbW8=">

---

The function `getCategoryDiscription()` returns the description of the category.

```java
	public String getCategoryDiscription() {
		return categoryDiscription;
	}
```

---

</SwmSnippet>

<SwmSnippet path="/src/main/java/com/Maven/web/HibernateEcommerceWebApp/entities/Category.java" line="62" repo-id="Z2l0aHViJTNBJTNBZWNvbW1lcmNlLXdlYmFwcC1oaWJlcm5hdGUtc2VydmxldCUzQSUzQVN3aW1tLURlbW8=">

---

The function `setCategoryDiscription(String categoryDiscription)` sets the description of the category.

```java
	public void setCategoryDiscription(String categoryDiscription) {
		this.categoryDiscription = categoryDiscription;
	}
```

---

</SwmSnippet>

<SwmSnippet path="/src/main/java/com/Maven/web/HibernateEcommerceWebApp/entities/Category.java" line="66" repo-id="Z2l0aHViJTNBJTNBZWNvbW1lcmNlLXdlYmFwcC1oaWJlcm5hdGUtc2VydmxldCUzQSUzQVN3aW1tLURlbW8=">

---

The function `getProducts()` returns the list of products that belong to the category.

```java
	public List<Products> getProducts() {
		return products;
	}
```

---

</SwmSnippet>

<SwmSnippet path="/src/main/java/com/Maven/web/HibernateEcommerceWebApp/entities/Category.java" line="70" repo-id="Z2l0aHViJTNBJTNBZWNvbW1lcmNlLXdlYmFwcC1oaWJlcm5hdGUtc2VydmxldCUzQSUzQVN3aW1tLURlbW8=">

---

The function `setProducts(List<Products> products)` sets the list of products that belong to the category.

```java
	public void setProducts(List<Products> products) {
		this.products = products;
	}
```

---

</SwmSnippet>

<SwmSnippet path="/src/main/java/com/Maven/web/HibernateEcommerceWebApp/entities/Category.java" line="74" repo-id="Z2l0aHViJTNBJTNBZWNvbW1lcmNlLXdlYmFwcC1oaWJlcm5hdGUtc2VydmxldCUzQSUzQVN3aW1tLURlbW8=">

---

The function `toString()` returns a string representation of the `Category` object, including the category ID, title, and description.

```java
	@Override
	public String toString() {
		return "Category [categoryId=" + categoryId + ", categoryTitle=" + categoryTitle + ", categoryDiscription="
				+ categoryDiscription + "]";
	}
```

---

</SwmSnippet>

&nbsp;

*This is an auto-generated document by Swimm 🌊 and has not yet been verified by a human*

<SwmMeta version="3.0.0" repo-id="Z2l0aHViJTNBJTNBZWNvbW1lcmNlLXdlYmFwcC1oaWJlcm5hdGUtc2VydmxldCUzQSUzQVN3aW1tLURlbW8=" repo-name="ecommerce-webapp-hibernate-servlet"><sup>Powered by [Swimm](https://staging.swimm.cloud/)</sup></SwmMeta>
