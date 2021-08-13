# Maps

void main() {
  Map<int, Map<String, dynamic>> std = {
    1: {
      'name': 'ahmed',
      'age': 20,
      'score': {
        'Math': 10,
        'language': 60,
      },
      'Family Member': [
        {
          'Father Name': 'He one',
          'Father Age': 50,
        },
        {
          'Mother Name': 'She one',
          'Mother Age': 40,
        },
      ]
    },
    2: {
      'name': 'Sara',
      'age': 30,
      'score': {
        'Math': 20,
        'language': 70,
      },
      'Family Member': [
        {
          'Father Name': 'He tow',
          'Father Age': 50,
        },
        {
          'Mother Name': 'She tow',
          'Mother Age': 40,
        },
      ]
    },
    3: {
      'name': 'salma',
      'age': 25,
      'score': {
        'Math': 30,
        'language': 80,
      },
      'Family Member': [
        {
          'Father Name': 'He three',
          'Father Age': 50,
        },
        {
          'Mother Name': 'She three',
          'Mother Age': 40,
        },
      ]
    },
  };
  print('''
Student Name is: ${std[3]!['name']},
Student Age is: ${std[3]!['age']},
Score in Math : ${std[3]!['score']['Math']},
Score in language : ${std[3]!['score']['language']},
Student Father Name : ${std[3]!['Family Member'][0]['Father Name']},
Student Father Age : ${std[3]!['Family Member'][0]['Father Age']},
Student Mother Name : ${std[3]!['Family Member'][0]['Mother Name']},
Student Mother Age : ${std[3]!['Family Member'][0]['Mother Age']},




''');
}
