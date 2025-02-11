# -Real-time-Fact-Checking
import streamlit as st

# Title of the app
st.title("Real-time Fact-Checking System")

# Input field for the claim
claim = st.text_input("Enter a claim:")

# Button to check the claim
if st.button("Check"):
    if claim:
        st.write(f"You entered: {claim}")
    else:
        st.warning("Please enter a claim.")
