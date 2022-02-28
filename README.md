# st-selectbox

Read about [`st.selectbox`](https://docs.streamlit.io/library/api-reference/widgets/st.selectbox) in the Streamlit API Documentation.

## Demo app
[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://share.streamlit.io/dataprofessor/st-selectbox/)

## Code
Contents of the `streamlit_app.py` file:
```python
import streamlit as st

option = st.selectbox(
     'How would you like to be contacted?',
     ('Email', 'Home phone', 'Mobile phone'))

st.write('You selected:', option)
```
