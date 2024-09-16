```markdown
# University Models - Django Application

This Django application, **University Models**, provides a database structure for managing universities, faculties,
departments, and other related entities. It is built using Django's ORM (Object-Relational Mapping) system.

## Features

- Manage universities, faculties, and departments
- Create, retrieve, update, and delete (CRUD) university data
- Easy-to-use admin interface for managing data
- Well-organized models for extending university features

## Installation

To get this application up and running on your local machine, follow these steps:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/AkramovFozil/unyversity_model.git
   ```

2. **Navigate to the project directory:**

   ```bash
   cd University project
   ```

3. **Set up a virtual environment (optional but recommended):**

   ```bash
   python -m venv venv
   source venv/bin/activate  # For Linux/macOS
   venv\Scripts\activate  # For Windows
   ```

4. **Install the required dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

5. **Apply migrations to set up the database:**

   ```bash
   python manage.py migrate
   ```

6. **Create a superuser (admin) for the Django admin interface:**

   ```bash
   python manage.py createsuperuser
   ```

7. **Run the development server:**

   ```bash
   python manage.py runserver
   ```

8. **Access the admin interface:**

   Open your browser and navigate to [http://127.0.0.1:8000/admin/](http://127.0.0.1:8000/admin/) to manage
   universities, faculties, departments, and students.

## Usage

- Use the admin panel to create universities, faculties, and departments.
- Add students to departments via the Django admin interface.

## Example

Here’s how the model relationships are structured:

1. A university can have many faculties.
2. A faculty can have multiple departments.
3. A department can have multiple students.

**Diagram Example**:

```
University
   ├── Faculty 1
   │   ├── Kafedra 1
   │   │   ├── Student 1
   │   │   ├── Student 2
   │   ├── Kafedra 2
   ├── Faculty 2
```

## Contribution

Feel free to fork this repository and submit pull requests for any improvements or fixes.

## Contact

For questions or suggestions, please email us at [fozil.9909@gmail.com].

```

### Qadamlar tushuntirilishi:
- **Loyiha tuzilishi**: Loyiha qanday tashkil etilganini tushuntiradi va qaysi modellar borligini ta'riflaydi.
- **O'rnatish**: Loyiha uchun zarur qadamlar va talablar qanday ekanligini tushuntiradi.
- **Admin interfeysi**: Django admin interfeysi orqali qanday ishlashni tushuntiradi.
