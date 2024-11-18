---
title: The User class
---
This document will cover the `User` class in the repository. We will explain:

1. What the `User` class is and its purpose.
2. The variables and functions defined in the `User` class.

# What is User

The `User` class in `src/main/java/com/Maven/web/HibernateEcommerceWebApp/entities/User.java` represents a user entity in the e-commerce web application. It is used to store and manage user-related information such as user ID, name, email, password, phone number, profile picture, address, and user type. This class is mapped to a database table using Hibernate ORM annotations.

<SwmSnippet path="/src/main/java/com/Maven/web/HibernateEcommerceWebApp/entities/User.java" line="10" repo-id="Z2l0aHViJTNBJTNBZWNvbW1lcmNlLXdlYmFwcC1oaWJlcm5hdGUtc2VydmxldCUzQSUzQVN3aW1tLURlbW8=">

---

# Variables and functions

The `User` class is defined as a public class and is annotated with `@Entity` to indicate that it is a JPA entity.

```java
public class User {
```

---

</SwmSnippet>

<SwmSnippet path="/src/main/java/com/Maven/web/HibernateEcommerceWebApp/entities/User.java" line="32" repo-id="Z2l0aHViJTNBJTNBZWNvbW1lcmNlLXdlYmFwcC1oaWJlcm5hdGUtc2VydmxldCUzQSUzQVN3aW1tLURlbW8=">

---

The constructor `User` initializes a new user object with the provided parameters: `userName`, `userEmail`, `userPassword`, `userPhone`, `userPic`, `userAddress`, and `user_type`.

```java
	public User(String userName, String userEmail, String userPassword, String userPhone, String userPic,
			String userAddress, String user_type) {
		super();
		this.userName = userName;
		this.userEmail = userEmail;
		this.userPassword = userPassword;
		this.userPhone = userPhone;
		this.userPic = userPic;
		this.userAddress = userAddress;
		this.user_type=user_type;
	}
```

---

</SwmSnippet>

<SwmSnippet path="/src/main/java/com/Maven/web/HibernateEcommerceWebApp/entities/User.java" line="45" repo-id="Z2l0aHViJTNBJTNBZWNvbW1lcmNlLXdlYmFwcC1oaWJlcm5hdGUtc2VydmxldCUzQSUzQVN3aW1tLURlbW8=">

---

The default constructor `User` initializes a new user object without any parameters.

```java
	public User() {
		super();
	}
```

---

</SwmSnippet>

<SwmSnippet path="/src/main/java/com/Maven/web/HibernateEcommerceWebApp/entities/User.java" line="50" repo-id="Z2l0aHViJTNBJTNBZWNvbW1lcmNlLXdlYmFwcC1oaWJlcm5hdGUtc2VydmxldCUzQSUzQVN3aW1tLURlbW8=">

---

The function `getUserId` returns the user ID of the user.

```java
	public int getUserId() {
		return userId;
	}
```

---

</SwmSnippet>

<SwmSnippet path="/src/main/java/com/Maven/web/HibernateEcommerceWebApp/entities/User.java" line="54" repo-id="Z2l0aHViJTNBJTNBZWNvbW1lcmNlLXdlYmFwcC1oaWJlcm5hdGUtc2VydmxldCUzQSUzQVN3aW1tLURlbW8=">

---

The function `setUserId` sets the user ID of the user.

```java
	public void setUserId(int userId) {
		this.userId = userId;
	}
```

---

</SwmSnippet>

<SwmSnippet path="/src/main/java/com/Maven/web/HibernateEcommerceWebApp/entities/User.java" line="58" repo-id="Z2l0aHViJTNBJTNBZWNvbW1lcmNlLXdlYmFwcC1oaWJlcm5hdGUtc2VydmxldCUzQSUzQVN3aW1tLURlbW8=">

---

The function `getUserName` returns the user name of the user.

```java
	public String getUserName() {
		return userName;
	}
```

---

</SwmSnippet>

<SwmSnippet path="/src/main/java/com/Maven/web/HibernateEcommerceWebApp/entities/User.java" line="62" repo-id="Z2l0aHViJTNBJTNBZWNvbW1lcmNlLXdlYmFwcC1oaWJlcm5hdGUtc2VydmxldCUzQSUzQVN3aW1tLURlbW8=">

---

The function `setUserName` sets the user name of the user.

```java
	public void setUserName(String userName) {
		this.userName = userName;
	}
```

---

</SwmSnippet>

<SwmSnippet path="/src/main/java/com/Maven/web/HibernateEcommerceWebApp/entities/User.java" line="66" repo-id="Z2l0aHViJTNBJTNBZWNvbW1lcmNlLXdlYmFwcC1oaWJlcm5hdGUtc2VydmxldCUzQSUzQVN3aW1tLURlbW8=">

---

The function `getUserEmail` returns the user email of the user.

```java
	public String getUserEmail() {
		return userEmail;
	}
```

---

</SwmSnippet>

<SwmSnippet path="/src/main/java/com/Maven/web/HibernateEcommerceWebApp/entities/User.java" line="70" repo-id="Z2l0aHViJTNBJTNBZWNvbW1lcmNlLXdlYmFwcC1oaWJlcm5hdGUtc2VydmxldCUzQSUzQVN3aW1tLURlbW8=">

---

The function `setUserEmail` sets the user email of the user.

```java
	public void setUserEmail(String userEmail) {
		this.userEmail = userEmail;
	}
```

---

</SwmSnippet>

<SwmSnippet path="/src/main/java/com/Maven/web/HibernateEcommerceWebApp/entities/User.java" line="74" repo-id="Z2l0aHViJTNBJTNBZWNvbW1lcmNlLXdlYmFwcC1oaWJlcm5hdGUtc2VydmxldCUzQSUzQVN3aW1tLURlbW8=">

---

The function `getUserPassword` returns the user password of the user.

```java
	public String getUserPassword() {
		return userPassword;
	}
```

---

</SwmSnippet>

<SwmSnippet path="/src/main/java/com/Maven/web/HibernateEcommerceWebApp/entities/User.java" line="78" repo-id="Z2l0aHViJTNBJTNBZWNvbW1lcmNlLXdlYmFwcC1oaWJlcm5hdGUtc2VydmxldCUzQSUzQVN3aW1tLURlbW8=">

---

The function `setUserPassword` sets the user password of the user.

```java
	public void setUserPassword(String userPassword) {
		this.userPassword = userPassword;
	}
```

---

</SwmSnippet>

<SwmSnippet path="/src/main/java/com/Maven/web/HibernateEcommerceWebApp/entities/User.java" line="82" repo-id="Z2l0aHViJTNBJTNBZWNvbW1lcmNlLXdlYmFwcC1oaWJlcm5hdGUtc2VydmxldCUzQSUzQVN3aW1tLURlbW8=">

---

The function `getUserPhone` returns the user phone number of the user.

```java
	public String getUserPhone() {
		return userPhone;
	}
```

---

</SwmSnippet>

<SwmSnippet path="/src/main/java/com/Maven/web/HibernateEcommerceWebApp/entities/User.java" line="86" repo-id="Z2l0aHViJTNBJTNBZWNvbW1lcmNlLXdlYmFwcC1oaWJlcm5hdGUtc2VydmxldCUzQSUzQVN3aW1tLURlbW8=">

---

The function `setUserPhone` sets the user phone number of the user.

```java
	public void setUserPhone(String userPhone) {
		this.userPhone = userPhone;
	}
```

---

</SwmSnippet>

<SwmSnippet path="/src/main/java/com/Maven/web/HibernateEcommerceWebApp/entities/User.java" line="90" repo-id="Z2l0aHViJTNBJTNBZWNvbW1lcmNlLXdlYmFwcC1oaWJlcm5hdGUtc2VydmxldCUzQSUzQVN3aW1tLURlbW8=">

---

The function `getUserPic` returns the user profile picture of the user.

```java
	public String getUserPic() {
		return userPic;
	}
```

---

</SwmSnippet>

<SwmSnippet path="/src/main/java/com/Maven/web/HibernateEcommerceWebApp/entities/User.java" line="94" repo-id="Z2l0aHViJTNBJTNBZWNvbW1lcmNlLXdlYmFwcC1oaWJlcm5hdGUtc2VydmxldCUzQSUzQVN3aW1tLURlbW8=">

---

The function `setUserPic` sets the user profile picture of the user.

```java
	public void setUserPic(String userPic) {
		this.userPic = userPic;
	}
```

---

</SwmSnippet>

<SwmSnippet path="/src/main/java/com/Maven/web/HibernateEcommerceWebApp/entities/User.java" line="98" repo-id="Z2l0aHViJTNBJTNBZWNvbW1lcmNlLXdlYmFwcC1oaWJlcm5hdGUtc2VydmxldCUzQSUzQVN3aW1tLURlbW8=">

---

The function `getUserAddress` returns the user address of the user.

```java
	public String getUserAddress() {
		return userAddress;
	}
```

---

</SwmSnippet>

<SwmSnippet path="/src/main/java/com/Maven/web/HibernateEcommerceWebApp/entities/User.java" line="102" repo-id="Z2l0aHViJTNBJTNBZWNvbW1lcmNlLXdlYmFwcC1oaWJlcm5hdGUtc2VydmxldCUzQSUzQVN3aW1tLURlbW8=">

---

The function `setUserAddress` sets the user address of the user.

```java
	public void setUserAddress(String userAddress) {
		this.userAddress = userAddress;
	}
```

---

</SwmSnippet>

<SwmSnippet path="/src/main/java/com/Maven/web/HibernateEcommerceWebApp/entities/User.java" line="107" repo-id="Z2l0aHViJTNBJTNBZWNvbW1lcmNlLXdlYmFwcC1oaWJlcm5hdGUtc2VydmxldCUzQSUzQVN3aW1tLURlbW8=">

---

The function `getUser_type` returns the user type of the user.

```java
	public String getUser_type() {
		return user_type;
	}
```

---

</SwmSnippet>

<SwmSnippet path="/src/main/java/com/Maven/web/HibernateEcommerceWebApp/entities/User.java" line="111" repo-id="Z2l0aHViJTNBJTNBZWNvbW1lcmNlLXdlYmFwcC1oaWJlcm5hdGUtc2VydmxldCUzQSUzQVN3aW1tLURlbW8=">

---

The function `setUser_type` sets the user type of the user.

```java
	public void setUser_type(String user_type) {
		this.user_type = user_type;
	}
```

---

</SwmSnippet>

<SwmSnippet path="/src/main/java/com/Maven/web/HibernateEcommerceWebApp/entities/User.java" line="115" repo-id="Z2l0aHViJTNBJTNBZWNvbW1lcmNlLXdlYmFwcC1oaWJlcm5hdGUtc2VydmxldCUzQSUzQVN3aW1tLURlbW8=">

---

The function `toString` returns a string representation of the user object, including user ID, name, email, password, phone number, profile picture, and address.

```java
	@Override
	public String toString() {
		return "User [userId=" + userId + ", userName=" + userName + ", userEmail=" + userEmail + ", userPassword="
				+ userPassword + ", userPhone=" + userPhone + ", userPic=" + userPic + ", userAddress=" + userAddress
				+ "]";
```

---

</SwmSnippet>

&nbsp;

*This is an auto-generated document by Swimm 🌊 and has not yet been verified by a human*

<SwmMeta version="3.0.0" repo-id="Z2l0aHViJTNBJTNBZWNvbW1lcmNlLXdlYmFwcC1oaWJlcm5hdGUtc2VydmxldCUzQSUzQVN3aW1tLURlbW8=" repo-name="ecommerce-webapp-hibernate-servlet"><sup>Powered by [Swimm](https://staging.swimm.cloud/)</sup></SwmMeta>
