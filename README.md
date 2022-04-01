# st.selectbox
`st.selectbox` display a select widget. 

## Demo app
[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://share.streamlit.io/dataprofessor/st.selectbox/)

## Code
Contents of the `streamlit_app.py` file:
```python
import streamlit as st

option = st.selectbox(
     'What is your favorite color?',
     ('Blue', 'Red', 'Green'))

st.write('Your favorite color is ', option)
```

## References
Read about [`st.selectbox`](https://docs.streamlit.io/library/api-reference/widgets/st.selectbox) in the Streamlit API Documentation.
