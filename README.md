# Gestor de Órdenes en Nest.js

Este repositorio aloja un proyecto Nest.js diseñado para gestionar órdenes recibidas a través de una solicitud POST, imprimir los detalles de la orden en formato de tabla y devolver la orden con un identificador aleatorio generado.

## Funcionalidades

The project establishes a controller with a dedicated endpoint that accepts the URL or the path of an email file as a parameter. This endpoint is crafted to respond with the JSON data extracted from the email in the following scenarios:

1. **Recibir Orden**: El controlador acepta una solicitud POST que incluye los detalles de una orden en formato JSON.

2. **Imprimir Orden**: Los detalles de la orden se imprimen en formato de tabla para su visualización clara y organizada.

3. **Generar Identificador Aleatorio**: Se genera un identificador aleatorio para la orden recibida y se incluye en la respuesta devuelta al cliente.

## Getting Started

To get started with this project, follow these steps:

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/JosueG15/boxful-backend-challenge.git
   cd boxful-backend-challenge
   ```

2. **Install Dependencies**:

   ```bash
   npm install
   ```

3. **Run the Project**:
   ```bash
   npm run start
   ```

Now, the server will be running, and you can send HTTP requests to the endpoint to test the JSON extraction functionality.

## Testing

This project employs a Test-Driven Development (TDD) approach. You can run the test suite using the following command:

```bash
npm run test
```

## Contributing

Feel free to fork the repository, create a feature branch, and open a Pull Request if you have enhancements or bug fixes you'd like to contribute.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.
