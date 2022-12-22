# myFavoriteLibraries

1. AOS (fade effects)

https://github.com/michalsnik/aos
http://michalsnik.github.io/aos/

  - install

    <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">

    <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
    <script>
      AOS.init();
    </script>
    
  - ussage
    
    <div
    data-aos="fade-up"
    data-aos-offset="200"
    data-aos-delay="50"
    data-aos-duration="1000"
    data-aos-easing="ease-in-out"
    data-aos-mirror="true"
    data-aos-once="false"
    data-aos-anchor-placement="top-center"
  >
  </div>


------------------
import setupLocatorUI from "@locator/runtime"   - component bulmaya yarar. orhan abiden
--------------------
  const callApi = () => {
    console.log("worksss");
  };

  const [debouncedCallApi] = useState(() => _.debounce(callApi, 1000));

  function handleChange() {
    debouncedCallApi();
  }
  
                      onChange={(e) => {
                      setData({
                        ...data,
                        zipCode: e.target.value,
                      });
                      handleChange();
                    }}
                  />
----------------------------------
                  
  

