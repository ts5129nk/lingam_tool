docker build . -t lingam_img
docker run -it --rm --name lingam_tmp -p 8502:8501 lingam_img streamlit run app.py