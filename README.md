theme: ThemeData(
  brightness: Brightness.light,
  primaryColor: Color(0xFF0A0E21),
  scaffoldBackgroundColor: Color(0xFFF8F9FA),
  appBarTheme: AppBarTheme(
    color: Color(0xFF0A0E21),
    centerTitle: true,
    elevation: 4,
    titleTextStyle: TextStyle(
      color: Colors.white,
      fontSize: 22,
      fontWeight: FontWeight.bold,
    ),
  ),
  inputDecorationTheme: InputDecorationTheme(
    border: OutlineInputBorder(
      borderRadius: BorderRadius.circular(12.0),
    ),
    filled: true,
    fillColor: Colors.white,
    labelStyle: TextStyle(color: Colors.black87),
  ),
  elevatedButtonTheme: ElevatedButtonThemeData(
    style: ElevatedButton.styleFrom(
      backgroundColor: Color(0xFF0A0E21),
      foregroundColor: Colors.white,
      padding: EdgeInsets.symmetric(vertical: 14, horizontal: 20),
      textStyle: TextStyle(fontSize: 16, fontWeight: FontWeight.bold),
      shape: RoundedRectangleBorder(
        borderRadius: BorderRadius.circular(12.0),
      ),
    ),
  ),
  textTheme: TextTheme(
    bodyLarge: TextStyle(fontSize: 18.0),
    bodyMedium: TextStyle(fontSize: 16.0),
  ),
),

