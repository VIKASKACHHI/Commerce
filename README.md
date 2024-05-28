# Commerce-
A website like ebay that is to bid on different product added by the user

## Features

1. **User Authentication**: Users can register, log in, and log out.
2. **Create Listings**: Authenticated users can create new auction listings.
3. **Bid on Listings**: Authenticated users can place bids on active listings.
4. **Add Comments**: Authenticated users can add comments to listings.
5. **Watchlist**: Users can add or remove listings from their watchlist.
6. **Category Filtering**: Users can browse listings by category.
7. **Image Upload**: Users can upload images for their listings.

## Setup and Installation

1. **Clone the repository**:

    ```sh
    git clone https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git
    cd YOUR_REPOSITORY_NAME
    ```

2. **Create and activate a virtual environment**:

    ```sh
    python -m venv .venv
    .venv\Scripts\activate  # On Windows
    # source .venv/bin/activate  # On macOS/Linux
    ```

3. **Install dependencies**:

    ```sh
    pip install -r requirements.txt
    ```

4. **Run migrations**:

    ```sh
    python manage.py migrate
    ```

5. **Create a superuser**:

    ```sh
    python manage.py createsuperuser
    ```

6. **Run the development server**:

    ```sh
    python manage.py runserver
    ```

7. **Access the site**:

    Open your web browser and go to `http://127.0.0.1:8000`.

## Usage

- **Home Page**: View all active auction listings.
- **Create Listing**: Click on "Create Listing" to add a new auction listing.
- **Watchlist**: Add or remove listings from your watchlist.
- **Bid**: Place bids on active listings.
- **Comments**: Add comments to listings.

## Demonstration Video

A screencast demonstrating the functionality of this project can be found [here](LINK_TO_YOUR_VIDEO).

### Timestamps:

- **User Authentication**: 00:00 - 00:30
- **Create Listings**: 00:30 - 01:00
- **Bid on Listings**: 01:00 - 01:30
- **Add Comments**: 01:30 - 02:00
- **Watchlist**: 02:00 - 02:30
- **Category Filtering**: 02:30 - 03:00
- **Image Upload**: 03:00 - 03:30

