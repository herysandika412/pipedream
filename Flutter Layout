import 'package:flutter/material.dart';

void main() {
  runApp(MyApp());
}

class MyApp extends StatelessWidget {
  // This widget is the root of your application.
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      home: Scaffold(
        appBar: AppBar(
          title: Text('My Profil'),
          centerTitle: true,
        ),
        body: Container(
          color: Colors.lightBlue,
          child: Column(
            mainAxisAlignment: MainAxisAlignment.center,
            children: <Widget>[
              ClipRRect(
                borderRadius: BorderRadius.circular(90.0),
                child: Image.network('https://mahasiswa.undiksha.ac.id/data/foto/055b4c84838af1afda9511568bdfe99a20180705040757.jpg',
                width: 140.0,
                  height:140.0,
                  fit: BoxFit.cover,
                ),
              ),
              Text(''
                  'Putu Hery Andi Sandika',
              style: TextStyle(
                color: Colors.yellowAccent,
                fontSize: 30,
                fontWeight: FontWeight.bold),
              ),
              Card(
                margin: EdgeInsets.only(top: 20.0),
                color: Colors.black38,
                child: Row(
                  mainAxisAlignment: MainAxisAlignment.spaceEvenly,
                  mainAxisSize: MainAxisSize.max,
                  crossAxisAlignment: CrossAxisAlignment.center,
                  children: <Widget>[
                    Expanded(
                      child: Card(
                        color: Colors.amber,
                        margin: EdgeInsets.only(left: 5.0, right: 5.0),
                        child: Column(
                          children: <Widget>[
                            Icon(Icons.my_location, size: 70, color: Colors.white),
                            Text(
                              'Kelungkung',
                                  style: TextStyle(
                                    color: Colors.black,
                                    fontSize: 20,
                                    fontWeight: FontWeight.bold),
                                  ),
                          ],
                        ),
                      ),
                    ),
                    Expanded(
                      child: Card(
                        color: Colors.purpleAccent,
                        margin: EdgeInsets.only(left: 5.0, right: 5.0),
                        child: Column(
                          children: <Widget>[
                            Icon(Icons.school, size: 70, color: Colors.white),
                            Text(
                              'Undiksha',
                              style: TextStyle(
                                  color: Colors.black,
                                  fontSize: 20,
                                  fontWeight: FontWeight.bold),
                            ),
                          ],
                        ),
                      ),
                    ),
                  ],
                ),
              ),
        Card(
          margin: EdgeInsets.only(top: 20.0),
          color: Colors.black38,
          child: Row(
            mainAxisAlignment: MainAxisAlignment.spaceEvenly,
            mainAxisSize: MainAxisSize.max,
            crossAxisAlignment: CrossAxisAlignment.center,
            children: <Widget>[
              Expanded(
                child: Card(
                  color: Colors.purpleAccent,
                  margin: EdgeInsets.only(left: 5.0, right: 5.0),
                  child: Column(
                    children: <Widget>[
                      Icon(Icons.favorite, size: 70, color: Colors.white),
                      Text(
                        'Anime',
                        style: TextStyle(
                            color: Colors.black,
                            fontSize: 20,
                            fontWeight: FontWeight.bold),
                      ),
                    ],
                  ),
                ),
              ),
              Expanded(
                child: Card(
                  color: Colors.amber,
                  margin: EdgeInsets.only(left: 5.0, right: 5.0),
                  child: Column(
                    children: <Widget>[
                      Icon(Icons.music_note, size: 70, color: Colors.white),
                      Text(
                        'Pop',
                        style: TextStyle(
                            color: Colors.black,
                            fontSize: 20,
                            fontWeight: FontWeight.bold),
                      ),
                    ],
                  ),
                ),
              ),
            ],
          ),
        ),

          ],
        ),
      ),
    ),
    );
  }
}
