# Encode a guid with base32 encoding in C# / .Net

Voorbeeld om een guid met base32 encoding naar een string van 26 karakters om te zetten, zodat deze te gebruiken is als referentie.

	Guid id = Guid.NewGuid();
	string encodedGuid = Base32Encoding.ToString(id);


