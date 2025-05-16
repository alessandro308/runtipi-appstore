# Omnivore

Omnivore is an open source read-it-later app that helps you save and organize your reading. It's a great alternative to Pocket, Instapaper, and other read-it-later services.

## Features

- Save articles, blog posts, and other web content for later reading
- Organize your reading with labels and highlights
- Sync across all your devices
- Open source and self-hostable
- Modern, clean interface
- Support for highlights and annotations
- Email newsletter support
- RSS feed support
- PDF upload and reading
- Mobile apps for iOS and Android

## Requirements

- PostgreSQL database (included)
- Redis (included)
- MinIO for file storage (included)

## Configuration

The following environment variables are required:

- `POSTGRES_PASSWORD`: Password for the PostgreSQL database
- `JWT_SECRET`: Secret key for JWT authentication
- `ADMIN_EMAIL`: Email address for the admin user
- `ADMIN_PASSWORD`: Password for the admin user

## Access

Once installed, you can access Omnivore at:

- Web interface: `https://omnivore.yourdomain.com`
- API: `https://omnivore.yourdomain.com/api`

## Support

For support, please visit:
- [GitHub Repository](https://github.com/omnivore-app/omnivore)
- [Documentation](https://docs.omnivore.app) 