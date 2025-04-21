import 'package:flutter/material.dart';
void main() => runApp(MyApp());
class MyApp extends StatelessWidget {
 @override
 Widget build(BuildContext context) {
 return MaterialApp(
 home: ColumnDemo(),
 );
 }
}
class ColumnDemo extends StatelessWidget {
 @override
Widget build(BuildContext context) {
 return Scaffold(
 appBar: AppBar(title: Text('Column Widget')),
 body: Center(
 child: Column(
 mainAxisAlignment: MainAxisAlignment.center,
 children: [
 Icon(Icons.phone, size: 40, color: Colors.blue),
 SizedBox(height: 10),
 Text('Call', style: TextStyle(fontSize: 18)),
 ],
 ),
 ),
 );
 }
}
